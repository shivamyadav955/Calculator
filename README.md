# Calculator.py
A simple calculator built by using python
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y == 0:
        return "Error: Division by zero!"
    return x / y

print("Simple Calculator")
print("1. Add")
print("2. Subtract")
print("3. Multiply")
print("4. Divide")

choice = input("Enter your choice (1-4): ")

if choice == "1":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("Result:", add(num1, num2))
elif choice == "2":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("Result:", subtract(num1, num2))
elif choice == "3":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("Result:", multiply(num1, num2))
elif choice == "4":
    num1 = float(input("Enter first number: "))
    num2 = float(input("Enter second number: "))
    print("Result:", divide(num1, num2))
else:
    print("Invalid choice!")
