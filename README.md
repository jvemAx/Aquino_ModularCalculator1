# Aquino_ModularCalculator1
# Function definitions for arithmetic operations
def add_numbers(a, b):
    return a + b

def subtract_numbers(a, b):
    return a - b

def multiply_numbers(a, b):
    return a * b

def divide_numbers(a, b):
    return a / b

# User input for the two integers
number1 = int(input("Choose your first number: "))
number2 = int(input("Choose your second number: ")) 

# Menu selection for operation
print("Choose an operation")
print("      1 - Addition")
print("      2 - Subtraction")
print("      3 - Multiplication")
print("      4 - Division")
operation = input("Enter choice: ")

# Execute selected operation and display result
if operation == "1":
    print("The sum is ", add_numbers(number1, number2))
if operation == "2":
    print("The difference is ", subtract_numbers(number1, number2))
if operation == "3":
    print("The product is ", multiply_numbers(number1, number2))
if operation == "4":
    print("The quotient is", divide_numbers(number1, number2))
