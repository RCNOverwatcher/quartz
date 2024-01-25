---
banner: "![[computerscience.jpg]]"
---
# Introduction to Hashing Algorithms 

> [!Info] What is Hashing?
> - A hashing algorithm is a mathematical function that transforms input data into a fixed-size string of characters, which is typically used to index and retrieve items in a data structure. 
> - It is a one-way function, meaning that the original input cannot be derived from the output. Hashing algorithms are used in various applications, such as protecting data at rest, ensuring data integrity, and organizing and retrieving files.
> - In the context of file organization, a good hashing algorithm should minimize collisions, ensure uniform distribution of hash codes, and be quick to compute.

> [!Example] Example of Hashing 
> - A database of pupils is going to be organised using a hash file. This file structure has been chosen because the database will be used to deal with pupil/parent enquiries and so needs to retrieve each record quickly.
> - The secretary dealing with enquiries will type in a pupil's surname to get their data back. The database designer has selected the following maths formula, known as a ‘hash algorithm’:
> 	- When a surname is typed in, convert each letter of the surname into a number, and then add the numbers together to give an address. 
> 	- Convert letters to numbers using A=1, B=2, C=3 ... X=24, Y=25, Z=26.
> ---
> In the example provided, a database of pupils is organized using a hash file structure. A hash algorithm is applied to the search data (pupil's surname) to transform it into an address or 'hash code', allowing the computer to directly retrieve the record associated with that hash code. However, it is important to design a good hashing algorithm to minimize clashes and ensure efficient storage utilization.
> 
> Overall, hashing algorithms play a crucial role in fast data access and retrieval, and the design of a good hashing algorithm is essential to ensure efficient and reliable operation of hash file structures.

