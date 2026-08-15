# Python Programming Internship — Project 02

## DECODELABS

**Project:** Expense Tracker
**Prepared by:** Saadia Shaheen
**Batch:** 31 Jul – 31 August 2026
**File:** `Decodelabs_Internship_Python_Project_02.ipynb`

---

## Description

This project is a Python-based **Expense Tracker** that allows users to enter multiple expense amounts, calculates the running total, validates user input, and displays a final expense summary.

## Objective

To develop a Python program that accepts multiple expense amounts, accumulates the values, and displays the total amount spent.

---

## Features

- Accepts multiple expense entries in a single session
- Validates that expense amounts are numeric (handles invalid input gracefully)
- Rejects negative expense values
- Keeps a running total and a running count of expenses
- Prompts the user after each entry to add another expense or stop
- Validates the yes/no continuation prompt (re-asks on invalid input)
- Displays a final formatted summary showing the number of expenses and total amount spent

---

## Program Structure

The program is organized into four functions:

| Function | Purpose |
|---|---|
| `display_header()` | Displays the application heading |
| `get_expense()` | Prompts for and validates a single expense amount (rejects negative values and non-numeric input) |
| `run_expense_tracker()` | Runs the main loop: collects expenses, accumulates the total and count, and asks whether to continue |
| `main()` | Orchestrates the program — displays the header, runs the tracker, and prints the final summary |

The program runs via the standard `if __name__ == "__main__":` entry point, which calls `main()`.

---

## How It Works

1. The program displays the **EXPENSE TRACKER** header.
2. The user is repeatedly prompted to enter an expense amount.
   - Non-numeric input triggers an "Invalid input" message and re-prompts.
   - Negative values trigger an "Expense cannot be negative" message and re-prompts.
3. Each valid expense is added to the running total, and the expense count is incremented.
4. After each entry, the user is asked: *"Do you want to add another expense? (yes/no)"*
   - `yes` → loop continues to collect another expense
   - `no` → loop ends and the program moves to the summary
   - Any other input → the user is re-asked
5. Once the user chooses to stop, the program displays the **EXPENSE SUMMARY**, showing:
   - Number of Expenses
   - Total Spent (formatted to 2 decimal places)

---

## Sample Output

```
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
```

---

## Concepts Applied

- Loops (`while True`)
- Functions
- Input validation
- Exception handling (`try` / `except ValueError`)
- Accumulator pattern (running total and count)
- Basic data processing and formatted output

---

## How to Run

1. Open `Decodelabs_Internship_Python_Project_02.ipynb` in Jupyter Notebook, Google Colab, or any compatible environment.
2. Run all cells in order.
3. Follow the on-screen prompts to enter expense amounts and respond to the continuation prompt.
4. View the final expense summary once you choose to stop.

---

## Conclusion

This project successfully demonstrates a Python-based Expense Tracker that accepts and validates multiple expenses, calculates the total using accumulator logic, and displays the final amount spent. It strengthened understanding of loops, functions, input validation, exception handling, and basic data processing.

---
Author: Saadia Shaheen Internship: DecodeLabs Python Programming Internship Batch: 31 Jul – 31 August 2026
**Author:** Saadia Shaheen
**Internship:** DecodeLabs Python Programming Internship
**Batch:** 31 Jul – 31 August 2026
