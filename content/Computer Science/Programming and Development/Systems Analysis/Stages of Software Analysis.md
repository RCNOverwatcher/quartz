---
banner: "![[computerscience.jpg]]"
---
# Stages of Software Analysis

> [!Info] Ways that projects are initiated
> - A system that is currently in place in an organisation is not doing its job efficiently. Perhaps the business has grown and the system can't cope anymore. Perhaps too many problems keep arising.
> - Perhaps it is a new business that needs a way of solving a problem, e.g. it needs to take on-line payments.
> - Perhaps an old system isn't flexible enough, or costs too much to run.
> - Perhaps there is a change in legislation that requires an existing computer system to be modified in some way.
> - Perhaps the company has heard of some new technology that they think may help them make their business more efficient and give them an advantage over their competitors.
Whatever the reason, a manager will notice that a system needs to be looked at. In the first instance, they will arrange a meeting with a Systems Analyst.

> [!Info] Fact-finding and Information Gathering
> - One-to-one meetings can be valuable as it allows an environment where the systems analyst can easily find out the requirements for the project. The client can easily ask questions and gather their own information about how the project will take place.
> - Questionaires are also useful as they allow large scale data gathering at a very cheap cost. They can also be asked online which can allow more organised data to provide graphs and tables about the audience. However asking good quality questions is hard and open ended questions mean the person filling in the questionaire has to write lots of words which can waste their time.
> - Finally, more open forms of communication can be used such as letters, emails or just a simple phone call. This allows the analyst to gauge exactly what the client wants.

> [!Info] Analysing a systems 
> Sometimes, too much information can be as bad as too little information! A Systems Analyst will quickly amass a large amount of data and information, as they carry out interviews, do questionnaires, collect documents and so on. They need to make sense of it all for the Systems Analysis Report. They would typically do the following things as part of the systems analysis stage:
> 
>  1.  Produce written descriptions of current methods and systems.
>  2.  Draw dataflow diagrams (DFDs).
>  3.  Draw systems flowcharts.
>  4.  Draw Jackson diagrams.
>  5.  Design the data dictionary.
>  6.  Write down descriptions of problems.
>  7.  Write down and agree with the customer the Requirements Specification.
>  8.  Write down possible outline solutions that would satisfy the Requirements Specification.
>  9.  Write down a description of the current hardware and software and what needs to be upgraded or replaced.

> [!Info] Dataflow Diagrams (DFD)
Dataflow diagrams, or DFD diagrams, are used to summarise the flow of data around a system. Written descriptions are fine, but pulling a lot of information together in the form of a diagram helps everyone involved 'see' what is going on in the system a lot easier and systems can then be discussed amongst different people. Because systems such as the library can get quite complicated, they should be broken down into sub-systems, as we have already explained. Each one can then be described and then a DFD can be drawn for each one. There are only four basic symbols in a DFD (not counting the big system box in the Level zero diagram). 
>
> 1.  An oval, representing an entity. This is someone or something that puts information into the system or receives information from it.
> 2.  An arrow, representing a flow of data from one place to another.
> 3.  A box, which represents an action or processing on some data. 
> 4.  A long box, which represents a store of data.
> 
![[qo3iq6u2.bmp|500]]
>
>![[l3zekqxr.bmp|500]]

> [!Info] Systems Flowcharts 
A similar but different type of Dataflow Diagram is known as a ‘systems flowchart’. This type of diagram also gives an overall picture of a system. A systems flowchart shows similar information to DFDs in that it shows the processes that happen on data along with the data flows. In addition, however, these diagrams also show what hardware is used for input, what hardware is used for output and also the data storage devices. They also show what type of file is being used, for example, whether it is a master file or a transaction file. Both system flowcharts and DFDs are used by analysts to show whole systems. A number of symbols are used in systems flowcharts.
![[neazlaw4.bmp|500]]
![[7iisnz57.bmp|500]]

> [!Info] Data dictionary
The data dictionary holds information about data! Any system needs data to make the system work. The Systems Analyst must construct a dictionary of all the data items used in the system because this information will be needed by the people who actually build the new system, who write the software. This point of reference for information about data items is known as the ‘data dictionary’. They tell somebody the form of the data, how each data item is actually made up. Data dictionaries are often best done as a table. A simple data dictionary may just have the name of the data, its data type, the validation rules that apply to it and an example but you may also find a data dictionary with the following headings being used:
> - The name of the data item.
> - What synonyms there are for the data item (different words that mean the same thing e.g. pupil and student. Ideally, every diagram should refer to a 'pupil' or a 'student' but both should not be used across the project as it can lead to confusion.
> - Whether it is a primary key, foreign key, a secondary key or a simple piece of data.
> - Data type. (Whether it is a real number, an integer, a text, a character, a Boolean, a date and so on).
> - Validation rules that apply e.g. the range of allowable values for integers, the number of allowable characters for text, the allowable characters for a character, the way that the date has to be entered using an input mask, the number of decimal points allowed, whether it is required or not and so on.
> - Examples of typical data entries.
> - The origin of the data, where it comes from, how it is generated in the first place, where it is stored.
> - What exactly the data item is used for, what happens to it, why it is part of the system at all.
> - Specification of access rights – who can view, edit or delete the data item.


## Systems Analysis

> [!Info] Written descriptions of problems
> As interviews progress and the Analyst becomes more familiar with the existing system, problems with it will emerge. People using the current system and methods will highlight problems and the Analyst will notice others.
> - System users might complain about things not working as it should.
> - System users might complain about things taking a long time or requiring a lot of paperwork.
> - It might become obvious to the Analyst that some tasks are labour-intensive and could be easily automated.

> [!Info] RS: Requirement Specification 
> When the Analyst has fully investigated the problem area of a business, they should have produced the following deliverables for the Systems Analysis stage of the Systems Life Cycle:
> - Written descriptions of current methods 
> - Flowcharts 
> - A data dictionary 
> - Data-Flow Diagrams 
>---
>In summary, the Analyst now understands the business, the problems in detail and the methods used at the moment. They will not start designing the new system yet, however.
>
>This is because they have not actually agreed with the customer what the final system will be able to do! This is the next job in this stage.

> [!Tip] Smart Requirements 
> - **Specific**: The requirement must outline exactly what needs to be done.
> - **Measurable**: You should be able to write down tests that can measure the requirement. Requirements such as ‘user-friendly’ are difficult to measure. ‘Fast’ is easy to measure because you can set tests e.g. must be able to display a customer’s account details in under 0.5 seconds.
> - **Agreed**: The customer and Project Manager must agree on each requirement and how it will be measured.
> - **Realistic**: Each requirement must be realistically achievable, taking into account the resources and budget.
> - **Trackable**: The project manager must be able to monitor and measure the progress of the achievement of a requirement.

> [!Info] Making an RS
> - The Systems Analyst will use the written description of problems as a starting point to producing the RS. 
>  
> - They will produce a 'draft RS’. In the draft RS, the Analyst will set out what he thinks the customer should expect from the new system, what the new system will be able to do and how success/failure will be measured. 
>  
> - He will then arrange a meeting with the customer so that they can discuss the draft. 
> - Both the customer and the Analyst may well want to make a few changes as a result of the meeting. 
> - The Analyst then goes away and re-drafts the RS. Another meeting is arranged and the re-draft is discussed. 
> - If everyone is happy, both parties sign and date the RS. If more work needs to be done on it, then it is re-drafted again.
	
## System testing and installation planning

> [!Info] Testing 
> Thorough testing should be carried out once the system has been built. It should follow the test plan produced in the Design stage. All results should be documented and cross-referenced just in case there is a problem in the future, to prove that they have been carried out properly and thoroughly. Ensuring that a system works is very important.
> - A company that builds systems has a reputation to protect. They do not want to damage this by producing products that get into the news for the wrong reasons! In some cases, it could cause the company to go bust.
> - They need customers to say good things about the product they bought because 'word of mouth' will generate new business. This will help the company make bigger profits.

> [!Info] Installation 
> - Once a product has been built and tested in the system designer's buildings, it then needs to be installed in the customer's buildings in a way that ensures minimum disruption to the business. Excellent planning is essential to install a new product with the minimum of disruption.
> - Staff training on the new system must take place. This should include those who will use the system and those who will support others in the initial phases of installation, for example the Network Administrator or the various managers. This has implications for the business. If staff are training, they are not working! The cost of this should be taken into account when the project is planned.
> - When a new system is to replace an old system, the data files kept on the old system needs to be transferred. Someone has to actually do this and this takes money, time and resources. In addition, any data transferred to the new system should be current. It would be of little use to transfer data from the old system to the new system one day but then not use the new system for a week. There would be one week's worth of data out-of-date!

> [!Tip] Parallel running 
> - The new system is run alongside the old system. Both systems operate together. This allows the new system to prove itself before the old system is abandoned - data generated by the new system can be compared to data generated by the old system. It also means that staff can be trained and gain confidence in the new system. Of course, if you are running two systems together, that means twice as much work for everyone for a short time!

> [!Tip] Pilot running 
> - According to the British Computing Society (BCS), pilot running is when the new system is run alongside the old system, but only a portion of the data is actually used in the new system. This method is less of a drain on resources. Data from part of the new system can be compared with the old system, but you cannot check how the whole system will react until you have got the whole system up and running. The term pilot running can also be applied when a system is to be installed in a chain of stores e.g. when a new store accounts system is to be installed in each of twenty stores in a chain. The whole system will be put intro one store and piloted. When it has proven itself, it will be rolled out to other stores, one at a time.

> [!Tip] Direct Changeover (Big Bang)
> - The old system is stopped and the new system is started. This might happen over a weekend, for example. If something goes wrong with the new system, then it has to be sorted out because you cannot fall back on the old system. Staff training needs to take place in advance with this method.

> [!Tip] Phased Implementation
> - Parts of a new system completely replace parts of an old system, whilst the old system continues to be used as required. The part of the new system that has been installed can be used for staff training and can prove itself before the next part of the installation takes place. This method takes longer than the direct changeover method. A company with 10 branches may install a new accounting system in one branch first, for example. They run it in the branch until it has proven itself and possibly bring in staff members from other branches for training. Once the system has proven itself in one branch, it can then be phased into the other branches.

## Testing 

> [!Info] White box/Glass box [[Testing]] 
> - White box (or glass box) testing is used by developers to write their tests.
> - It means that the developers can see the code and try to plan for all possible cases.
> - An example of this is having an if statement and then planning for all possible outcomes from the if statement.

> [!Info] Black box [[Testing]] 
> - Black box testing is running the system from the users' point of view.
> - This means that the tester will not be ablke to see any of the code behind the scenes.
> - This cannot be done by the programmers of the system as they know the code base.

> [!Info] How to [[Testing|test]]
> Whether you are doing black box testing or white box testing, a plan should use a range of data to produce a range of results. The programmer would:
> -   Decide what data to use.
> -   Decide why you will use that data.
> -   Predict the results.
> -   Carry out the test.
> - Compare the prediction with the actual results and comment on whether the test passed or failed.
>   
> When deciding what data to use, the programmer would consider the following categories of input data:
> - Valid data 
> - Invalid data.
> - Extreme data.
> - Mad data.
> - Borderline data - bugs lurk in corners!

> [!Info] Other types of testing 
> **Alpha testing**  
Software can be fully or partially written and then tested using black box and white box testing. Whether complete or only partially complete, the code is passed to a restricted audience within the company that produced the software, possibly a Testing Department set up for the purpose of testing software products. They will use it and give feedback to the programmers. They will report any faults they find, make comments about the ease of use of the software and suggest improvements, for example. This kind of testing is known as ‘alpha testing’. It is used to further improve a product and to help track down bugs.
>
>**Beta testing**  
Once a product has been alpha tested, it can then be improved and 'finished off'. It is released to a limited audience in return for their feedback. The audience might include reviewers, special customers and people who write textbooks about software products. This information can be used to further improve the quality of the final product before it is finally released and sold as a finished program to an awaiting public. This kind of testing is known as ‘beta testing’.
> **Acceptance Testing**
> Once the product has gone through alpha and beta testing, it goes through acceptance testing. This stage involves sertain senarios that meet the requirement specification. This stage of testing is done right at the very end of the project lifecycle, before the system is launched.

> [!Info] Extra Testing 
> **Unit testing**  
Whenever a module of code (or subroutine, or unit, or function, or procedure, or whatever other name you want to give to the block of self-contained code) is written, it needs to be tested. Testing can be done using black or white box testing, as discussed earlier. Whether you use black box or white box testing, testing an individual module of code is known as ‘unit testing’.
>**Integration testing**  
Once modules of code are tested using unit testing, they need to be combined and tested together. It is possible that two fully tested modules (tested individually using unit testing) will produce a problem when they are combined and asked to work together. Bringing modules together and checking that there are no unintentional problems is known as ‘integration testing’.

## Documentation

> [!Info] User documentation
With any product, some help needs to be provided for the users to enable them to run the software successfully. With many applications, those facilities are provided as software, as part of the application. To access the on-screen help, a user might click on a Help icon or press a function key, for example. A pop-up screen would then appear. A typical set of help features in an on-screen help system include:
> - An index to allow a user to scroll through help files.
> - A search engine to allow a user to type in key words or use natural language to search for solutions.
> - A FAQ (Frequently Asked Questions) facility so that users can find answers to common questions quickly.
> - Internet links to helpful web sites and support groups so that a user can find further help if they need to.
> - Tutorials, to show users how to carry out tasks. These are often animated and interactive.
> - Examples to help a user, such as a typical way to construct a formula.
> - Provision of a README file to tell the user important information before they get started using the product e.g. licence information.

> [!Info] Technical documentation for maintenance
The purpose of the technical documentation is to describe how the system actually functions. It is not written with a user in mind, but to assist a technical person in the future. The technical documentation is needed by a technical person because all software has a 'shelf-life'. Just because it is 'finished' at a particular point in time, it doesn't mean that it will never need to be re-visited again for ‘maintenance’, to upgrade the software, for example.
Apart from a contents page and index, the technical documentation would typically contain:
> - the Requirements Specification 
> - the hardware and software specification 
> - all of the documents from the design specification, including any program specifications and how to configure the systems 
> - details of all of the tests that were carried out and the results of the tests.
> - the code for any new software that was written. This should be fully documented so that someone can follow how the software works. 
> - the tables that detail what names have been used for variables, constants, subroutines and data structures in the code
> - a map of the whole software product so people can find their way around it easily. Imagine wondering where to start if you were given the task to modify in some way a program that was a million lines long!

## Evaluation

> [!Info] The basics of evaluation 
> - When a system has been completed, the customer needs to be sure that they have got what they paid for. 
> - The company who made the system needs to be sure that they have delivered what they promised. 
> - Checking this is known as the 'system evaluation'. The purpose of evaluating a system is to check that the product meets the requirements as laid down in the Requirements Specification.

> [!Info] What if it isn't what the clients paid for 
> - If some items are not completed, or completed but not to the required standard then negotiations may need to take place between the company and the maker of the product. 
> - They might agree a price reduction. 
> - They might agree an extension to fix the problems. 
> - They might agree that the company created the situation that has caused a problem and that they should pay more money than was originally agreed.

> [!Info] Ideas for Customer Feedback 
> -  Are there any bugs in the system?
   >  -   Are the users finding it easy to use?
   >  -   Do the users feel as though they got adequate training and retraining?
    > -   How are the Help facilities working?
  >   -   Has the product started to make an impact on the company - is it saving time and money?
  >   -   Have profits increased as a result of the product?

## Maintenance

> [!Info] Maintenance 
> - Maintenance is the term used to describe changing a system after it has been designed, installed and has been running for a time. 
> - Software products have a limited lifespan. There will come a time when they need to be revisited and code changed for a variety of reasons, some of which are given in the list below. 
> - One of the reasons why so much documentation is needed when designing a new system is that any future maintenance will undoubtedly be required. 
> - It is very likely, however, that the person maintaining a system will not be the same person who originally designed and built it.

> [!Tip] Perfective Maintenance 
> - This means maintenance to improve an existing system and trying to make a system perfect.
> - A complete re-write is not necessary, but some things are changed to improve the system. 
> - Examples might include redesigning user screens, improving the code to speed up actions, adding helpful tool tips and links to external sources of Internet help, removing any features that aren't used to simplify the overall user experience and so on.

> [!Tip] Adaptive Maintenance 
> - This type of maintenance means keeping a system up to date.
> - If changes in new technology needed to be introduced, this would be adaptive maintenance, for example, if employees had to log in by using biometrics rather than a login and password. 
> - If new laws on privacy meant that certain types of data couldn't be kept, the system would have to be changed to accommodate this.

> [!Tip] Corrective Maintenance 
> - This kind of maintenance is done to ensure errors and bugs are corrected. 
> - For example, if an employee reports that a function isn't working correctly, or in certain circumstances, something doesn't work properly then that would involve corrective maintenance. 
> - Most systems have a formal way for staff to report problems, which would identify areas for corrective maintenance. 
> - There will also be automatically generated error logs and these too can highlight areas where corrective maintenance needs to be carried out. 
> - If a problem was reported that caused a security issue, a 'patch' would be written and applied to the software.

