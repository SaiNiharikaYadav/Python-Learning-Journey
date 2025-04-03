Day 2 - Python Learning Concepts
Topics Covered
Variables in Python
User Input in Python
Type Conversion (Casting)
Basic Arithmetic Operations
Operators in Python

1️⃣ Variables in Python
Variables are used to store data in memory. Python variables do not require explicit type declaration.

Example:
name = "Niharika"  # String variable
age = 20  # Integer variable
pi = 3.14  # Float variable

print(name)
print(age)
print(pi)

2️⃣ User Input in Python
The input() function allows users to enter data from the keyboard.
Example:
name = input("Enter your name: ")
print("Hello, " + name + "!")

3️⃣ Type Conversion (Casting)
Type conversion is used to convert one data type into another using functions like int(), float(), and str().
Example:
num_str = "25"
num_int = int(num_str)  # Convert string to integer
num_float = float(num_str)  # Convert string to float
print(num_int, type(num_int))
print(num_float, type(num_float))

4️⃣ Basic Arithmetic Operations
Python supports arithmetic operations like addition, subtraction, multiplication, division, and more.
Example:
a = 10
b = 3
print("Addition:", a + b)       
print("Subtraction:", a - b)     
print("Multiplication:", a * b)  
print("Division:", a / b)        
print("Floor Division:", a // b)  
print("Modulus:", a % b)         
print("Exponentiation:", a ** b)  

5️⃣ Operators in Python
Operators perform operations on variables.
Types of Operators:
Arithmetic Operators (+, -, *, /, //, %, **)
Comparison Operators (==, !=, >, <, >=, <=)
Logical Operators (and, or, not)
Assignment Operators (=, +=, -=, *=, /=, //=, %=, **=)
Bitwise Operators (&, |, ^, ~, <<, >>)

Example:
x = 5
y = 10

print(x == y)   
print(x != y)   
print(x > y)    
print(x < y)    
print(x >= y)   
print(x <= y)  


📝 Problem 1: Simple Interest Calculator
Write a Python program that takes principal amount, rate of interest, and time (in years) as input and calculates the simple interest using the formula:

Simple Interest = (Principal × Rate × Time) / 100
Code:
# Simple Interest Calculator
principal = float(input("Enter Principal amount: "))
rate = float(input("Enter Rate of Interest: "))
time = float(input("Enter Time (in years): "))
simple_interest = (principal * rate * time) / 100
print("Simple Interest:", simple_interest)
Example Input:
Enter Principal amount: 1000  
Enter Rate of Interest: 5  
Enter Time (in years): 3  
Example Output:
Simple Interest: 150.0


📝 Problem 2: Area of a Circle
Write a program to calculate the area of a circle given the radius.
Formula:
Area = π × r²
Code:
import math
radius = float(input("Enter the radius of the circle: "))
area = math.pi * radius ** 2
print("Area of Circle:", round(area, 2))
Example Input:
Enter the radius of the circle: 7  
Example Output:
Area of Circle: 153.94


📝 Problem 3: Swap Two Numbers (Using Temporary Variable)
Write a Python program to swap two numbers using a temporary variable.
Code:
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
temp = a
a = b
b = temp
print("After swapping:")
print("First number:", a)
print("Second number:", b)
Example Input:
Enter first number: 5  
Enter second number: 10  
Example Output:
After swapping:  
First number: 10  
Second number: 5  


📝 Problem 4: Temperature Converter
Convert Celsius to Fahrenheit using the formula:
Fahrenheit = (Celsius × 9/5) + 32
Code:
celsius = float(input("Enter temperature in Celsius: "))
fahrenheit = (celsius * 9/5) + 32
print("Temperature in Fahrenheit:", fahrenheit, "°F")
Example Input:
Enter temperature in Celsius: 25  
Example Output:
Temperature in Fahrenheit: 77.0°F


📝 Problem 5: Even or Odd Number Checker
Write a program that takes an integer as input and checks whether it is even or odd.
Code:
num = int(input("Enter a number: "))
if num % 2 == 0:
    print(num, "is an even number.")
else:
    print(num, "is an odd number.")
Example Input:
Enter a number: 7  
Example Output:
7 is an odd number.


📝 Problem 6: Sum of Digits
Write a program to calculate the sum of the digits of a three-digit number.
Code:
num = int(input("Enter a three-digit number: "))
sum_of_digits = sum(int(digit) for digit in str(num))
print("Sum of digits:", sum_of_digits)
Example Input:
Enter a three-digit number: 123  
Example Output:
Sum of digits: 6  (1 + 2 + 3)


📝 Problem 7: Maximum of Two Numbers
Write a program that takes two numbers as input and prints the larger number.
Code:
num1 = int(input("Enter first number: "))
num2 = int(input("Enter second number: "))
max_num = max(num1, num2)
print("Maximum number is:", max_num)
Example Input:
Enter first number: 25  
Enter second number: 42  
Example Output:
Maximum number is: 42


📝 Problem 8: Bill Splitter
Write a program that takes the total bill amount and the number of people and calculates how much each person should pay.
Code:
total_bill = float(input("Enter total bill amount: "))
num_people = int(input("Enter number of people: "))
amount_per_person = total_bill / num_people
print("Each person should pay:", round(amount_per_person, 2))
Example Input:
Enter total bill amount: 2000  
Enter number of people: 4  
Example Output:
Each person should pay: 500.0


📝 Problem 9: Power of a Number
Write a program that takes a base number and an exponent as input and calculates the result using the ** operator.
Code:
base = int(input("Enter base number: "))
exponent = int(input("Enter exponent: "))
result = base ** exponent
print("Result:", result)
Example Input:
Enter base number: 2  
Enter exponent: 5  
Example Output:
Result: 32  (2^5)


📝 Problem 10: Check Positive, Negative, or Zero
Write a program that takes a number as input and checks if it is positive, negative, or zero.
Code:
num = float(input("Enter a number: "))
if num > 0:
    print("The number is positive.")
elif num < 0:
    print("The number is negative.")
else:
    print("The number is zero.")
Example Input:
Enter a number: -8  
Example Output:
The number is negative.
