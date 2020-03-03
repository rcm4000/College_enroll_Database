# College_enroll_Database
class projects

Object and Purpose
The main purpose for this project is to get familiar with structured storage, application, modification, and lastly maintenance of data. In this project, students will use DBMS, which is a system that aims to allow the definition, creation, querying, update, and administration of databases. Moreover, another purpose of this project is to understand the data modeling concepts that is applied in a real time scenario and to implement a fully functional database system that interacts with an end user interface.

Problem Definition
In this term project, we are asked to design a small database system, The Course Registration system for New Jersey Institute of Technology needs to be created with a back-end database and a front-end web interface. The selection of a database system for the back-end is optional. Also, the web server used can be chosen optionally from the various application. In addition, we need to write a number of application programs to access the database. The topic of the project is to design the database system that the New Jersey Tech., a university of excellence can use to manage students and courses.

Summary of The System Requirements
New Jersey Institute Technology is starting to move some of its applications into a database environment. We have been hired to set-up the database system to assist New Jersey Tech. achieve its goals. A requirements analysis that was conducted has identified a number of things about the operations and goals of New Jersey Tech.. We, as the systems analyst/designer, should feel free to add to these requirements in order to achieve a richer design. New Jersey Tech. keeps records about a number of items. These are the following: 
1. First and foremost, it keeps track of its students who are uniquely identified by their Student Ids (different from the SSN). For each student, his/her SSN, address, high school, major (identified by a particular department) and year are other essential information. 
2. Information about staff is also maintained. The name and SSN (which uniquely identify each staff) are essential information for each staff. The address, salary are other required information. 3. A particular type of staff is the faculty. In addition to the general staff information, the rank and course load (in terms of maximum number of courses that the particular faculty can teach) information are stored for each faculty. 
4. A faculty may be assigned to multiple departments (joint appointments). This enables them to teach courses at multiple departments as long as the total number of courses is not higher than the course load. 
5. Information about each department is maintained. Each department is identified by a unique codes. The department name, the location of the main office, latest annual budget 1 are the information that are stored. Each department has a chairperson who is a faculty member. 
6. Physical room facilities of the university are identified. The identification is by means of a building code and room number. Other information include the audio-visual equipment and the capacity of the room. 
7. Departments offer a number of courses. Course information includes the course code, course name, course credit (using the nomenclature that is followed at NJIT). No two courses in the university can have the same code. For each course, the teaching assistant requirements (in terms of number of hours per week) are also stored. 
8. Sections of courses are identified by a number. Note that there cannot exist a section unless it is related to an existing course. For the sections, New Jersey Tech. keeps information about the room, the weekdays (1 or 2) and the time the lectures are held and the maximum enrollment. 
9. Each section is taught by one faculty member. Faculty members can teach multiple sections of a course or sections of different courses. 
10. Students register for a number of course sections but to only one section of the same course. 11. For each course a number of teaching assistants (TA) can be assigned. Teaching assistants are students who have been hired as staff. Full-time TAs are allowed to work a maximum of 20 hours a week while half-time TAs can work 12 hours a week.

Database Server & Web Interface Application
This project was developed using ASP.net and C# and Microsoft SQL Server.   We use Visual Studio to write and test the code. We chose to use Visual Studio because it had a built in web Server which runs locally on our machine and it made testing our web application easier.  Using the Local IIS is the closest to what a live site would run under.  It also has a one click deploy to Azure, which makes transferring our application into a life environment fast and easy.   In addition, since Visual studio comes built in with Microsoft SQL Server it made it easy for us to install the program and start code immediately. We didn’t  need to set up any server connections or install any other tools separately it was just one program.  It this made testing easy because we both were in different locations and the application was saved on the cloud.

Design Software:

Microsoft Visual Studio Community 2017  Version 15.2 (26430.16) Release
Microsoft .NET Framework
Version 4.7.02046
Azure portal 

Installed Version: Community

Visual C# 2017  
Microsoft Visual C# 2017
Microsoft SQL Server
Version 13.00.1601
 
Data Source=(LocalDB)\MSSQLLocalDB;AttachDbFilename=" v5-rm_FY_st\v5-rm_FY_st\App_Data\stbase1.mdf";Integrated Security=True;MultipleActiveResultSets=True


 










