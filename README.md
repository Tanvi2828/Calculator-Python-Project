# Calculator-Python-Project
Project Description
This project is a command-line calculator application with the following features:

Basic arithmetic operations: Addition, Subtraction, Multiplication, Division, and Exponentiation.
Operation logging: Logs all operations performed with timestamps to a file (calculator_history.log).
History management: Saves the operation history to a text file (calculator_history.txt) and allows users to load and view it.
Features
Arithmetic Operations:

Addition
Subtraction
Multiplication
Division (handles division by zero gracefully)
Power (exponentiation)
Logging:

Logs each operation and its result to calculator_history.log.
History:

Keeps a list of operations during the session.
Saves history to calculator_history.txt.
Allows loading and viewing saved history.
Error Handling:

Handles invalid inputs and division by zero.
Requirements
Python 3.x
No external libraries are needed.
Installation
Clone or download the repository.
Ensure Python 3.x is installed on your system.
How to Use
Run the script in your terminal:

bash
Copy code
python calculator.py
Follow the prompts:

Select an operation by entering a number (1-7).
For operations (1-5), enter two numbers when prompted.
For viewing history, choose option 6.
To save the history to a file, choose option 7.
Example flow:

mathematica
Copy code
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
Additional Notes
Viewing History:

Option 6 allows you to view previously saved history from calculator_history.txt.
If the file doesn't exist, you'll see "No history found."
Saving History:

Option 7 saves the current session history to calculator_history.txt.
Example Output
Performing an Addition
mathematica
Copy code
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
Viewing History
mathematica
Copy code
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
Future Improvements
Add support for additional mathematical functions (e.g., square root, logarithms).
Implement a graphical user interface (GUI).
Add user authentication for saving history.
Enjoy using the Enhanced Calculator! 🎉
