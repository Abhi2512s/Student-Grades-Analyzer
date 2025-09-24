Student Grades Analyzer 2.0 🎓📊

A Python mini-project to manage student records, calculate averages, find toppers, and search students interactively. Ideal for learning Python dictionaries, loops, functions, file handling, and building a portfolio project.

Features

Print All Students
Displays all students with their marks, average, and highlights the topper.

Find Topper
Calculates and displays the student with the highest average marks.

Class Average
Calculates the average marks of the class across all subjects.

Search Student by Name
Allows you to search a student by name and view their age, marks, and average.

Add New Student

Add a new student with custom subjects and marks.

Includes input validation for age and marks.

Automatically saves data to students.json.

Persistent Storage
All data is saved to students.json so it can be loaded when the program restarts.

Technologies Used

Python 3

Python Dictionaries & Lists

Functions & Loops

File Handling (json)

Input Validation

How to Use

Clone the repository or download the student_analyzer.py file.

Run the program using:

python student_analyzer.py


Use the interactive menu to:

Print all students

Find topper

Calculate class average

Search student by name

Add new students

Exit program

New student data is automatically saved in students.json.

Sample Output
===== Student Grades Analyzer 2.0 =====
1. Print All Students
2. Find Topper
3. Class Average
4. Search Student by Name
5. Add New Student
6. Exit
Enter your choice (1-6): 1

🎓 ---- All Students ----
Name: Riya, Age: 21, Marks: {'Math': 90, 'English': 88, 'Science': 95}, Average: 91.00 ⭐ Topper
Name: Amit, Age: 20, Marks: {'Math': 78, 'English': 65, 'Science': 89}, Average: 77.33
Name: Sneha, Age: 22, Marks: {'Math': 45, 'English': 56, 'Science': 67}, Average: 56.00

Future Improvements

Add graphical reports using matplotlib (e.g., bar chart of averages).

Allow edit/delete student functionality.

Add login system for multiple users.
