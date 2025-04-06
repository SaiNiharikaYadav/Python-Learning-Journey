Day 4: Python Basics – Functions, Loops, Lists, and Tuples
✅ Topics Covered:
Functions
For and While Loops
Lists and List Comprehension
Tuples
Dictionaries

📘 Concept Overview:
🔹 Functions:
Functions are reusable blocks of code that perform a specific task. You can pass data (arguments) to a function and get a result (return value).

def: Used to define a function.

Parameters: The inputs to a function.

Return: A function can return a value using the return keyword.

🔹 For and While Loops:
Loops are used to repeat a block of code multiple times.

For loop: Iterates over a sequence (list, range, etc.)

While loop: Repeats a block of code as long as the given condition is true.

🔹 Lists:
Lists are ordered collections of items, which can be of different types. Lists are mutable, meaning you can change their values.

List comprehension: A concise way to create a list.

🔹 Tuples:
Tuples are immutable sequences of values. Once defined, you cannot change their contents.

🔹 Dictionaries:
Dictionaries store key-value pairs. They are unordered and mutable.

📝 Practice Questions with Code and Output
✅ Problem 1: Calculate the factorial of a number
def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

num = int(input("Enter a number: "))
print("Factorial:", factorial(num))
Output:
Enter a number: 5
Factorial: 120
✅ Problem 2: Check if a number is even or odd using a function
def is_even(num):
    return num % 2 == 0

num = int(input("Enter a number: "))
if is_even(num):
    print(f"{num} is even.")
else:
    print(f"{num} is odd.")
Output:
Enter a number: 7
7 is odd.
✅ Problem 3: Loop through a list of numbers and print each element
numbers = [1, 2, 3, 4, 5]

for number in numbers:
    print(number)
Output:
1
2
3
4
5
✅ Problem 4: Find the largest number in a list using a for loop
numbers = [5, 10, 3, 20, 15]

max_num = numbers[0]

for num in numbers:
    if num > max_num:
        max_num = num

print("Largest number:", max_num)
Output:
Largest number: 20
✅ Problem 5: Create a list of squares of numbers from 1 to 10 using list comprehension
squares = [x**2 for x in range(1, 11)]
print("List of squares:", squares)
Output:
List of squares: [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]
✅ Problem 6: Create a tuple and print its elements
my_tuple = (10, 20, 30, 40, 50)

for item in my_tuple:
    print(item)
Output:
10
20
30
40
50
✅ Problem 7: Use a while loop to print numbers from 1 to 5
i = 1
while i <= 5:
    print(i)
    i += 1
utput:

1
2
3
4
5
✅ Problem 8: Create a dictionary that stores the frequency of elements in a list

my_list = ['apple', 'banana', 'apple', 'orange', 'banana', 'apple']

frequency = {}
for item in my_list:
    frequency[item] = frequency.get(item, 0) + 1

print(frequency)
Output:
{'apple': 3, 'banana': 2, 'orange': 1}
