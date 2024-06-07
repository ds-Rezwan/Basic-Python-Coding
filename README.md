# Basic-Python-Coding
1. Basic Syntax and Data Types
Variables and Data Types:

python
Copy code
# Integer 
x = 5

# Float
y = 3.14

# String
name = "Alice"

# Boolean
is_valid = True
Comments:

python
Copy code
# This is a single-line comment

"""
This is a
multi-line comment
"""
2. Basic Operations
Arithmetic Operations:

python
Copy code
a = 10
b = 3

print(a + b)  # Addition
print(a - b)  # Subtraction
print(a * b)  # Multiplication
print(a / b)  # Division
print(a % b)  # Modulus
print(a ** b) # Exponentiation
3. Collections
Lists:

python
Copy code
# List
numbers = [1, 2, 3, 4, 5]
print(numbers[0])  # Accessing the first element

# Add an element
numbers.append(6)

# Remove an element
numbers.remove(3)

# List slicing
print(numbers[1:3])  # Elements from index 1 to 2
Tuples:

python
Copy code
# Tuple (immutable list)
coordinates = (10, 20)
print(coordinates[0])
Dictionaries:

python
Copy code
# Dictionary
person = {
    "name": "Alice",
    "age": 25,
    "city": "New York"
}

print(person["name"])  # Access value by key
person["age"] = 26    # Update value
4. Control Flow
Conditional Statements:

python
Copy code
x = 10
if x > 0:
    print("Positive")
elif x == 0:
    print("Zero")
else:
    print("Negative")
Loops:

For Loop:

python
Copy code
# For loop
for i in range(5):  # 0 to 4
    print(i)

# Loop through a list
fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
While Loop:

python
Copy code
# While loop
count = 0
while count < 5:
    print(count)
    count += 1
5. Functions
Defining and Calling Functions:

python
Copy code
# Function definition
def greet(name):
    return "Hello, " + name

# Function call
print(greet("Alice"))
6. Classes and Objects
Basic Class Definition:

python
Copy code
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        return f"Hello, my name is {self.name} and I am {self.age} years old."

# Creating an object
person1 = Person("Alice", 30)
print(person1.greet())
7. Importing Modules
Using Modules:

python
Copy code
# Importing the math module
import math

print(math.sqrt(16))  # Using a function from the math module
8. File Handling
Reading and Writing Files:

python
Copy code
# Writing to a file
with open("example.txt", "w") as file:
    file.write("Hello, world!")

# Reading from a file
with open("example.txt", "r") as file:
    content = file.read()
    print(content)
9. Exception Handling
Try and Except Blocks:

python
Copy code
try:
    result = 10 / 0
except ZeroDivisionError:
    print("You can't divide by zero!")
finally:
    print("This will always execute.")
Summary
Python is known for its simplicity and readability, making it an excellent choice for beginners. The basics covered here, such as variables, data types, control flow, functions, classes, modules, file handling, and exception handling, provide a strong foundation for further exploration and learning in Python programming.






