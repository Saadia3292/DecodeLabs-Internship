# Random Password Generator

**Python Programming Internship – Project 03**
**DecodeLabs**

Prepared by: **Saadia Shaheen**
Batch: **31 Jul – 31 August 2026**

---

## Description

This Python-based Random Password Generator creates secure passwords of a desired length using letters, numbers, and special characters, with randomized and shuffled characters for better security.

## Objective

To develop a Python program that generates strong and secure random passwords based on the user's selected length, while ensuring that each password contains at least one letter, one number, and one special character.

## Features

- Generates a random password of a user-specified length
- Guarantees the password contains:
  - At least one letter (uppercase or lowercase)
  - At least one number
  - At least one special character
- Shuffles the final character set so required characters aren't predictably placed
- Validates user input:
  - Rejects non-numeric input
  - Enforces a minimum password length of 4 characters

## Character Sets Used

| Type | Characters |
|---|---|
| Letters | `string.ascii_letters` (a–z, A–Z) |
| Numbers | `string.digits` (0–9) |
| Special Characters | `!@#$%^&*` |

## How It Works

1. The program prompts the user to enter a desired password length.
2. Input is validated in a loop:
   - Non-numeric entries raise a `ValueError`, which is caught and reported.
   - Lengths below 4 are rejected with an error message.
3. Once a valid length is provided, `generate_password()` is called:
   - One random letter, one random number, and one random special character are added first to guarantee complexity.
   - The remaining characters are filled in randomly from the combined character pool (letters + numbers + special characters).
   - The full list of characters is shuffled using `random.shuffle()`.
   - The list is joined into a single password string.
4. The generated password is displayed to the user.

## Requirements

- Python 3.x
- No external libraries required (uses only the built-in `random` and `string` modules)

## Usage

Open and run the notebook `Python_Programming_Internship_Project_03.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab, then run all cells.

You will be prompted to enter the desired password length:

```
Enter password length: 12
```

## Example Output

```
=======================================================
          RANDOM PASSWORD GENERATOR
          Python Programming - Project 3
=======================================================

Create a strong and secure random password.
Password must contain at least 4 characters.

Enter password length: 3
Error: Password length must be at least 4.

Enter password length: 12

-------------------------------------------------------
Generated Password:
tb9!SywaK1eR
-------------------------------------------------------

Password generated successfully!
Thank you for using the Random Password Generator.
```

## Concepts Applied

- Functions
- Loops (`while`, `for`)
- Randomization (`random.choice`, `random.shuffle`)
- Input validation
- Exception handling (`try` / `except`)

## Conclusion

This project successfully demonstrates a Python-based Random Password Generator that creates secure passwords using letters, numbers, and special characters. It strengthened my understanding of functions, loops, randomization, input validation, and exception handling.

## Author

**Saadia Shaheen**
Python Programming Internship – DecodeLabs (Batch: 31 Jul – 31 August 2026)
