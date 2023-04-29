## Grade Tracker
The Grade Tracker is a program written in C designed to help teachers keep track of grades for their classes. With this application, teachers can easily enter, view, and update student grades for multiple classes.

## Features
Add new students with their name and ID number
Enter grades for two exams and a final project for each student
Calculate the final grade for each student using the following formula:

Final grade = (Exam 1 grade * 0.2) + (Exam 2 grade * 0.3) + (Final project grade * 0.5)
View a summary of all student grades for a particular class
Update grades for existing students
Remove students from a class
Getting Started

## Prerequisites
A C compiler installed

## Installation
Clone the repository
git clone https://github.com/username/grade-tracker.git
## Navigate to the project directory
cd grade-tracker

## Compile the program
gcc grade_tracker.c -o grade_tracker

## Usage
Run the program
./grade_tracker
Select a class from the menu or create a new class

Welcome to Grade Tracker!
1. Select a class
2. Create a new class
3. Quit
Enter your choice: 1
Add students to the class

Class: Math 101
1. Add a new student
2. View student grades
3. Update student grades
4. Remove a student
5. Back
Enter your choice: 1
Enter student name: John Doe
Enter student ID: 12345
Enter grades for each student

Class: Math 101
1. Add a new student
2. View student grades
3. Update student grades
4. Remove a student
5. Back
Enter your choice: 2
Enter student ID: 12345

Student: John Doe (ID: 12345)
Exam 1: 80
Exam 2: 90
Final project: 85
Final grade: 86.5
View a summary of all student grades for a particular class
markdown
Copy code
Class: Math 101
1. Add a new student
2. View student grades
3. Update student grades
4. Remove a student
5. Back
Enter your choice: 2

Student grades for Math 101:
John Doe (ID: 12345) - Final grade: 86.5
Contributing
We welcome contributions from the community. To contribute to the project, please follow these steps:

Fork the repository
Create a new branch for your feature or bug fix
Write tests and code for your feature or bug fix
Ensure that tests pass and the code is well-documented
Create a pull request
License
This project is licensed under the MIT License - see the LICENSE.md file for details.
