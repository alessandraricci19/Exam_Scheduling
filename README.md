# Exam_Scheduling_in_C++
**Exams Database Management System developed in C++ during the Algorithms and Computers class at the Polythecnic of Turin (2021).**

This project aims to manage a university database and exam scheduling. It involves creating a system with defined actors such as students, professors, courses, study programs, and classrooms. Each entity has specific attributes and methods. Interaction with the system occurs via input and output files and the database files themselves. Data must be entered in an orderly fashion, maintaining database integrity. The user interacts with the program via command line for operations like addition, updating, and insertion of data.

The second part focuses on exam management across three academic periods. Information is stored in files, and commands allow for insertion, updating of exam periods, professor unavailability, and exam date generation

The program is divided into two parts: database implementation and management, and exam definition. Specifically, to handle both parts, a *DbManager class* has been implemented, containing all the necessary methods to generate algorithms used for various requests. File management is also part of one of the methods in this class, which is called in the main function when appropriate. In the main file, there is a straightforward execution of the program where various operations on the data are invoked based on command-line options. These are selected using if-else loops. Additionally, for error management, a specific *Error class* has been created, containing possible errors that may occur during program execution.
