age = int(input("Enter your age: "))

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
def get_letter_grade(percentage):
    if 90 <= percentage <= 100:
        return "A"
    elif 80 <= percentage < 90:
        return "B"
    elif 70 <= percentage < 80:
        return "C"
    elif 60 <= percentage < 70:
        return "D"
    else:
        return "F"

# Example usage
grade = float(input("Enter your grade percentage: "))
print("Your letter grade is:", get_letter_grade(grade))
num1 = float(input("Enter first number: "))
num2 = float(input("Enter second number: "))
operation = input("Choose operation (+, -, *, /): ")

if operation == "+":
    print("Result:", num1 + num2)
elif operation == "-":
    print("Result:", num1 - num2)
elif operation == "*":
    print("Result:", num1 * num2)
elif operation == "/":
    if num2 != 0:
        print("Result:", num1 / num2)
    else:
        print("Error! Division by zero is not allowed.")
else:
    print("Invalid operation selected.")
import random
number = random.randint(1, 100)
print("Generated number:", number)

if number % 2 == 0:
    print("The number is even.")
else:
    print("The number is odd.")
