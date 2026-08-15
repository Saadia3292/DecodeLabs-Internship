Python Programming Internship Project 01
DecodeLabs Internship — To-Do List Application

Prepared by: Saadia Shaheen Batch: 31 Jul – 31 Aug 2026

Description

This project is a menu-driven To-Do List Application developed in Python. It allows users to add tasks, view tasks, and exit the program, while demonstrating the use of variables, lists, loops, conditional statements, user input, and exception handling.

Features
Add a task to the to-do list
View all added tasks (numbered list)
Handles empty task input (won't add a blank task)
Handles invalid menu input using exception handling
Exit the application through the menu
Concepts Used
Variables
Lists
append()
User Input (input())
while Loop
for Loop
if-elif-else
Exception Handling (try/except)
List Traversal
Project Structure
DecodeLabs_Internship_Python_Project_01.ipynb

The notebook contains:

A markdown cell with the project title, author, batch, and description
A markdown/comment cell listing the core concepts used
The main code cell containing the To-Do List Application logic
A closing markdown cell with the Project Summary, Concepts Used, and Learning Outcome
How the Program Works
The program starts by printing a welcome banner.
It displays a menu with three options:
1. Add Task
2. View Tasks
3. Exit
The user enters a choice (1–3):
Choice 1: Prompts the user for a task. If the task is empty, it shows an error and asks again; otherwise, the task is added to the list.
Choice 2: Displays all tasks currently in the list, numbered in order. If no tasks exist, it shows "No tasks available."
Choice 3: Prints a thank-you message and exits the program (break).
Any other number prints an invalid-choice message.
If the user enters something that is not a number, a ValueError is caught and an "Invalid input" message is shown, and the menu loops again.
This loop (while True) continues until the user selects option 3 to exit.
Sample Output
=============================================
        WELCOME TO TO-DO LIST
=============================================

Choose an Option
1. Add Task
2. View Tasks
3. Exit
Enter your choice (1-3): 1
Enter your task: 2
Task added successfully.

Choose an Option
1. Add Task
2. View Tasks
3. Exit
Enter your choice (1-3): 3

Thank you for using the To-Do List Application.
Project Completed Successfully.
Project Summary

This project demonstrates the implementation of a menu-driven To-Do List Application using Python.

Learning Outcome

Through this project, I learned how to manage data using Python lists, create interactive console applications, validate user input, and implement logical program flow using loops and conditional statements.

How to Run
Open DecodeLabs_Internship_Python_Project_01.ipynb in Google Colab or Jupyter Notebook.
Run the main code cell.
Follow the on-screen menu prompts to add tasks, view tasks, or exit.
Author: Saadia Shaheen Internship: DecodeLabs Internship (Batch: 31 Jul – 31 Aug 2026) Project: 01 — To-Do List Application

Author: Saadia Shaheen Internship: DecodeLabs Internship (Batch: 31 Jul – 31 Aug 2026) Project: 01 — To-Do List Application
