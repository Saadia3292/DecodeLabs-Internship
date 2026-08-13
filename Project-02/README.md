💰 Expense Tracker
DecodeLabs – Python Programming Internship | Project 02

A simple command-line Expense Tracker built with Python that allows users to enter multiple expense amounts, validates the entered amounts, calculates the running total, and displays a final expense summary.

📌 Project Overview

The Expense Tracker is a Python-based console application developed as part of the DecodeLabs Python Programming Internship.

The application allows users to:

Enter multiple expense amounts
Validate expense input
Prevent negative expense values
Handle invalid/non-numeric input
Maintain a running total of expenses
Count the number of expenses entered
Display a final expense summary

The project demonstrates fundamental Python programming concepts including functions, loops, input validation, exception handling, conditional statements, and accumulator logic.

🎯 Objective

The main objective of this project is to develop a Python program that:

Accepts multiple expense amounts from the user.
Validates the entered values.
Accumulates all valid expenses.
Counts the number of expenses.
Displays the total amount spent at the end of the program.
✨ Features
1. Expense Input

Users can enter an expense amount through the command line.

2. Input Validation

The application checks whether the entered value is a valid number.

If the user enters invalid data, the program displays:

Invalid input. Please enter a valid number.
3. Negative Expense Prevention

Negative expense values are not accepted.

Error: Expense cannot be negative.
4. Multiple Expenses

Users can continue adding expenses until they choose no.

5. Expense Counting

The application keeps track of the total number of expenses entered.

6. Running Total

Every valid expense is added to the accumulated total.

7. Final Expense Summary

At the end, the program displays:

Number of expenses
Total amount spent
🛠️ Technologies Used
Python 3
Google Colab / Jupyter Notebook
Python built-in functions and control structures
🧠 Python Concepts Demonstrated

This project demonstrates practical use of:

Functions
while loops
if / elif / else statements
User input with input()
Type conversion using float()
Exception handling with try-except
ValueError handling
String methods such as .strip() and .lower()
Incrementing counters
Accumulator logic
Formatted output using f-strings
The if __name__ == "__main__": pattern
📂 Project Structure
Expense-Tracker/
│
├── Expense_Tracker.ipynb
└── README.md

If your notebook has a different filename in your GitHub repository, replace Expense_Tracker.ipynb with the actual filename.

⚙️ How the Program Works
Start
  ↓
Display Expense Tracker Header
  ↓
Enter Expense Amount
  ↓
Validate Input
  ↓
Is the amount valid?
  ├── No → Display Error → Enter Again
  └── Yes
        ↓
    Add Expense to Total
        ↓
    Increase Expense Count
        ↓
    Ask: Add Another Expense?
        ↓
      Yes → Enter Another Expense
        ↓
      No
        ↓
Display Expense Summary
        ↓
End
🔧 Main Functions
display_header()

Displays the application heading.

get_expense()

Gets an expense amount from the user and validates the input. It rejects negative values and handles invalid numeric input using exception handling.

run_expense_tracker()

Controls the main expense-tracking process. It maintains:

total
expense_count

Each valid expense is added to the running total and counted.

main()

Runs the application, displays the header, starts the expense tracker, and presents the final expense summary.

▶️ Sample Execution
==================================================
                 EXPENSE TRACKER
==================================================
Enter expense amount: 100
Expense added: 100.00

Do you want to add another expense? (yes/no): yes

Enter expense amount: 50
Expense added: 50.00

Do you want to add another expense? (yes/no): yes

Enter expense amount: 20
Expense added: 20.00

Do you want to add another expense? (yes/no): no

==================================================
                 EXPENSE SUMMARY
==================================================
Number of Expenses : 3
Total Spent        : 170.00
==================================================
📊 Example Calculation
Expense 1 = 100
Expense 2 = 50
Expense 3 = 20

Total = 100 + 50 + 20
      = 170

Number of Expenses: 3
Total Spent: 170.00

🚀 How to Run
1. Clone the repository
git clone <your-repository-url>
2. Open the project

Open the notebook:

Expense_Tracker.ipynb
3. Run the cells

Execute the Python cells in Google Colab or Jupyter Notebook.

4. Enter expenses

Follow the prompts and enter your expense amounts.

5. View the summary

Choose no when you finish entering expenses to display the final expense summary.

📚 Learning Outcomes

Through this project, I strengthened my practical understanding of:

Python functions
Loops and repetition
User input handling
Input validation
Exception handling
Conditional logic
Accumulator-based calculations
Counters
Clean console output
Structuring a small Python application
🔮 Future Improvements

Possible future enhancements include:

Adding expense categories
Storing individual expenses in a list
Showing a detailed expense history
Adding dates for expenses
Saving expenses to a CSV file
Generating monthly expense reports
Adding a graphical user interface
Adding charts for expense analysis
👩‍💻 Author

Saadia Shaheen

DecodeLabs Python Programming Internship

Project: Expense Tracker
Batch: 31 July – 31 August 2026

⭐ Project Status

Completed ✅

This project demonstrates a functional Python-based Expense Tracker with expense validation, multiple expense entry, running total calculation, expense counting, and final summary generation.

🏷️ Tags

Python Python Programming Expense Tracker DecodeLabs Internship Beginner Python Input Validation Exception Handling Functions Loops
