# 🚀 Day 3: Python Basics – Conditional Statements and Logical Operations

---

## ✅ Topics Covered:

1. **If, elif, else statements**
2. **Comparison Operators**: `==`, `!=`, `<`, `>`, `<=`, `>=`
3. **Logical Operators**: `and`, `or`, `not`
4. **Nested if statements**
5. **Indentation rules in Python**

---

## 📘 Concept Overview:

### 🔹 If, elif, else statements:
These are control flow statements used to execute different blocks of code based on certain conditions.

- `if`: Executes a block of code if the condition is true.
- `elif`: Checks another condition if the previous ones are false.
- `else`: Executes a block if all previous conditions are false.

---

### 🔹 Comparison Operators:
Used to compare two values. They return a Boolean value (`True` or `False`).

- `==`: Equal to  
- `!=`: Not equal to  
- `>` : Greater than  
- `<` : Less than  
- `>=`: Greater than or equal to  
- `<=`: Less than or equal to

---

### 🔹 Logical Operators:
Used to combine conditional statements.

- `and`: Returns True if both conditions are true.
- `or`: Returns True if at least one condition is true.
- `not`: Reverses the result (True becomes False, and vice versa).

---

### 🔹 Nested if statements:
An if statement inside another if statement. It allows checking multiple layers of conditions.

---

### 🔹 Indentation rules in Python:
Indentation (spaces or tabs) is used to define blocks of code. Python relies on indentation to separate code blocks, unlike other languages that use braces.

---

## 📝 Practice Questions with Code and Output

---

### ✅ Problem 1: Check if a number is positive, negative, or zero

```python
num = float(input("Enter a number: "))

if num > 0:
    print("Positive number")
elif num < 0:
    print("Negative number")
else:
    print("Zero")
Output:
Enter a number: -4
Negative number
✅ Problem 2: Find the greatest of three numbers
a = int(input("Enter first number: "))
b = int(input("Enter second number: "))
c = int(input("Enter third number: "))

if a >= b and a >= c:
    print("Greatest number is:", a)
elif b >= a and b >= c:
    print("Greatest number is:", b)
else:
    print("Greatest number is:", c)
Output:
Enter first number: 23
Enter second number: 89
Enter third number: 45
Greatest number is: 89
✅ Problem 3: Voting Eligibility Checker
age = int(input("Enter your age: "))

if age >= 18:
    print("You are eligible to vote.")
else:
    print("You are not eligible to vote.")
Output:
Enter your age: 17
You are not eligible to vote.
✅ Problem 4: Password Match Validator
password = input("Enter your password: ")
confirm_password = input("Confirm your password: ")

if password == confirm_password:
    print("Password matched!")
else:
    print("Passwords do not match.")
Output:
Enter your password: hello123
Confirm your password: hello123
Password matched!
✅ Problem 5: Check if a number is divisible by both 3 and 5
num = int(input("Enter a number: "))

if num % 3 == 0 and num % 5 == 0:
    print(num, "is divisible by both 3 and 5.")
else:
    print(num, "is not divisible by both 3 and 5.")
Output:
Enter a number: 30
30 is divisible by both 3 and 5.
