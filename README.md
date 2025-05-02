This project was created as part of a University of Washington course focused on object-oriented programming concepts using C#.

Project Overview
The application is a simple console-based student database system written in C#. It demonstrates the use of:

Object-oriented principles: inheritance, encapsulation, and polymorphism

A class hierarchy (Student, Undergrad, and GradStudent)

CRUD operations (Create, Read, Update, Delete)

Data persistence using plain .txt files

Collection manipulation using List<Student>

Learning Disclaimer
This code was written while I was learning C# in a classroom setting. While I passed the course and implemented all required functionality, I do not currently consider myself proficient in C#. This project represents exposure and early experience with the language — not expertise.

I'm continuing to improve my software development skills and exploring more hands-on practice in different languages and tools.

Testing Summary
The program was tested using a set of 4 student objects with varying data, including both Undergrad and GradStudent types. Testing verified that:

All CRUD operations performed correctly on the in-memory collection

Changes were reflected persistently in the output .txt file

One record remained unchanged throughout the full program run to validate safe storage

What I Learned
How to model real-world data using inheritance

How to work with file input/output in C#

How to manage data in a generic list and simulate database-like behavior

The importance of structured testing and version control

Technologies Used
C#

.NET CLI (in Visual Studio Code)

PowerShell (for transcript logging)

* How to Run
Clone the repo

Open in Visual Studio Code

Compile and run via terminal:
dotnet build
dotnet run
