Multi-Utility Toolkit

A console-based, interactive Python application providing a collection of utilities for date-time management, mathematical calculations, random data generation, unique identifier (UUID) generation, file I/O operations, and dynamic module inspection.

📋 Features & Functionalities

1. Datetime and Time Operations

Current Date & Time: Displays the current timestamp in YYYY-MM-DD HH:MM:SS format.

Date Difference: Calculates the absolute difference in days between two ISO-formatted dates (YYYY-MM-DD).

Format Date: Formats the current date and time using custom user-supplied directives (e.g., %d-%m-%Y).

Stopwatch: Measures elapsed time between two user keypresses.

Countdown Timer: Provides a second-by-second countdown with input validation.

2. Mathematical Operations

Factorial: Computes the factorial of non-negative integers.

Compound Interest: Calculates total amount and total compound interest given principal, interest rate, and duration.

Trigonometry: Calculates Sine, Cosine, and Tangent values for angles entered in degrees.

Area of Shapes: Computes areas for Circles, Rectangles, and Triangles.

Logarithms: Computes Natural Logarithm ($\ln$) and Base-10 Logarithm ($\log_{10}$) for positive numbers.

3. Random Data Generation

Random Number: Generates a random integer within a specified range [min, max].

Random List: Generates a list of random integers based on count and range constraints.

Password Generator: Creates random passwords composed of letters, digits, and special characters (!@#$%&*).

OTP Generator: Generates numeric One-Time Passwords of custom lengths.

Random Sampling: Selects a specified number of items randomly from a comma-separated list.

Number Guessing Game: Mini-game where the user guesses a secret random integer between 1 and 10.

4. UUID Generation

Generates standard UUID4 unique identifiers using Python's built-in uuid module.

5. File Operations

Create File: Creates a new file safely (raises an error if the file already exists).

Write to File: Overwrites or writes new content to a file using standard UTF-8 encoding.

Read File: Reads and displays the full content of an existing text file.

Append to File: Appends new lines of content to an existing file.

6. Explore Module Attributes

Inspects available methods, classes, and attributes of imported standard modules (datetime, time, math, random, string, uuid) dynamically via dir().

🛠️ Requirements & Dependencies

This toolkit relies exclusively on standard Python 3 built-in libraries. No external package installation (pip) is required.

Python Version: Python 3.8 or higher.

Standard Modules Used:

datetime

time

math

random

string

uuid

🚀 How to Run

Clone or Download: Save the Python code to a file, for example main.py.

Open Terminal / Command Prompt: Navigate to the folder containing main.py.

Execute the Script:

python main.py


💻 Sample Interactive Menu

Module and Packager - Multi-Utility Toolkit
1. Datetime and Time Operations
2. Mathematical Operations
3. Random Data Generation
4. UUID Generation
5. File Operations
6. Explore Module Attributes
7. Exit
Enter your choice:


🛡️ Error Handling & Guardrails

Input Validation: Prevents crashes caused by non-numeric inputs using try-except ValueError blocks across math and date menus.

Range & Boundary Checks: Validates negative values for lengths, dimensions, interest rates, and countdown durations.

File Exception Handling: Catches FileExistsError, FileNotFoundError, and standard OSError exceptions during file manipulation.

Execution Guard: Utilizes the if __name__ == "__main__": block to ensure top-level program execution and modularity.
