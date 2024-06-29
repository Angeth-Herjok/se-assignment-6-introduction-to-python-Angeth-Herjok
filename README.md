[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15348606&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level, interpreted programming language known for its readability and simplicity. It supports multiple programming paradigms, including procedural, object-oriented, and functional programming.

   Key Features:

   Easy to Learn and Use: Simple syntax that mimics natural language.
   Interpreted Language: Executes code line-by-line, which simplifies debugging.
   Dynamically Typed: No need to declare variable types explicitly.
   Extensive Standard Library: Rich set of modules and functions for various tasks.
   Community Support: Large and active community contributing to numerous libraries and frameworks.

   Use Cases:

   Web Development: Using frameworks like Django and Flask.
   Data Science and Machine Learning: With libraries such as Pandas, NumPy, and TensorFlow.
   Automation and Scripting: Automating repetitive tasks with scripts.
   Software Development: Building applications and tools.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

      Steps to Install Python:

   Windows:

   Download the installer from the official Python website.
   Run the installer and select "Add Python to PATH".
   Follow the installation prompts.

   macOS:

   Download the installer from the official Python website.
   Open the downloaded package and follow the instructions.

   Linux:

   Open a terminal.
   Run the command: sudo apt-get update.
   Install Python with: sudo apt-get install python3.
   Verify Installation:
   Open a terminal or command prompt and type:

   python --version
   or

   python3 --version

   Setting up a Virtual Environment:

   python -m venv myenv
   source myenv/bin/activate  # On Windows, use `myenv\Scripts\activate`

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Simple Program:

   print("Hello, World!")

   Explanation:

   print(): A built-in function that outputs text to the console.
   "Hello, World!": A string, a sequence of characters enclosed in quotes.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Data Types in Python:

   int: Integer numbers, e.g., 10.
   float: Floating-point numbers, e.g., 10.5.
   str: Strings, e.g., "Hello".
   bool: Boolean values, e.g., True or False.
   list: Ordered collection of items, e.g., [1, 2, 3].
   dict: Unordered collection of key-value pairs, e.g., {"key": "value"}.

   Script Example:

   # Integer
   a = 10
   # Float
   b = 20.5
   # String
   c = "Hello"
   # Boolean
   d = True
   # List
   e = [1, 2, 3]
   # Dictionary
   f = {"name": "Alice", "age": 25}

   print(a, b, c, d, e, f)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Conditional Statements:

   x = 10
   if x > 5:
      print("x is greater than 5")
   else:
      print("x is 5 or less")

   Loops:

   # For loop
   for i in range(5):
      print(i)

   # While loop
   i = 0
   while i < 5:
      print(i)
    i += 1

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Functions in Python:
   Functions are reusable blocks of code that perform a specific task. They help in making code modular and easier to manage.

   Function Example:

   def add(a, b):
      return a + b

   # Calling the function
   result = add(5, 3)
   print(result)  # Output: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Differences:

   List: Ordered, indexed by integers, allows duplicates.
   Dictionary: Unordered, indexed by keys, unique keys.
   Script Example:

   # List
   numbers = [1, 2, 3, 4, 5]
   print(numbers[0])  <!-- Accessing an element -->

   # Dictionary
   person = {"name": "Morice", "age": 25}
   print(person["name"])  <!-- Accessing a value by key -->

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   Example:

      try:
      x = 10 / 0
   except ZeroDivisionError:
      print("Division by zero is not allowed")
   finally:
      print("This will execute no matter what")


9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   Modules and Packages:

   Module: A single file containing Python code.
   Package: A collection of modules in directories.
   Import Example:

   import math

   print(math.sqrt(16))   <!-- Using the sqrt function from the math module -->

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   Reading from a File:

   with open('example.txt', 'r') as file:
      content = file.read()
      print(content)

   Writing to a File:

   lines = ["First line", "Second line", "Third line"]
   with open('output.txt', 'w') as file:
      for line in lines:
         file.write(line + "\n")

# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


