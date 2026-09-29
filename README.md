# basic-calculatorSimple CLI Calculator
A lightweight Python command-line utility to perform basic arithmetic operations and percentage calculations on two user-supplied numbers.

Features

Addition: Calculates the sum of two values.

Subtraction: Calculates the difference between the first and second value.

Multiplication: Calculates the product of two values.

Division: Computes the quotient of the two numbers.

Percentage: Determines what percentage the first number is of the second number ((a / b) * 100).

Precision Formatting: Rounds all output results to 2 decimal places.

How It Works

The script operates through three sequential stages:

Function Definitions: Implements modular helper functions for each supported operation:

addition(a, b)

subtraction(a, b)

multiplication(a, b)

division(a, b)

percentage(a, b)

User Input Collection:

Prompts for two floating-point numbers (a and b).

Strips extraneous whitespace via .strip() to prevent input formatting errors.

Prompts for the intended operation name (operation).

Execution & Evaluation:

Matches the input string against conditional checks (if/elif).

Executes the corresponding function, wraps the result in round(..., 2), and prints it to the console.

Requirements
Python 3.6 or later (standard library only; no external dependencies required).

Usage
Save the script to a file named calculator.py.

Run the script via your terminal:
