Bill Splitter Calculator
Description:

The Bill Splitter Calculator is a simple Python project that helps divide a bill amount equally among a group of people. Users enter the total bill amount and the number of people sharing the bill, and the program calculates how much each person needs to pay.
This project is perfect for beginners to practice working with user input, arithmetic operations, and formatted output in Python.

Features:
>Accepts the total bill amount from the user.
>Takes the number of people sharing the bill.
>Calculates the amount each person should pay.
>Simple and easy-to-understand Python code.
>Requirements
>Python 3.x
Code:
Python
>n = float(input("Enter total bill amount: "))
>p = int(input("Enter total persons: "))
> 
>per_person = n / p
> 
>print(f"Bill per person: {per_person}")
How to Run:
>Save the code as bill_splitter.py.
>Open a terminal or command prompt.
Run the program:
>Shell
>python bill_splitter.py
> 
>Enter the total bill amount:
>Enter the number of people sharing the bill.
>The program will display the amount each person should pay.
>Example Output
>Plain Text
>Enter total bill amount: 1000
>Enter total persons: 4
>Bill per person: 250.0
Learning Concepts:
>User Input (input())
>Type Conversion (float() and int())
>Arithmetic Operations
>Variables
>Formatted Output using f-strings
Future Improvements:
>Round the result to 2 decimal places.
>Validate inputs to prevent division by zero.
>Allow users to add tip percentages.
>Split bills with unequal shares.
