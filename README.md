# python-calculator-
my small first project 
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

def multiply(x, y):
    return x * y

def divide(x, y):
    if y != 0:
        return x / y
    else:
        return "Error! Division by zero."

print("Simple Calculator")
print("Operations: +, -, *, /")

num1 = float(input("Enter first number: "))
op = input("Enter operator (+, -, *, /): ")
num2 = float(input("Enter second number: "))

if op == '+':
    print("Result:", add(num1, num2))
elif op == '-':
    print("Result:", subtract(num1, num2))
elif op == '*':
    print("Result:", multiply(num1, num2))
elif op == '/':
    print("Result:", divide(num1, num2))
else:
    print("Invalid operator")
