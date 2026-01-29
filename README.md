# Calculator-calculator.py
Copy code
Python
def add(a, b):
    return a + b

def sub(a, b):
    return a - b

def mul(a, b):
    return a * b

def div(a, b):
    if b == 0:
        return "Error: Division by zero"
    return a / b

while True:
    print("\nSimple Calculator")
    print("1. Add")
    print("2. Subtract")
    print("3. Multiply")
    print("4. Divide")
    print("5. Exit")

    choice = input("Choose option (1-5): ")

    if choice == "5":
        break

    a = float(input("Enter first number: "))
    b = float(input("Enter second number: "))

    if choice == "1":
        print("Result:", add(a, b))
    elif choice == "2":
        print("Result:", sub(a, b))
    elif choice == "3":
        print("Result:", mul(a, b))
    elif choice == "4":
        print("Result:", div(a, b))
    else:
        print("Invalid choice")
Optional file: README.md
Copy code
Markdown
# Simple Calculator (Python)

This is a basic command-line calculator written in Python.

## Functions
- Addition
- Subtraction
- Multiplication
- Division

## How to run

```bash
python calculator.py
