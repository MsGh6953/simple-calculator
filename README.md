# Simple Calculator 🧮  

This repository has a basic calculator that performs addition, subtraction, multiplication, and division.  

## Code in This Repo  
```python
num1 = float(input("Enter your first number below: "))  
operator = input("Enter an operator (+, -, *, /): ")  
num2 = float(input("Enter second number: "))  

if operator == "+":  
    print(f"Result: {num1 + num2}")  
elif operator == "-":  
    print(f"Result: {num1 - num2}")  
elif operator == "*":  
    print(f"Result: {num1 * num2}")  
elif operator == "/":  
    if num2 != 0:  
        print(f"Result: {num1 / num2}")  
    else:  
        print("Error! Division by zero isn't allowed.")  
else:  
    print("Invalid operator!")
