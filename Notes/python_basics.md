# Python Basics

This file contains my notes on the fundamental concepts of Python. I'll update it as I learn more!

---

## Table of Contents
1. [Variables and Data Types](#variables-and-data-types)
2. [Input and Output](#input-and-output)
3. [Operators](#operators)
4. [Conditional Statements](#conditional-statements)
5. [Loops](#loops)
6. [Functions](#functions)
7. [Lists](#lists)
8. [Tuples](#tuples)
9. [Dictionaries](#dictionaries)
10. [Sets](#sets)
11. [Strings](#strings)
12. [File Handling](#file-handling)
13. [Error Handling](#error-handling)
14. [Modules and Packages](#modules-and-packages)
15. [Additional Notes](#additional-notes)

---

## Variables and Data Types
- **Variables**: Used to store data. Example:
  ```python
  x = 10
  name = "Alice" 
  ``` 

- **Data Types:** 
  - Integers (int): 10, -5
  - Floats (float): 3.14, -0.001 
  - Strings (str): "Hello", 'Python' 
  - Booleans (bool): True, False
  - None: Represents absence of value.

## Input and Output
  - Input: Use input() to get user input.

  ```python
  name = input("Enter your name: ")
  Output: Use print() to display output. 
  ```

  ```python
  print("Hello, " + name) 
  ```
## Operators
  - Arithmetic: +, -, *, /, //, %, **

  - Comparison: ==, !=, >, <, >=, <=

  - Logical: and, or, not

  - Assignment: =, +=, -=, *=, /=

## Conditional Statements
  - **if-elif-else**:

```python
if x > 10:
    print("x is greater than 10")
elif x == 10:
    print("x is 10")
else:
    print("x is less than 10")
```
  - **Loops for Loop**:

```python
for i in range(5):
    print(i)
```
  - **while Loop**:

```python
while x > 0:
    print(x)
    x -= 1
```

## Functions

  - **Defining Functions**:

```python
def greet(name):
    return "Hello, " + name
```

  - **Lambda Functions**:

```python
square = lambda x: x ** 2
```

## Lists

  - **Creating Lists**:

```python
fruits = ["apple", "banana", "cherry"] 
```
  - **Accessing Elements**:

```python
print(fruits[0])  # Output: apple 
```

  - **List Methods**:
     - append(), remove(), sort(), reverse(), etc.

## Tuples

  - **Creating Tuples**:

```python
coordinates = (10, 20) 
```
  - Immutable: Cannot be changed after creation.


## Dictionaries

- **Creating Dictionaries**:

```python
person = {"name": "Alice", "age": 25} 
```
- **Accessing Values**:

```python
print(person["name"])  # Output: Alice 
```

## Sets

- **Creating Sets**:

```python
unique_numbers = {1, 2, 3, 3}  # Output: {1, 2, 3}
```
- Set Operations: Union, intersection, difference.

## Strings

- **String Methods**:

  - upper(), lower(), strip(), split(), replace(), etc.

- **String Formatting**:

```python
name = "Alice"
print(f"Hello, {name}!")
```
## File Handling

- **Reading Files**:

```python
with open("file.txt", "r") as file:
    content = file.read()
```
- **Writing Files**:

```python
with open("file.txt", "w") as file:
    file.write("Hello, World!")
```
## Error Handling
- **try-except**:

```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")
```

## Modules and Packages

- **Importing Modules**:

```python
import math
print(math.sqrt(16))  # Output: 4.0
```
- Creating Packages: Organize code into reusable modules.

## Additional Notes
- Python is case-sensitive.

- Use # for single-line comments and """ for multi-line comments.

- Always follow PEP 8 style guidelines for clean and readable code.