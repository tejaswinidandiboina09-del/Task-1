Command-Line Calculator
1. Project Title
Simple Command-Line Calculator using Python
2. Objective
To create a simple command-line calculator that performs basic arithmetic operations such as addition, subtraction, multiplication, and division.
3. Tools Required
Python
VS Code / Any Text Editor
Terminal
4. File Name
calculator.py
5. Program
# calculator.py

print("===== Simple Calculator =====")

num1 = float(input("Enter first number: "))
operator = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if operator == "+":
    result = num1 + num2
elif operator == "-":
    result = num1 - num2
elif operator == "*":
    result = num1 * num2
elif operator == "/":
    if num2 == 0:
        print("Error: Cannot divide by zero.")
        exit()
    result = num1 / num2
else:
    print("Invalid operator.")
    exit()

print("Result:", result)
6. How to Run
Open the terminal in VS Code and type:
python calculator.py
7. Output
Addition:
===== Simple Calculator =====
Enter first number: 10
Enter operator (+, -, *, /): +
Enter second number: 5
Result: 15.0
Subtraction:
===== Simple Calculator =====
Enter first number: 20
Enter operator (+, -, *, /): -
Enter second number: 8
Result: 12.0
Multiplication:
===== Simple Calculator =====
Enter first number: 6
Enter operator (+, -, *, /): *
Enter second number: 5
Result: 30.0
Division:
===== Simple Calculator =====
Enter first number: 20
Enter operator (+, -, *, /): /
Enter second number: 4
Result: 5.0
8. Result
The command-line calculator was successfully created using Python. It performs basic arithmetic operations and also handles division by zero and invalid operators.
