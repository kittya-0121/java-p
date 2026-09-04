# Student Management System

A simple **Student Management System built using Java**. This project is a console-based application that allows users to add, view, search, and delete student records.

## Features

* Add a new student
* View all students
* Search for a student by ID
* Delete a student by ID
* Prevent duplicate student IDs
* Simple menu-driven interface
* No external libraries required

## Technologies Used

* **Java**
* **ArrayList**
* **Scanner**
* Object-Oriented Programming (OOP)

## Project Structure

```text
StudentManagementSystem/
│
└── StudentManagementSystem.java
```

## Requirements

Before running the project, make sure you have:

* Java JDK 8 or higher
* Command Prompt / Terminal
* Any Java IDE (optional)

## How to Run

### 1. Clone or download the project

Download the project files to your computer.

### 2. Open the project folder

Open Command Prompt or Terminal inside the project folder.

### 3. Compile the program

```bash
javac StudentManagementSystem.java
```

### 4. Run the program

```bash
java StudentManagementSystem
```

## How to Use

After starting the application, you will see the following menu:

```text
=================================
     STUDENT MANAGEMENT SYSTEM
=================================
1. Add Student
2. View Students
3. Search Student
4. Delete Student
5. Exit
=================================
Enter your choice:
```

### Add Student

Select option `1` and enter:

* Student ID
* Student Name
* Age
* Course

Example:

```text
Enter Student ID: 101
Enter Student Name: Rahul
Enter Age: 20
Enter Course: Computer Science

Student added successfully!
```

### View Students

Select option `2` to display all registered students.

### Search Student

Select option `3` and enter the Student ID.

### Delete Student

Select option `4` and enter the Student ID that you want to delete.

### Exit

Select option `5` to close the application.

## Example

```text
=================================
     STUDENT MANAGEMENT SYSTEM
=================================
1. Add Student
2. View Students
3. Search Student
4. Delete Student
5. Exit
=================================
Enter your choice: 1

Enter Student ID: 101
Enter Student Name: Rahul
Enter Age: 20
Enter Course: Java

Student added successfully!

Enter your choice: 2

===== ALL STUDENTS =====
--------------------------------
Student ID : 101
Name       : Rahul
Age        : 20
Course     : Java
```

## Concepts Demonstrated

This project demonstrates several basic Java concepts:

* Classes and Objects
* Constructors
* Methods
* ArrayList
* Loops
* Conditional Statements
* Switch Statements
* User Input
* Encapsulation basics
* Object-Oriented Programming

## Limitations

* Student data is stored only in memory.
* Data will be lost when the application is closed.
* It does not currently use a database.
* It is a console-based application.

## Future Improvements

The project can be extended by adding:

* MySQL database connectivity
* Java Swing or JavaFX GUI
* Update student details
* Login and authentication
* Student marks and grades
* Attendance management
* Export student data to CSV/PDF

## Author

**Student Management System - Java Project**

## License

This project is created for **educational and learning purposes**.
