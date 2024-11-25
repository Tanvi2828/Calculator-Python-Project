# Calculator-Python-Project
# Project Description : 
This project is a command-line calculator application with the following features:


# Features: 

1.Arithmetic Operations:
Addition
Subtraction
Multiplication
Division (handles division by zero gracefully)
Power (exponentiation)

2.Logging:
Logs each operation and its result to calculator_history.log.

3.History:
Keeps a list of operations during the session.
Saves history to calculator_history.txt.
Allows loading and viewing saved history.

Error Handling:
Handles invalid inputs and division by zero.

# Requirements:
Python 3.x
No external libraries are needed.

# Installation:
Clone or download the repository.
Ensure Python 3.x is installed on your system.

# How to Use:
Run the script in your terminal:

bash
python calculator.py

Follow the prompts:
Select an operation by entering a number (1-7).
For operations (1-5), enter two numbers when prompted.
For viewing history, choose option 6.
To save the history to a file, choose option 7.

# Example flow:
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Power
6. Show History
7. Save History to File
Enter choice (1-7): 1
Enter first number: 10
Enter second number: 5
The result is: 15.0
Files
calculator.py: Main script containing the calculator logic.
calculator_history.log: Automatically created file for logging all operations with timestamps.
calculator_history.txt: Optional file where session history is saved for future reference.

# Additional Notes:
1.Viewing History:
Option 6 allows you to view previously saved history from calculator_history.txt.
If the file doesn't exist, you'll see "No history found."

2.Saving History:
Option 7 saves the current session history to calculator_history.txt.

# Example Output:
Performing an Addition

Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Power
6. Show History
7. Save History to File
Enter choice (1-7): 1
Enter first number: 10
Enter second number: 5
The result is: 15.0

Viewing History :
Select operation:
1. Add
2. Subtract
3. Multiply
4. Divide
5. Power
6. Show History
7. Save History to File
Enter choice (1-7): 6
2024-11-18 14:00:00 - 10 + 5 = 15.0
   
# Future Improvements:
Add support for additional mathematical functions (e.g., square root, logarithms).
Implement a graphical user interface (GUI).
Add user authentication for saving history.


Enjoy using the Enhanced Calculator! 🎉
