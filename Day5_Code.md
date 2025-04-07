Day 5: Python Basics – Strings and String Operations
✅ Topics Covered:
String Basics
String Indexing and Slicing
String Methods
String Formatting
Looping Through Strings

📘 Concept Overview:
🔹 String Basics:
Strings in Python are sequences of characters enclosed in quotes (' ' or " ").
name = "Python"
🔹 String Indexing and Slicing:
Indexing: Access characters using index (0-based)
Slicing: Extract parts of a string using [start:end]
text = "Hello"
print(text[1])      # 'e'
print(text[1:4])    # 'ell'
🔹 String Methods:
Common methods include:
upper(), lower()
strip(), replace()
find(), count()
split(), join()

🔹 String Formatting:
Used to insert values into strings using:
f-strings: f"Hello {name}"
format(): "Hello {}".format(name)

🔹 Looping Through Strings:
You can iterate through characters in a string using loops.
for ch in "Python":
    print(ch)
📝 Practice Questions with Code and Output
✅ Problem 1: Reverse a string
text = input("Enter a string: ")
reversed_text = text[::-1]
print("Reversed string:", reversed_text)
Output:
Enter a string: hello
Reversed string: olleh
✅ Problem 2: Count vowels in a string
text = input("Enter a string: ").lower()
vowels = 'aeiou'
count = 0

for char in text:
    if char in vowels:
        count += 1

print("Number of vowels:", count)
Output:
Enter a string: Python
Number of vowels: 1
✅ Problem 3: Check if a string is a palindrome
text = input("Enter a string: ").lower()

if text == text[::-1]:
    print("Palindrome")
else:
    print("Not a palindrome")
Output:
Enter a string: madam
Palindrome
✅ Problem 4: Convert string to uppercase and lowercase
text = input("Enter a string: ")

print("Uppercase:", text.upper())
print("Lowercase:", text.lower())
Output:
Enter a string: Hello
Uppercase: HELLO
Lowercase: hello
✅ Problem 5: Replace a word in a string
sentence = input("Enter a sentence: ")
old = input("Word to replace: ")
new = input("New word: ")

new_sentence = sentence.replace(old, new)
print("Updated sentence:", new_sentence)
Output:
Enter a sentence: I love Python
Word to replace: Python
New word: Programming
Updated sentence: I love Programming
✅ Problem 6: Count frequency of characters in a string
text = input("Enter a string: ")
frequency = {}

for char in text:
    frequency[char] = frequency.get(char, 0) + 1

print("Character frequencies:")
for k, v in frequency.items():
    print(f"{k}: {v}")
Output:
Enter a string: apple
Character frequencies:
a: 1
p: 2
l: 1
e: 1
✅ Problem 7: Split a sentence into words and count them
sentence = input("Enter a sentence: ")
words = sentence.split()

print("Words:", words)
print("Total number of words:", len(words))
Output:
Enter a sentence: Python is awesome
Words: ['Python', 'is', 'awesome']
Total number of words: 3
