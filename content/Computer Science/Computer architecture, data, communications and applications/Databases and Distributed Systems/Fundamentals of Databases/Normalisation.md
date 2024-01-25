---
banner: "![[computerscience.jpg]]"
---
# Normalisation 

> [!Info] What is Normalisation 
> - The process of dividing larger tables into smaller tables such that these smaller tables are related to each other. 
> - The main motive of normalisation is to reduce data redundancy.

> [!Abstract] Rules for normalising a table 
> - No data is duplicated. If data duplication is avoided, consistency of data can be ensured. As a result, there will no anomalies during data insertion, changes and deletion. 
> - Flexible and Proper structure of a table: A table must allow for a wide range of number of entries to a table. 
> - The structure of table must allow users to run different types of queries to get result.

> [!Info] Stages of Normalisation 
> **1. First Normal Form (1NF)**
> - A table is said to be in first Normal Form (1NF) if none of its attributes are repeated and there is no grouping of attributes.
> - Let us consider Student table of a School database: Student (StudentID, StudentName, Major, CourseID, CourseTitle, TeacherID, TeacherName, Grades)
> - A part of table showing the various courses is given.
> - A student may take several courses. 
> - Each course will have an individual teacher to handle it. 
> - Each course will also have separate grades. 
> ![[Pasted image 20230927135508.png]]
> - In the above table, there will be grouping of courses and several other fields in the table.
> - The best way to solve this is to separate this table into two different tables: 
> - Student (StudentID, StudentName, Major) Course (CourseID, CourseTitle, TeacherID, TeacherName, Grades)
> - Now, the tables are in 1NF form.
> 
> **2. Second Normal Form (2NF)**
> - For a table is to be in second Normal Form (2NF), it must first be in first Normal Form (1NF).
> - If it contains a single primary key, then it is automatically in 2NF.
> - But if the table consists of a composite primary key, all the non-key attributes must be dependent on the complete primary key, that is, no partial dependencies on the primary key.
> - A partial dependency is a state in which the one or more non-key attributes are dependent on only a part of primary key.
> - The Student table and Course table are in 2NF form already because all its entities are completely dependent on their primary key.
> - The CourseGrade table consists of a composite primary key (CourseID, StudentID). 
> - The non-key attribute Grade is dependent on both the primary keys.
> - Hence, the tables are now in 2NF form.
> 	Student (StudentID, StudentName, Major)
> 	Course (CourseID, CourseTitle, TeacherID, TeacherName)
> 	CourseGrade (CourseID, StudentID, Grades)
> - However, there are still some anomalies present.
> - To add teacher information, a course is required.
> - When a course is deleted, the teacher information is automatically deleted.
> - These problems are solved in the next stage of normalisation.
> 
> **3. Third Normal Form (3NF)**
> - For a table is to be in third Normal Form (3NF), if must first be in second Normal Form (2NF) and it must not contain any ‘non-key dependencies’. 
> - Non-key dependency is said to be present when the value of a non-key attribute is functionally dependent on another non-key attribute.
> - Consider the table Course: 
>   Course (CourseID, CourseTitle, TeacherID, TeacherName)
> - The attribute TeacherName is directly associated with TeacherID, but in the table it is defined to be dependent to CourseID. 
> - This is incorrect and creates anomalies.
> - This relation is modified by removing this table and creating two new tables Course and Teacher.
> - The tables in the database now are:
>	Course (CourseID, CourseTitle, TeacherID)
>	Teacher (TeacherID, TeacherName)
>	CourseGrade (CourseID, StudentID, Grades)
>	Student (StudentID, StudentName, Major)
> - Now, the tables are in 3NF.

> [!Tip] Advantages of Normalisation 
> - No data redundancy: Normalisation ensures that data in a table is not repeated on another table. Data redundancy leads to inconsistency and anomalies during data insertion, deletion and modifications.
> - Easy to maintain: Because there are no data duplications, it is enough to update data once. In case of data duplication, we must change the data everywhere it appears, which is tedious and missing updates in a place leads to data inconsistencies.
> - Saves memory space: Because there are no data duplications, a normalised table occupies lesser memory compared to its unnormalised version. 
> - Saves time in searching and sorting: Because of normalisation, we have smaller tables without duplication. Hence, searching and sorting is performed at a faster rate.
> - Prevents accidental deletions: The link between the tables are well-defined. Hence, data in a table that is linked to other tables cannot be deleted accidentally.

> [!Warning] Definitions 
>  **Normalisation**: 
> Normalisation is the process of dividing larger tables into smaller tables such that these smaller tables are related to each other.
> 
>  **First Normal Form (1NF)**:
>  No repeated attributes and no grouping of attributes 
>  
>  **Link table**:
>  Many-to-many relationships always require a link table 
>  
>  **Second Normal Form (2NF)**:
>  Table is in 1NF form & no partial dependencies 
>  
>  **Third Normal Form (3NF)**:
>  Table is in 3NF form & no non-key dependencies

