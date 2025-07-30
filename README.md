# My_Calculator
# 🐍 Intro to Python Assignment – Basic Calculator

## 📌 Overview
This project is part of the **Intro to Python Assignment**. The goal is to practice Python fundamentals by building a simple **basic calculator program** that uses user input, arithmetic operations, and conditional statements.

---

## 🎯 Objective
- Practice creating Python programs to perform arithmetic and string operations.  
- Experiment with variables and data types.  
- Use `if/elif/else` statements for decision-making.  

---

## 📝 Instructions
The program should:  
1. Ask the user to input **two numbers**.  
2. Ask the user to input a mathematical operation: `+`, `-`, `*`, or `/`.  
3. Perform the calculation based on the input.  
4. Display the result in a clear format.  
## 💻 Code Example
```python
# Basic Calculator Program

num1 = float(input("Enter the first number: "))
num2 = float(input("Enter the second number: "))
operation = input("Enter the operation (+, -, *, /): ")

if operation == "+":
    print(f"{num1} + {num2} = {num1 + num2}")
elif operation == "-":
    print(f"{num1} - {num2} = {num1 - num2}")
elif operation == "*":
    print(f"{num1} * {num2} = {num1 * num2}")
elif operation == "/":
    if num2 != 0:
        print(f"{num1} / {num2} = {num1 / num2}")
    else:
        print("Error: Division by zero is not allowed!")
else:
    print("Invalid operation. Please choose +, -, * or /")
