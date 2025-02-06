<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Data Science Learning Path for Beginners</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; margin: 20px; }
    pre { background: #f4f4f4; padding: 10px; overflow-x: auto; }
    code { background: #f4f4f4; padding: 2px 4px; }
    h1, h2, h3, h4 { color: #2c3e50; }
    ul { margin-bottom: 1em; }
    .module { border: 1px solid #ddd; padding: 15px; margin-bottom: 30px; }
    .module h2 { background: #ecf0f1; padding: 10px; }
  </style>
</head>
<body>

  <h1>Data Science Learning Path for Beginners</h1>
  <p>This comprehensive 12‑module guide is designed for students with little or no technical background. It starts with basic computer and programming skills and builds up to advanced AI integrations, including use of the OpenAI API and DeepSeek AI. Each module is organized into 10 detailed topics with multiple subtopics and code examples.</p>

  <!-- Module 1 -->
  <div class="module" id="module1">
    <h2>Module 1: Getting Started with Computers &amp; Python</h2>
    <p><strong>Introduction:</strong> In Module 1, we introduce basic computer concepts, how to install Python, and run your first Python program. This module is ideal even if you have only just begun using a computer.</p>
    
    <h3>1. Understanding Computers and Operating Systems</h3>
    <ul>
      <li><strong>What is a Computer?</strong>
        <p>Explanation of hardware and software concepts.</p>
        <pre><code># No code for this concept; this is an explanation.
</code></pre>
      </li>
      <li><strong>Introduction to Operating Systems (Windows, macOS, Linux)</strong>
        <p>Overview of popular OS features.</p>
      </li>
      <li><strong>Using the Command Line/Terminal</strong>
        <p>Basic commands to navigate your computer.</p>
        <pre><code># List files in a directory
ls
# Change directory
cd Documents
</code></pre>
      </li>
      <li><strong>Setting Up Your Workspace</strong>
        <p>How to install Python and a code editor (e.g., VSCode).</p>
      </li>
    </ul>
    
    <h3>2. Installing Python and Required Tools</h3>
    <ul>
      <li><strong>Downloading Python from the Official Website</strong>
        <p>Step-by-step guide for installation.</p>
      </li>
      <li><strong>Verifying Your Python Installation</strong>
        <pre><code>python --version
</code></pre>
      </li>
      <li><strong>Installing a Code Editor (VSCode/Atom)</strong>
        <p>Download and basic configuration.</p>
      </li>
      <li><strong>Setting Up Virtual Environments</strong>
        <p>Creating an isolated environment for your projects.</p>
        <pre><code>python -m venv myenv
source myenv/bin/activate  # On Windows: myenv\Scripts\activate
</code></pre>
      </li>
    </ul>
    
    <h3>3. Writing Your First Python Program</h3>
    <ul>
      <li><strong>Hello World in Python</strong>
        <pre><code>print("Hello, World!")
</code></pre>
      </li>
      <li><strong>Understanding the Print Function</strong>
        <p>Explanation of functions and strings.</p>
      </li>
      <li><strong>Saving and Running Python Scripts</strong>
        <p>How to create a .py file and execute it.</p>
        <pre><code>python hello_world.py
</code></pre>
      </li>
      <li><strong>Error Messages and Debugging Basics</strong>
        <p>Simple troubleshooting steps.</p>
      </li>
    </ul>
    
    <h3>4. Understanding Python Syntax &amp; Comments</h3>
    <ul>
      <li><strong>Basic Syntax Rules</strong>
        <p>Indentation and code blocks.</p>
        <pre><code>if True:
    print("This is properly indented!")
</code></pre>
      </li>
      <li><strong>Writing Comments</strong>
        <pre><code># This is a single-line comment
print("Comments help explain code!")
</code></pre>
      </li>
      <li><strong>Multi-line Comments</strong>
        <pre><code>"""
This is a multi-line comment.
It can span several lines.
"""
</code></pre>
      </li>
      <li><strong>Importance of Readable Code</strong>
        <p>Why clean code matters in programming.</p>
      </li>
    </ul>
    
    <h3>5. Using the Python Interpreter</h3>
    <ul>
      <li><strong>Interactive Mode vs Script Mode</strong>
        <p>Differences between running code interactively and as a script.</p>
      </li>
      <li><strong>Launching the Python Shell</strong>
        <pre><code>python
</code></pre>
      </li>
      <li><strong>Running Simple Commands in the Shell</strong>
        <pre><code>>> print("Interactive Python Shell")
</code></pre>
      </li>
      <li><strong>Exiting the Interpreter</strong>
        <pre><code>exit()
</code></pre>
      </li>
    </ul>
    
    <h3>6. Understanding Data Types</h3>
    <ul>
      <li><strong>Introduction to Strings</strong>
        <pre><code>greeting = "Hello, World!"
print(greeting)
</code></pre>
      </li>
      <li><strong>Numbers (Integers and Floats)</strong>
        <pre><code>integer_num = 5
float_num = 5.5
print(integer_num, float_num)
</code></pre>
      </li>
      <li><strong>Booleans</strong>
        <pre><code>is_valid = True
print(is_valid)
</code></pre>
      </li>
      <li><strong>Type Conversion</strong>
        <pre><code>num_str = "10"
num_int = int(num_str)
print(num_int)
</code></pre>
      </li>
    </ul>
    
    <h3>7. Basic Input and Output</h3>
    <ul>
      <li><strong>Using the <code>input()</code> Function</strong>
        <pre><code>name = input("Enter your name: ")
print("Hello, " + name)
</code></pre>
      </li>
      <li><strong>Formatted String Output</strong>
        <pre><code>age = 25
print(f"You are {age} years old.")
</code></pre>
      </li>
      <li><strong>Basic Error Handling for Input</strong>
        <p>Ensuring user enters the correct type of data.</p>
      </li>
      <li><strong>Simple Data Display Techniques</strong></li>
    </ul>
    
    <h3>8. Simple Arithmetic and Operators</h3>
    <ul>
      <li><strong>Addition, Subtraction, Multiplication, Division</strong>
        <pre><code>a = 10
b = 5
print(a + b, a - b, a * b, a / b)
</code></pre>
      </li>
      <li><strong>Modulus and Exponentiation</strong>
        <pre><code>print(10 % 3, 2 ** 3)
</code></pre>
      </li>
      <li><strong>Operator Precedence</strong>
        <p>Explaining order of operations.</p>
      </li>
      <li><strong>Combining Operations in One Expression</strong>
        <pre><code>result = (a + b) * (a - b)
print(result)
</code></pre>
      </li>
    </ul>
    
    <h3>9. Working with Variables</h3>
    <ul>
      <li><strong>Declaring Variables</strong>
        <pre><code>my_variable = 42
print(my_variable)
</code></pre>
      </li>
      <li><strong>Variable Naming Conventions</strong>
        <p>Best practices for names.</p>
      </li>
      <li><strong>Reassigning Variables</strong>
        <pre><code>my_variable = "Now a string"
print(my_variable)
</code></pre>
      </li>
      <li><strong>Scope of Variables (Local vs Global)</strong>
        <p>Introduction to variable scope in functions.</p>
      </li>
    </ul>
    
    <h3>10. Debugging Your First Program</h3>
    <ul>
      <li><strong>Identifying Common Errors</strong>
        <p>Syntax vs runtime errors.</p>
      </li>
      <li><strong>Using Print Statements to Debug</strong>
        <pre><code>x = 10
print("x is:", x)
</code></pre>
      </li>
      <li><strong>Reading Error Messages</strong>
        <p>How to interpret traceback messages.</p>
      </li>
      <li><strong>Practice Debugging Exercises</strong>
        <p>Simple faulty code snippet and walkthrough.</p>
        <pre><code># Faulty code example
# x = 10
# if x = 10:  # This should be '=='
#     print("x is 10")
# Corrected:
x = 10
if x == 10:
    print("x is 10")
</code></pre>
      </li>
    </ul>
  </div>
  <!-- End Module 1 -->

  <!-- Module 2 -->
  <div class="module" id="module2">
    <h2>Module 2: Python Data Types &amp; Basic Operations</h2>
    <p><strong>Introduction:</strong> This module delves into Python’s core data types and operations. Learn about strings, numbers, lists, tuples, dictionaries, and sets. Every topic is explained with clear code examples.</p>
    
    <h3>1. Strings and Their Operations</h3>
    <ul>
      <li><strong>Declaring and Printing Strings</strong>
        <pre><code>my_string = "Data Science is fun!"
print(my_string)
</code></pre>
      </li>
      <li><strong>Concatenation and Repetition</strong>
        <pre><code>print("Hello " + "World!")
print("Echo! " * 3)
</code></pre>
      </li>
      <li><strong>String Formatting Methods</strong>
        <pre><code>name = "Alice"
print("Hello, {}!".format(name))
print(f"Hello, {name}!")
</code></pre>
      </li>
      <li><strong>Common String Methods</strong>
        <pre><code>s = "python programming"
print(s.upper(), s.capitalize(), s.split())
</code></pre>
      </li>
    </ul>
    
    <h3>2. Numeric Data Types and Operations</h3>
    <ul>
      <li><strong>Integers and Floats</strong>
        <pre><code>a = 10       # Integer
b = 3.14     # Float
print(a, b)
</code></pre>
      </li>
      <li><strong>Arithmetic Operators</strong>
        <pre><code>print(a + b, a - b, a * b, a / b)
</code></pre>
      </li>
      <li><strong>Mathematical Functions (using the math module)</strong>
        <pre><code>import math
print(math.sqrt(16), math.floor(3.7))
</code></pre>
      </li>
      <li><strong>Type Conversion between Numeric Types</strong>
        <pre><code>num_str = "100"
num = int(num_str)
print(num)
</code></pre>
      </li>
    </ul>
    
    <h3>3. Lists and List Operations</h3>
    <ul>
      <li><strong>Creating a List</strong>
        <pre><code>fruits = ["apple", "banana", "cherry"]
print(fruits)
</code></pre>
      </li>
      <li><strong>Indexing and Slicing Lists</strong>
        <pre><code>print(fruits[0], fruits[1:3])
</code></pre>
      </li>
      <li><strong>Adding, Removing, and Updating List Items</strong>
        <pre><code>fruits.append("date")
fruits.remove("banana")
fruits[0] = "avocado"
print(fruits)
</code></pre>
      </li>
      <li><strong>Iterating Over Lists</strong>
        <pre><code>for fruit in fruits:
    print(fruit)
</code></pre>
      </li>
    </ul>
    
    <h3>4. Tuples and Their Characteristics</h3>
    <ul>
      <li><strong>Creating a Tuple</strong>
        <pre><code>dimensions = (1920, 1080)
print(dimensions)
</code></pre>
      </li>
      <li><strong>Accessing Tuple Elements</strong>
        <pre><code>width, height = dimensions
print(width, height)
</code></pre>
      </li>
      <li><strong>Immutability of Tuples</strong>
        <p>Once created, tuples cannot be changed.</p>
      </li>
      <li><strong>Tuple Packing and Unpacking</strong>
        <pre><code>a, b = 5, 10
print(a, b)
</code></pre>
      </li>
    </ul>
    
    <h3>5. Dictionaries for Key-Value Mapping</h3>
    <ul>
      <li><strong>Creating a Dictionary</strong>
        <pre><code>student = {"name": "John", "age": 21}
print(student)
</code></pre>
      </li>
      <li><strong>Accessing Dictionary Values</strong>
        <pre><code>print(student["name"])
</code></pre>
      </li>
      <li><strong>Adding and Updating Entries</strong>
        <pre><code>student["major"] = "Data Science"
student["age"] = 22
print(student)
</code></pre>
      </li>
      <li><strong>Iterating Over Dictionaries</strong>
        <pre><code>for key, value in student.items():
    print(f"{key}: {value}")
</code></pre>
      </li>
    </ul>
    
    <h3>6. Sets and Their Uses</h3>
    <ul>
      <li><strong>Creating a Set</strong>
        <pre><code>unique_numbers = {1, 2, 3, 3, 4}
print(unique_numbers)  # Duplicates are removed
</code></pre>
      </li>
      <li><strong>Adding and Removing Elements from a Set</strong>
        <pre><code>unique_numbers.add(5)
unique_numbers.discard(2)
print(unique_numbers)
</code></pre>
      </li>
      <li><strong>Set Operations (Union, Intersection)</strong>
        <pre><code>set_a = {1, 2, 3}
set_b = {3, 4, 5}
print(set_a.union(set_b), set_a.intersection(set_b))
</code></pre>
      </li>
      <li><strong>When to Use Sets vs Lists</strong>
        <p>Explanation with examples.</p>
      </li>
    </ul>
    
    <h3>7. Type Conversion among Data Types</h3>
    <ul>
      <li><strong>Converting Strings to Lists</strong>
        <pre><code>s = "hello"
print(list(s))
</code></pre>
      </li>
      <li><strong>Converting Lists to Tuples</strong>
        <pre><code>l = [1, 2, 3]
t = tuple(l)
print(t)
</code></pre>
      </li>
      <li><strong>Converting Dictionaries to Lists of Keys</strong>
        <pre><code>print(list(student.keys()))
</code></pre>
      </li>
      <li><strong>Using Built-in Conversion Functions</strong>
        <p>Examples with int(), str(), float()</p>
      </li>
    </ul>
    
    <h3>8. Using Built-in Functions</h3>
    <ul>
      <li><strong>Common Functions (len, type, str, int)</strong>
        <pre><code>print(len(fruits), type(fruits))
</code></pre>
      </li>
      <li><strong>Lambda Functions</strong>
        <pre><code>square = lambda x: x * x
print(square(5))
</code></pre>
      </li>
      <li><strong>Map and Filter Functions</strong>
        <pre><code>numbers = [1, 2, 3, 4]
squared = list(map(lambda x: x ** 2, numbers))
print(squared)
</code></pre>
      </li>
      <li><strong>List Comprehensions</strong>
        <pre><code>squared = [x ** 2 for x in numbers]
print(squared)
</code></pre>
      </li>
    </ul>
    
    <h3>9. Understanding the Importance of Data Types in Data Science</h3>
    <ul>
      <li><strong>How Data is Represented in Code</strong>
        <p>Discussion and examples.</p>
      </li>
      <li><strong>Choosing the Right Data Structure for the Task</strong>
        <p>Pros and cons of lists, tuples, etc.</p>
      </li>
      <li><strong>Data Type Conversions in Real-World Applications</strong>
        <p>Example: Parsing CSV data.</p>
      </li>
      <li><strong>Practical Exercises</strong>
        <p>Interactive coding tasks.</p>
      </li>
    </ul>
    
    <h3>10. Review and Practice Exercises</h3>
    <ul>
      <li><strong>Mini-Project: Creating a Contact Book</strong>
        <p>Using dictionaries, lists, and basic input/output.</p>
        <pre><code>contacts = {}
name = input("Enter contact name: ")
number = input("Enter contact number: ")
contacts[name] = number
print("Contact saved:", contacts)
</code></pre>
      </li>
      <li><strong>Quizzes on Data Types</strong>
        <p>Multiple choice questions to review concepts.</p>
      </li>
      <li><strong>Debugging Practice Exercises</strong>
        <p>Find and fix errors in provided code snippets.</p>
      </li>
      <li><strong>Discussion and Q&amp;A Session</strong>
        <p>Recap key learnings and address any questions.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 2 -->

  <!-- Module 3 -->
  <div class="module" id="module3">
    <h2>Module 3: Control Structures, Loops &amp; Functions</h2>
    <p><strong>Introduction:</strong> This module introduces control flow elements such as conditionals, loops, and functions. Learn to make decisions in code, iterate over data, and write reusable functions.</p>
    
    <h3>1. Conditional Statements (if, elif, else)</h3>
    <ul>
      <li><strong>Basic if Statements</strong>
        <pre><code>x = 10
if x > 5:
    print("x is greater than 5")
</code></pre>
      </li>
      <li><strong>Using elif for Multiple Conditions</strong>
        <pre><code>if x > 15:
    print("x is large")
elif x > 5:
    print("x is moderate")
else:
    print("x is small")
</code></pre>
      </li>
      <li><strong>Nested Conditionals</strong>
        <pre><code>if x > 5:
    if x < 15:
        print("x is between 5 and 15")
</code></pre>
      </li>
      <li><strong>Short Hand Conditional Expressions</strong>
        <pre><code>result = "Even" if x % 2 == 0 else "Odd"
print(result)
</code></pre>
      </li>
    </ul>
    
    <h3>2. For Loops</h3>
    <ul>
      <li><strong>Basic For Loop Over a List</strong>
        <pre><code>fruits = ["apple", "banana", "cherry"]
for fruit in fruits:
    print(fruit)
</code></pre>
      </li>
      <li><strong>Looping with the range() Function</strong>
        <pre><code>for i in range(5):
    print(i)
</code></pre>
      </li>
      <li><strong>Using enumerate() for Index Tracking</strong>
        <pre><code>for index, fruit in enumerate(fruits):
    print(index, fruit)
</code></pre>
      </li>
      <li><strong>Nested Loops</strong>
        <pre><code>for i in range(3):
    for j in range(2):
        print(f"i={i}, j={j}")
</code></pre>
      </li>
    </ul>
    
    <h3>3. While Loops</h3>
    <ul>
      <li><strong>Basic while Loop Structure</strong>
        <pre><code>count = 0
while count < 5:
    print(count)
    count += 1
</code></pre>
      </li>
      <li><strong>Infinite Loops and How to Avoid Them</strong>
        <p>Discussion and examples with break conditions.</p>
      </li>
      <li><strong>Using break and continue Statements</strong>
        <pre><code>for i in range(10):
    if i == 5:
        break
    print(i)
</code></pre>
      </li>
      <li><strong>Loop Else Clause</strong>
        <pre><code>for i in range(3):
    print(i)
else:
    print("Loop finished without break")
</code></pre>
      </li>
    </ul>
    
    <h3>4. Functions: Definition &amp; Invocation</h3>
    <ul>
      <li><strong>Defining a Function with def</strong>
        <pre><code>def greet(name):
    return f"Hello, {name}!"
print(greet("Alice"))
</code></pre>
      </li>
      <li><strong>Parameters and Return Values</strong>
        <p>Explanation with examples.</p>
      </li>
      <li><strong>Default Arguments in Functions</strong>
        <pre><code>def power(base, exponent=2):
    return base ** exponent
print(power(3))
</code></pre>
      </li>
      <li><strong>Docstrings for Function Documentation</strong>
        <pre><code>def add(a, b):
    """Return the sum of a and b."""
    return a + b
print(add(5, 7))
</code></pre>
      </li>
    </ul>
    
    <h3>5. Understanding Variable Scope in Functions</h3>
    <ul>
      <li><strong>Local vs Global Variables</strong>
        <pre><code>global_var = "I am global"

def func():
    local_var = "I am local"
    print(local_var)
    print(global_var)

func()
</code></pre>
      </li>
      <li><strong>Modifying Global Variables</strong>
        <p>Using the <code>global</code> keyword when necessary.</p>
      </li>
      <li><strong>Function Parameters as Local Variables</strong>
        <p>Explanation with code examples.</p>
      </li>
      <li><strong>Nested Functions and Scoping Rules</strong>
        <p>Basic introduction to inner functions.</p>
      </li>
    </ul>
    
    <h3>6. Lambda Functions and Anonymous Functions</h3>
    <ul>
      <li><strong>Creating Lambda Functions</strong>
        <pre><code>multiply = lambda x, y: x * y
print(multiply(4, 5))
</code></pre>
      </li>
      <li><strong>Using Lambdas in Higher-Order Functions</strong>
        <pre><code>numbers = [1, 2, 3, 4]
squared = list(map(lambda x: x ** 2, numbers))
print(squared)
</code></pre>
      </li>
      <li><strong>Limitations of Lambda Functions</strong>
        <p>Discussion on readability and complexity.</p>
      </li>
      <li><strong>Comparing Lambdas with Regular Functions</strong>
        <p>When to use each approach.</p>
      </li>
    </ul>
    
    <h3>7. Recursion: Functions Calling Themselves</h3>
    <ul>
      <li><strong>Introduction to Recursion</strong>
        <p>Concept explanation with examples.</p>
      </li>
      <li><strong>Simple Recursive Function (Factorial)</strong>
        <pre><code>def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
print(factorial(5))
</code></pre>
      </li>
      <li><strong>Understanding Base Cases</strong>
        <p>Importance of stopping conditions.</p>
      </li>
      <li><strong>Recursion vs Iteration</strong>
        <p>Pros and cons discussion.</p>
      </li>
    </ul>
    
    <h3>8. Using Functions for Code Reusability</h3>
    <ul>
      <li><strong>Breaking Down a Problem into Functions</strong>
        <p>Example: A mini calculator application.</p>
        <pre><code>def add(a, b):
    return a + b
def subtract(a, b):
    return a - b
print("Sum:", add(10, 5))
print("Difference:", subtract(10, 5))
</code></pre>
      </li>
      <li><strong>Modular Code Design</strong>
        <p>How functions help in organizing code.</p>
      </li>
      <li><strong>Importing Functions from Other Files</strong>
        <pre><code># In a file called utils.py:
def greet(name):
    return f"Hi, {name}!"

# In your main script:
from utils import greet
print(greet("Bob"))
</code></pre>
      </li>
      <li><strong>Testing Functions with Simple Assertions</strong>
        <pre><code>assert add(2, 3) == 5
</code></pre>
      </li>
    </ul>
    
    <h3>9. Error Handling in Functions</h3>
    <ul>
      <li><strong>Using try and except Blocks</strong>
        <pre><code>def safe_divide(a, b):
    try:
        return a / b
    except ZeroDivisionError:
        return "Division by zero error"
print(safe_divide(10, 0))
</code></pre>
      </li>
      <li><strong>Handling Multiple Exceptions</strong>
        <pre><code>try:
    result = int("abc")
except ValueError:
    print("Conversion error!")
</code></pre>
      </li>
      <li><strong>The finally Block</strong>
        <pre><code>try:
    file = open("data.txt", "r")
except FileNotFoundError:
    print("File not found.")
finally:
    print("Execution complete.")
</code></pre>
      </li>
      <li><strong>Custom Exception Handling</strong>
        <p>How to raise and catch your own exceptions.</p>
      </li>
    </ul>
    
    <h3>10. Review and Hands-On Practice</h3>
    <ul>
      <li><strong>Mini-Project: Build a Simple Calculator</strong>
        <p>Incorporate conditionals, loops, and functions.</p>
        <pre><code>def calculator():
    while True:
        op = input("Enter operation (+, -, *, /) or 'exit' to quit: ")
        if op == 'exit':
            break
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        if op == '+':
            print("Result:", a + b)
        elif op == '-':
            print("Result:", a - b)
        elif op == '*':
            print("Result:", a * b)
        elif op == '/':
            print("Result:", a / b if b != 0 else "Error: Division by zero")
        else:
            print("Invalid operation!")
calculator()
</code></pre>
      </li>
      <li><strong>Q&amp;A Session on Control Structures</strong>
        <p>Recap key points and answer questions.</p>
      </li>
      <li><strong>Additional Coding Exercises</strong>
        <p>Practice problems on loops and functions.</p>
      </li>
      <li><strong>Peer Review and Debugging Sessions</strong>
        <p>Collaborate to find and fix errors.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 3 -->

  <!-- Module 4 -->
  <div class="module" id="module4">
    <h2>Module 4: Utilizing Generative AI Coding Assistants</h2>
    <p><strong>Introduction:</strong> In Module 4, learn how to use generative AI coding assistants (such as ChatGPT or GitHub Copilot) to help write code faster, troubleshoot, and learn programming concepts. Use these tools responsibly to enhance your learning.</p>
    
    <h3>1. Introduction to AI Coding Assistants</h3>
    <ul>
      <li><strong>What is a Generative AI Coding Assistant?</strong>
        <p>Overview of how these tools work.</p>
        <pre><code># The AI assistant provides code suggestions.
</code></pre>
      </li>
      <li><strong>Popular Tools (ChatGPT, GitHub Copilot)</strong>
        <p>Brief introduction to available tools.</p>
      </li>
      <li><strong>How AI Assistants Can Help You Code</strong>
        <p>Examples of suggestions, auto-completion, and debugging help.</p>
      </li>
      <li><strong>Ethical Considerations in Using AI Assistants</strong>
        <p>Discussion on responsible use and code ownership.</p>
      </li>
    </ul>
    
    <h3>2. Setting Up Access to an AI Assistant</h3>
    <ul>
      <li><strong>Registering for an AI Assistant Service</strong>
        <p>Step-by-step guide to sign up.</p>
      </li>
      <li><strong>Integrating the Assistant with Your Code Editor</strong>
        <p>Example: Installing the GitHub Copilot extension in VSCode.</p>
      </li>
      <li><strong>Configuring API Keys and Settings</strong>
        <p>Ensuring secure configuration.</p>
      </li>
      <li><strong>Troubleshooting Common Setup Issues</strong>
        <p>Basic tips for resolving problems.</p>
      </li>
    </ul>
    
    <h3>3. Basic Commands and Interactions</h3>
    <ul>
      <li><strong>How to Ask for Code Suggestions</strong>
        <p>Examples of prompts you can type.</p>
      </li>
      <li><strong>Getting Explanations of Code</strong>
        <pre><code># Ask your AI assistant: "Explain this code snippet:"
print("Hello, AI!")
</code></pre>
      </li>
      <li><strong>Using AI to Generate Boilerplate Code</strong>
        <p>Example: Generating a function template.</p>
      </li>
      <li><strong>Editing and Iterating on Suggestions</strong>
        <p>Practice refining code outputs.</p>
      </li>
    </ul>
    
    <h3>4. Debugging with AI Assistants</h3>
    <ul>
      <li><strong>Inputting Code Errors for Explanation</strong>
        <p>How to paste an error message for suggestions.</p>
      </li>
      <li><strong>Interpreting AI Debugging Feedback</strong>
        <p>Examples of debugging hints provided by the assistant.</p>
      </li>
      <li><strong>Improving Code Based on Suggestions</strong>
        <pre><code># Example scenario: Fixing a typo in a variable name
x = 10
print(x)  # AI suggests checking for variable misnaming
</code></pre>
      </li>
      <li><strong>Validating AI-Generated Fixes</strong>
        <p>Testing suggested changes in your code.</p>
      </li>
    </ul>
    
    <h3>5. Learning New Concepts via AI Assistance</h3>
    <ul>
      <li><strong>Asking for Code Examples</strong>
        <p>Example: “Show me a for-loop in Python.”</p>
      </li>
      <li><strong>Exploring Advanced Topics with AI</strong>
        <p>Example: “Explain decorators in Python with examples.”</p>
      </li>
      <li><strong>Comparing Multiple AI Responses</strong>
        <p>Reviewing and testing different outputs.</p>
      </li>
      <li><strong>Cross-Checking AI Suggestions with Documentation</strong>
        <p>Ensuring correctness and reliability.</p>
      </li>
    </ul>
    
    <h3>6. Writing Documentation and Comments with AI</h3>
    <ul>
      <li><strong>Generating Docstrings for Functions</strong>
        <pre><code>def add(a, b):
    """
    Returns the sum of a and b.
    """
    return a + b
</code></pre>
      </li>
      <li><strong>Using AI to Write Code Comments</strong>
        <p>Ask the AI: “Add comments to this code snippet.”</p>
      </li>
      <li><strong>Improving Readability of Code with AI</strong>
        <p>Discuss auto-formatting and style guides.</p>
      </li>
      <li><strong>Reviewing Documentation Consistency</strong>
        <p>Ensuring your code is well documented.</p>
      </li>
    </ul>
    
    <h3>7. Best Practices for AI-Assisted Coding</h3>
    <ul>
      <li><strong>Validating AI-Generated Code</strong>
        <p>Always test and understand suggestions.</p>
      </li>
      <li><strong>Integrating AI Assistance into Your Workflow</strong>
        <p>Step-by-step workflow with code examples.</p>
      </li>
      <li><strong>Understanding the Limitations of AI</strong>
        <p>AI may not always provide optimal solutions.</p>
      </li>
      <li><strong>Documenting AI Contributions in Your Projects</strong>
        <p>Keeping track of what was AI-assisted.</p>
      </li>
    </ul>
    
    <h3>8. Practical Exercises Using AI Assistants</h3>
    <ul>
      <li><strong>Task: Generate a Function to Compute Factorials</strong>
        <pre><code>def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
print(factorial(5))
</code></pre>
      </li>
      <li><strong>Task: Get an AI Explanation for a Code Error</strong>
        <p>Simulate an error scenario and analyze the AI feedback.</p>
      </li>
      <li><strong>Task: Request a Code Refactor for Improved Readability</strong>
        <p>Practice and compare different versions.</p>
      </li>
      <li><strong>Group Discussion: Sharing AI Tips</strong>
        <p>Discuss what worked well with your peers.</p>
      </li>
    </ul>
    
    <h3>9. Integrating AI in Daily Coding Practices</h3>
    <ul>
      <li><strong>Creating a Habit of Consulting AI</strong>
        <p>When and how to use the assistant during coding.</p>
      </li>
      <li><strong>Maintaining Code Quality and Originality</strong>
        <p>Ensuring your code remains uniquely yours.</p>
      </li>
      <li><strong>Documenting AI Interactions</strong>
        <p>Keeping a log of AI suggestions and modifications.</p>
      </li>
      <li><strong>Continuous Learning from AI Feedback</strong>
        <p>Using AI as a learning tool over time.</p>
      </li>
    </ul>
    
    <h3>10. Review, Q&amp;A, and Hands-On Project</h3>
    <ul>
      <li><strong>Mini-Project: Build a Simple Script Using AI Assistance</strong>
        <pre><code>def process_input():
    user_input = input("Enter some text: ")
    return user_input.upper()

print(process_input())
</code></pre>
      </li>
      <li><strong>Group Discussion: Sharing Experiences with AI Tools</strong>
        <p>What worked, what didn’t, and why.</p>
      </li>
      <li><strong>Q&amp;A Session on Best Practices</strong>
        <p>Clarify doubts and explore advanced queries.</p>
      </li>
      <li><strong>Feedback on AI Integration in Coding</strong>
        <p>Discuss improvements and suggestions.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 4 -->

  <!-- Module 5 -->
  <div class="module" id="module5">
    <h2>Module 5: Object-Oriented Programming (OOP) in Python</h2>
    <p><strong>Introduction:</strong> This module introduces Object-Oriented Programming. Learn the fundamentals of classes, objects, inheritance, and more through clear examples.</p>
    
    <h3>1. Introduction to OOP Concepts</h3>
    <ul>
      <li><strong>What is OOP?</strong>
        <p>Definition and benefits of object-oriented design.</p>
        <pre><code># OOP is a way to structure code using objects.
</code></pre>
      </li>
      <li><strong>Classes and Objects Explained</strong>
        <p>Conceptual explanation with examples.</p>
      </li>
      <li><strong>Real-World Analogies</strong>
        <p>Examples: Cars, Animals, etc.</p>
      </li>
      <li><strong>Comparing Procedural and Object-Oriented Approaches</strong>
        <p>Discussion on different coding paradigms.</p>
      </li>
    </ul>
    
    <h3>2. Defining Classes and Creating Objects</h3>
    <ul>
      <li><strong>Basic Class Definition</strong>
        <pre><code>class Animal:
    pass
</code></pre>
      </li>
      <li><strong>Creating an Instance (Object) of a Class</strong>
        <pre><code>class Animal:
    pass

dog = Animal()
print(dog)
</code></pre>
      </li>
      <li><strong>The <code>__init__</code> Method for Initialization</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name

cat = Animal("Whiskers")
print(cat.name)
</code></pre>
      </li>
      <li><strong>Instance Variables vs Class Variables</strong>
        <p>Explanation with code examples.</p>
        <pre><code>class Animal:
    species = "Mammal"  # Class variable
    def __init__(self, name):
        self.name = name  # Instance variable
</code></pre>
      </li>
    </ul>
    
    <h3>3. Methods and Their Uses</h3>
    <ul>
      <li><strong>Defining Instance Methods</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name
    def speak(self):
        return f"{self.name} makes a noise."

dog = Animal("Buddy")
print(dog.speak())
</code></pre>
      </li>
      <li><strong>Method Parameters and Self</strong>
        <p>Explanation of the <code>self</code> parameter.</p>
      </li>
      <li><strong>Class Methods vs Static Methods</strong>
        <pre><code>class Animal:
    @classmethod
    def general_info(cls):
        return "Animals are living organisms."
    @staticmethod
    def kingdom():
        return "Animalia"

print(Animal.general_info(), Animal.kingdom())
</code></pre>
      </li>
      <li><strong>Overriding Methods in Child Classes</strong>
        <p>Discussion and examples.</p>
      </li>
    </ul>
    
    <h3>4. Inheritance and Subclasses</h3>
    <ul>
      <li><strong>Concept of Inheritance</strong>
        <p>How subclasses inherit attributes and methods from parent classes.</p>
      </li>
      <li><strong>Creating a Subclass</strong>
        <pre><code>class Dog(Animal):
    def speak(self):
        return f"{self.name} barks."

dog = Dog("Max")
print(dog.speak())
</code></pre>
      </li>
      <li><strong>Using super() to Call Parent Methods</strong>
        <pre><code>class Cat(Animal):
    def __init__(self, name, color):
        super().__init__(name)
        self.color = color
    def speak(self):
        return f"{self.name} meows."

cat = Cat("Luna", "black")
print(cat.speak())
</code></pre>
      </li>
      <li><strong>Multiple Inheritance Overview</strong>
        <p>Simple example and cautionary notes.</p>
      </li>
    </ul>
    
    <h3>5. Encapsulation and Data Hiding</h3>
    <ul>
      <li><strong>Private vs Public Attributes</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance  # Private attribute
    def get_balance(self):
        return self.__balance

account = BankAccount(1000)
print(account.get_balance())
</code></pre>
      </li>
      <li><strong>Getter and Setter Methods</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance
    def deposit(self, amount):
        self.__balance += amount
    def get_balance(self):
        return self.__balance

account = BankAccount(1000)
account.deposit(500)
print(account.get_balance())
</code></pre>
      </li>
      <li><strong>Benefits of Encapsulation</strong>
        <p>Protection and maintainability of code.</p>
      </li>
      <li><strong>Using Properties for Cleaner Access</strong>
        <pre><code>class BankAccount:
    def __init__(self, balance):
        self.__balance = balance
    @property
    def balance(self):
        return self.__balance

account = BankAccount(1500)
print(account.balance)
</code></pre>
      </li>
    </ul>
    
    <h3>6. Polymorphism and Method Overriding</h3>
    <ul>
      <li><strong>What is Polymorphism?</strong>
        <p>Allowing methods to behave differently on different classes.</p>
      </li>
      <li><strong>Method Overriding in Subclasses</strong>
        <p>Using the same method name in different classes.</p>
      </li>
      <li><strong>Examples of Polymorphism in Python</strong>
        <pre><code>class Bird(Animal):
    def speak(self):
        return f"{self.name} chirps."

animals = [Dog("Rex"), Cat("Mia", "white"), Bird("Tweety")]
for animal in animals:
    print(animal.speak())
</code></pre>
      </li>
      <li><strong>Abstract Classes and Methods (Conceptual Introduction)</strong>
        <p>Using the <code>abc</code> module for abstract classes.</p>
      </li>
    </ul>
    
    <h3>7. Composition: Building Complex Objects</h3>
    <ul>
      <li><strong>Difference Between Inheritance and Composition</strong>
        <p>Explanation with examples.</p>
      </li>
      <li><strong>Using Composition to Build Objects</strong>
        <pre><code>class Engine:
    def start(self):
        return "Engine starting"
class Car:
    def __init__(self, engine):
        self.engine = engine
    def start(self):
        return self.engine.start()

my_car = Car(Engine())
print(my_car.start())
</code></pre>
      </li>
      <li><strong>Benefits of Composition</strong>
        <p>Flexibility and modularity in code design.</p>
      </li>
      <li><strong>Real-World Use Cases</strong>
        <p>Examples in various applications.</p>
      </li>
    </ul>
    
    <h3>8. Special Methods (Magic Methods)</h3>
    <ul>
      <li><strong>The <code>__str__</code> and <code>__repr__</code> Methods</strong>
        <pre><code>class Person:
    def __init__(self, name):
        self.name = name
    def __str__(self):
        return f"Person named {self.name}"
print(Person("Alice"))
</code></pre>
      </li>
      <li><strong>Operator Overloading</strong>
        <pre><code>class Vector:
    def __init__(self, x, y):
        self.x = x
        self.y = y
    def __add__(self, other):
        return Vector(self.x + other.x, self.y + other.y)
    def __str__(self):
        return f"Vector({self.x}, {self.y})"

v1 = Vector(1, 2)
v2 = Vector(3, 4)
print(v1 + v2)
</code></pre>
      </li>
      <li><strong>Implementing Length and Comparison Methods</strong>
        <p>Examples using <code>__len__</code>, <code>__eq__</code>, etc.</p>
      </li>
      <li><strong>Using __init__ for Custom Initialization</strong>
        <p>Advanced initialization techniques.</p>
      </li>
    </ul>
    
    <h3>9. Designing and Organizing Large Programs with OOP</h3>
    <ul>
      <li><strong>Structuring Your Project into Classes and Modules</strong>
        <p>Strategies for maintainable code organization.</p>
      </li>
      <li><strong>Using Packages to Group Related Classes</strong>
        <pre><code><!-- Example Directory Structure:
my_project/
├── animals/
│   ├── __init__.py
│   ├── dog.py
│   └── cat.py
└── main.py -->
</code></pre>
      </li>
      <li><strong>Documenting Your Classes</strong>
        <p>Importance of clear documentation and comments.</p>
      </li>
      <li><strong>Refactoring Existing Code into OOP</strong>
        <p>How to reorganize procedural code into object-oriented structures.</p>
      </li>
    </ul>
    
    <h3>10. Review and Hands-On OOP Project</h3>
    <ul>
      <li><strong>Mini-Project: Build a Simple Animal Simulator</strong>
        <pre><code>class Animal:
    def __init__(self, name):
        self.name = name
    def speak(self):
        return f"{self.name} makes a noise."

class Dog(Animal):
    def speak(self):
        return f"{self.name} barks."

class Cat(Animal):
    def speak(self):
        return f"{self.name} meows."

animals = [Dog("Rex"), Cat("Whiskers")]
for animal in animals:
    print(animal.speak())
</code></pre>
      </li>
      <li><strong>Q&amp;A and Code Review Sessions</strong>
        <p>Discuss challenges and improvements.</p>
      </li>
      <li><strong>Peer Programming Exercises</strong>
        <p>Work in pairs to extend and improve your code.</p>
      </li>
      <li><strong>Final Recap of OOP Concepts</strong>
        <p>Review and summarize key ideas.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 5 -->

  <!-- Module 6 -->
  <div class="module" id="module6">
    <h2>Module 6: Python Standard Libraries &amp; Modules</h2>
    <p><strong>Introduction:</strong> Learn how to use Python’s built-in libraries and modules to extend your code’s capabilities. This module covers topics like file handling, OS interaction, and creating your own modules.</p>
    
    <h3>1. Understanding Python Modules and Packages</h3>
    <ul>
      <li><strong>What Are Modules and Packages?</strong>
        <p>Definition and examples.</p>
        <pre><code># Modules are Python files; packages are directories with __init__.py files.
</code></pre>
      </li>
      <li><strong>How to Import Modules</strong>
        <pre><code>import math
print(math.pi)
</code></pre>
      </li>
      <li><strong>Using from-import Statements</strong>
        <pre><code>from math import sqrt
print(sqrt(16))
</code></pre>
      </li>
      <li><strong>Exploring Package Structure</strong>
        <p>Understanding how packages are organized.</p>
      </li>
    </ul>
    
    <h3>2. Working with the os Module</h3>
    <ul>
      <li><strong>Introduction to the os Module</strong>
        <p>Interacting with the operating system.</p>
        <pre><code>import os
print(os.getcwd())
</code></pre>
      </li>
      <li><strong>Navigating the File System</strong>
        <pre><code>print(os.listdir('.'))
</code></pre>
      </li>
      <li><strong>Creating and Removing Directories</strong>
        <pre><code>os.mkdir("new_folder")
os.rmdir("new_folder")
</code></pre>
      </li>
      <li><strong>Path Manipulation with os.path</strong>
        <pre><code>print(os.path.join("folder", "file.txt"))
</code></pre>
      </li>
    </ul>
    
    <h3>3. File Handling with the io Module</h3>
    <ul>
      <li><strong>Opening and Reading Files</strong>
        <pre><code>with open("example.txt", "w") as file:
    file.write("Hello, file!")
with open("example.txt", "r") as file:
    content = file.read()
print(content)
</code></pre>
      </li>
      <li><strong>Writing to Files</strong>
        <p>Examples of appending data.</p>
      </li>
      <li><strong>Using the csv Module for Data Files</strong>
        <pre><code>import csv
data = [["Name", "Age"], ["Alice", 30], ["Bob", 25]]
with open("people.csv", "w", newline="") as file:
    writer = csv.writer(file)
    writer.writerows(data)
</code></pre>
      </li>
      <li><strong>Error Handling During File I/O</strong>
        <p>Basic strategies to manage errors.</p>
      </li>
    </ul>
    
    <h3>4. Working with the datetime Module</h3>
    <ul>
      <li><strong>Getting the Current Date and Time</strong>
        <pre><code>from datetime import datetime
now = datetime.now()
print(now)
</code></pre>
      </li>
      <li><strong>Formatting Dates and Times</strong>
        <pre><code>print(now.strftime("%Y-%m-%d %H:%M:%S"))
</code></pre>
      </li>
      <li><strong>Performing Date Calculations</strong>
        <pre><code>from datetime import timedelta
tomorrow = now + timedelta(days=1)
print(tomorrow)
</code></pre>
      </li>
      <li><strong>Parsing Date Strings</strong>
        <p>Converting strings into datetime objects.</p>
      </li>
    </ul>
    
    <h3>5. Using the random Module</h3>
    <ul>
      <li><strong>Generating Random Numbers</strong>
        <pre><code>import random
print(random.randint(1, 10))
</code></pre>
      </li>
      <li><strong>Random Choice from a List</strong>
        <pre><code>options = ["red", "blue", "green"]
print(random.choice(options))
</code></pre>
      </li>
      <li><strong>Shuffling a List</strong>
        <pre><code>random.shuffle(options)
print(options)
</code></pre>
      </li>
      <li><strong>Simulating Random Events</strong>
        <p>Examples in simulations.</p>
      </li>
    </ul>
    
    <h3>6. Introduction to the re (Regular Expressions) Module</h3>
    <ul>
      <li><strong>What are Regular Expressions?</strong>
        <p>Definition and applications in text processing.</p>
      </li>
      <li><strong>Basic Pattern Matching</strong>
        <pre><code>import re
pattern = r"\d+"
match = re.findall(pattern, "There are 15 apples")
print(match)
</code></pre>
      </li>
      <li><strong>Search and Replace Operations</strong>
        <pre><code>text = "Hello 123, welcome 456"
replaced = re.sub(r"\d+", "#", text)
print(replaced)
</code></pre>
      </li>
      <li><strong>Understanding Regex Patterns</strong>
        <p>Examples of simple regex constructs.</p>
      </li>
    </ul>
    
    <h3>7. Third-Party Libraries and pip</h3>
    <ul>
      <li><strong>What is pip?</strong>
        <p>Introduction to Python’s package installer.</p>
        <pre><code>pip install requests
</code></pre>
      </li>
      <li><strong>Installing and Importing Third-Party Packages</strong>
        <pre><code>import requests
response = requests.get("https://api.github.com")
print(response.status_code)
</code></pre>
      </li>
      <li><strong>Managing Dependencies with requirements.txt</strong>
        <p>Example of listing packages.</p>
      </li>
      <li><strong>Updating and Removing Packages</strong>
        <p>Basic package management tips.</p>
      </li>
    </ul>
    
    <h3>8. Exploring the sys Module</h3>
    <ul>
      <li><strong>Accessing Command-Line Arguments</strong>
        <pre><code>import sys
print(sys.argv)
</code></pre>
      </li>
      <li><strong>Understanding sys.exit()</strong>
        <p>How to terminate a program gracefully.</p>
      </li>
      <li><strong>Interacting with Python Runtime Environment</strong>
        <p>Memory and version information.</p>
      </li>
      <li><strong>Debugging and Error Reporting with sys</strong>
        <p>Techniques for troubleshooting.</p>
      </li>
    </ul>
    
    <h3>9. Building Your Own Modules</h3>
    <ul>
      <li><strong>Creating a Python File as a Module</strong>
        <p>Example: A file named <code>mymodule.py</code> with a simple function.</p>
        <pre><code># File: mymodule.py
def hello(name):
    return f"Hello, {name}!"
</code></pre>
      </li>
      <li><strong>Importing Your Module</strong>
        <pre><code>from mymodule import hello
print(hello("Student"))
</code></pre>
      </li>
      <li><strong>Organizing Code into Packages</strong>
        <p>Directory structure and <code>__init__.py</code> usage.</p>
      </li>
      <li><strong>Best Practices for Module Design</strong>
        <p>Design tips for maintainable code.</p>
      </li>
    </ul>
    
    <h3>10. Review and Practical Exercises</h3>
    <ul>
      <li><strong>Mini-Project: Build a File Organizer Script</strong>
        <pre><code>import os, shutil

def organize_files(directory):
    for filename in os.listdir(directory):
        if os.path.isfile(os.path.join(directory, filename)):
            ext = filename.split('.')[-1]
            folder = os.path.join(directory, ext)
            os.makedirs(folder, exist_ok=True)
            shutil.move(os.path.join(directory, filename), folder)

organize_files(".")
</code></pre>
      </li>
      <li><strong>Group Discussion: Modules and Their Uses</strong>
        <p>Share interesting modules discovered during exploration.</p>
      </li>
      <li><strong>Hands-On Coding Challenges</strong>
        <p>Practice exercises using <code>os</code>, <code>datetime</code>, and <code>re</code>.</p>
      </li>
      <li><strong>Q&amp;A and Code Review Sessions</strong>
        <p>Discuss challenges and clarify doubts.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 6 -->

  <!-- Module 7 -->
  <div class="module" id="module7">
    <h2>Module 7: Introduction to Data Manipulation with NumPy</h2>
    <p><strong>Introduction:</strong> In Module 7, you are introduced to NumPy—the foundational library for numerical computing in Python. Learn array creation, operations, slicing, reshaping, and more.</p>
    
    <h3>1. Introduction to NumPy and Its Importance</h3>
    <ul>
      <li><strong>What is NumPy?</strong>
        <p>Overview of NumPy’s role in Data Science.</p>
        <pre><code># NumPy is a library for numerical operations.
</code></pre>
      </li>
      <li><strong>Installation and Importing NumPy</strong>
        <pre><code>pip install numpy
import numpy as np
</code></pre>
      </li>
      <li><strong>NumPy vs. Python Lists</strong>
        <p>Comparison with code examples.</p>
      </li>
      <li><strong>Basic Array Creation Concepts</strong>
        <p>Introduction to arrays.</p>
      </li>
    </ul>
    
    <h3>2. Creating Arrays from Lists and Tuples</h3>
    <ul>
      <li><strong>Using np.array()</strong>
        <pre><code>data = [1, 2, 3, 4]
arr = np.array(data)
print(arr)
</code></pre>
      </li>
      <li><strong>Multi-Dimensional Arrays</strong>
        <pre><code>matrix = np.array([[1, 2], [3, 4]])
print(matrix)
</code></pre>
      </li>
      <li><strong>Array Attributes (shape, dtype)</strong>
        <pre><code>print(arr.shape, arr.dtype)
</code></pre>
      </li>
      <li><strong>Creating Arrays with np.zeros(), np.ones(), np.eye()</strong>
        <p>Examples of generating special arrays.</p>
      </li>
    </ul>
    
    <h3>3. Basic Array Operations</h3>
    <ul>
      <li><strong>Element-Wise Arithmetic Operations</strong>
        <pre><code>a = np.array([1, 2, 3])
b = np.array([4, 5, 6])
print(a + b, a * b)
</code></pre>
      </li>
      <li><strong>Scalar Operations on Arrays</strong>
        <pre><code>print(a * 3)
</code></pre>
      </li>
      <li><strong>Using Universal Functions (ufuncs)</strong>
        <pre><code>print(np.sqrt(a))
</code></pre>
      </li>
      <li><strong>Understanding Broadcasting Rules</strong>
        <p>Explanation of how arrays are broadcast for operations.</p>
      </li>
    </ul>
    
    <h3>4. Array Slicing and Indexing</h3>
    <ul>
      <li><strong>One-Dimensional Array Slicing</strong>
        <pre><code>arr = np.array([10, 20, 30, 40, 50])
print(arr[1:4])
</code></pre>
      </li>
      <li><strong>Multi-Dimensional Array Indexing</strong>
        <pre><code>matrix = np.array([[1, 2, 3], [4, 5, 6]])
print(matrix[1, :])
</code></pre>
      </li>
      <li><strong>Using Boolean Indexing</strong>
        <pre><code>print(arr[arr > 25])
</code></pre>
      </li>
      <li><strong>Advanced Slicing Techniques</strong>
        <p>Further examples of slicing.</p>
      </li>
    </ul>
    
    <h3>5. Reshaping and Transposing Arrays</h3>
    <ul>
      <li><strong>Reshaping Arrays with np.reshape()</strong>
        <pre><code>arr = np.arange(12)
reshaped = arr.reshape((3, 4))
print(reshaped)
</code></pre>
      </li>
      <li><strong>Transposing Arrays</strong>
        <pre><code>print(reshaped.T)
</code></pre>
      </li>
      <li><strong>Flattening Arrays</strong>
        <pre><code>print(reshaped.flatten())
</code></pre>
      </li>
      <li><strong>Using np.newaxis for Dimension Expansion</strong>
        <p>How to add new dimensions.</p>
      </li>
    </ul>
    
    <h3>6. Mathematical Operations on Arrays</h3>
    <ul>
      <li><strong>Aggregate Functions (sum, mean, std)</strong>
        <pre><code>print(np.sum(reshaped), np.mean(reshaped), np.std(reshaped))
</code></pre>
      </li>
      <li><strong>Applying Mathematical Functions</strong>
        <pre><code>print(np.sin(arr))
</code></pre>
      </li>
      <li><strong>Element-Wise Comparisons and Logical Operations</strong>
        <pre><code>print(arr > 5)
</code></pre>
      </li>
      <li><strong>Using np.where for Conditional Selection</strong>
        <p>Examples of conditional array selection.</p>
      </li>
    </ul>
    
    <h3>7. Array Manipulations and Data Transformations</h3>
    <ul>
      <li><strong>Sorting Arrays</strong>
        <pre><code>arr = np.array([3, 1, 2])
print(np.sort(arr))
</code></pre>
      </li>
      <li><strong>Unique Elements and Counting Frequencies</strong>
        <pre><code>arr = np.array([1, 2, 2, 3, 3, 3])
print(np.unique(arr, return_counts=True))
</code></pre>
      </li>
      <li><strong>Concatenating and Splitting Arrays</strong>
        <pre><code>a = np.array([1, 2])
b = np.array([3, 4])
print(np.concatenate([a, b]))
</code></pre>
      </li>
      <li><strong>Stacking Arrays Vertically and Horizontally</strong>
        <p>Examples of stacking arrays.</p>
      </li>
    </ul>
    
    <h3>8. Working with Random Data</h3>
    <ul>
      <li><strong>Generating Random Arrays</strong>
        <pre><code>random_arr = np.random.rand(3, 3)
print(random_arr)
</code></pre>
      </li>
      <li><strong>Random Integers and Normal Distributions</strong>
        <pre><code>print(np.random.randint(0, 10, size=(2, 2)))
</code></pre>
      </li>
      <li><strong>Seeding for Reproducibility</strong>
        <pre><code>np.random.seed(42)
print(np.random.rand(2, 2))
</code></pre>
      </li>
      <li><strong>Applications in Data Simulation</strong>
        <p>Discuss practical use cases.</p>
      </li>
    </ul>
    
    <h3>9. Performance Benefits of NumPy</h3>
    <ul>
      <li><strong>Vectorized Operations vs. Loops</strong>
        <p>Comparative examples and timings using <code>timeit</code>.</p>
      </li>
      <li><strong>Memory Efficiency of Arrays</strong>
        <p>How arrays use memory better than lists.</p>
      </li>
      <li><strong>Using NumPy for Large-Scale Data</strong>
        <p>Examples in scientific computing.</p>
      </li>
      <li><strong>Profiling NumPy Code for Optimization</strong>
        <p>Tools and techniques for profiling.</p>
      </li>
    </ul>
    
    <h3>10. Review and Practical NumPy Exercises</h3>
    <ul>
      <li><strong>Mini-Project: Data Analysis on a Simulated Dataset</strong>
        <pre><code>import numpy as np
# Simulate daily temperatures over a week
temps = np.random.randint(60, 100, size=7)
print("Temperatures:", temps)
print("Average Temperature:", np.mean(temps))
</code></pre>
      </li>
      <li><strong>Hands-On Exercises: Array Manipulations</strong>
        <p>Practice slicing, reshaping, and aggregations.</p>
      </li>
      <li><strong>Q&amp;A and Discussion on NumPy Challenges</strong>
        <p>Discuss common pitfalls and optimization tips.</p>
      </li>
      <li><strong>Recap of Core Concepts and Next Steps</strong>
        <p>Summarize key ideas.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 7 -->

  <!-- Module 8 -->
  <div class="module" id="module8">
    <h2>Module 8: Data Analysis with Pandas</h2>
    <p><strong>Introduction:</strong> This module introduces Pandas for data manipulation and analysis. Learn to work with DataFrames, clean data, perform aggregations, and visualize data.</p>
    
    <h3>1. Introduction to Pandas and DataFrames</h3>
    <ul>
      <li><strong>What is Pandas?</strong>
        <p>Overview of its role in data analysis.</p>
        <pre><code># Pandas provides DataFrame and Series objects.
</code></pre>
      </li>
      <li><strong>Installing and Importing Pandas</strong>
        <pre><code>pip install pandas
import pandas as pd
</code></pre>
      </li>
      <li><strong>Creating a DataFrame from a Dictionary</strong>
        <pre><code>data = {"Name": ["Alice", "Bob"], "Age": [25, 30]}
df = pd.DataFrame(data)
print(df)
</code></pre>
      </li>
      <li><strong>Understanding Series Objects</strong>
        <p>Explanation of one-dimensional data.</p>
      </li>
    </ul>
    
    <h3>2. Reading and Writing Data Files</h3>
    <ul>
      <li><strong>Loading CSV Files</strong>
        <pre><code>df = pd.read_csv("data.csv")
print(df.head())
</code></pre>
      </li>
      <li><strong>Writing DataFrames to CSV</strong>
        <pre><code>df.to_csv("output.csv", index=False)
</code></pre>
      </li>
      <li><strong>Working with Excel Files</strong>
        <pre><code>df_excel = pd.read_excel("data.xlsx")
</code></pre>
      </li>
      <li><strong>Other File Formats (JSON, HTML)</strong>
        <p>Overview of additional formats.</p>
      </li>
    </ul>
    
    <h3>3. Exploring and Inspecting Data</h3>
    <ul>
      <li><strong>DataFrame Attributes: shape, dtypes, info()</strong>
        <pre><code>print(df.shape)
print(df.info())
</code></pre>
      </li>
      <li><strong>Descriptive Statistics (mean, median, describe())</strong>
        <pre><code>print(df.describe())
</code></pre>
      </li>
      <li><strong>Selecting Columns and Rows</strong>
        <pre><code>print(df["Name"])
print(df.iloc[0])
</code></pre>
      </li>
      <li><strong>Filtering Data Based on Conditions</strong>
        <pre><code>print(df[df["Age"] > 25])
</code></pre>
      </li>
    </ul>
    
    <h3>4. Data Cleaning and Handling Missing Values</h3>
    <ul>
      <li><strong>Identifying Missing Data</strong>
        <pre><code>print(df.isnull().sum())
</code></pre>
      </li>
      <li><strong>Dropping Missing Data</strong>
        <pre><code>df_clean = df.dropna()
</code></pre>
      </li>
      <li><strong>Filling Missing Data</strong>
        <pre><code>df_filled = df.fillna("Unknown")
</code></pre>
      </li>
      <li><strong>Data Type Conversions</strong>
        <p>Converting data types as needed.</p>
      </li>
    </ul>
    
    <h3>5. Data Transformation and Aggregation</h3>
    <ul>
      <li><strong>Using apply() to Transform Data</strong>
        <pre><code>df["Name"] = df["Name"].apply(lambda x: x.upper())
print(df)
</code></pre>
      </li>
      <li><strong>Grouping Data with groupby()</strong>
        <pre><code>grouped = df.groupby("Age").count()
print(grouped)
</code></pre>
      </li>
      <li><strong>Pivot Tables and Crosstabs</strong>
        <p>Examples of reshaping data.</p>
      </li>
      <li><strong>Merging and Joining DataFrames</strong>
        <pre><code>df1 = pd.DataFrame({"ID": [1, 2], "Value": [10, 20]})
df2 = pd.DataFrame({"ID": [1, 2], "Category": ["A", "B"]})
merged = pd.merge(df1, df2, on="ID")
print(merged)
</code></pre>
      </li>
    </ul>
    
    <h3>6. Data Visualization Basics with Pandas</h3>
    <ul>
      <li><strong>Plotting with the DataFrame.plot() Method</strong>
        <pre><code>df["Age"].plot(kind="bar")
</code></pre>
      </li>
      <li><strong>Customizing Plots (titles, labels)</strong>
        <pre><code>import matplotlib.pyplot as plt
df["Age"].plot(kind="bar", title="Age Distribution")
plt.xlabel("Index")
plt.ylabel("Age")
plt.show()
</code></pre>
      </li>
      <li><strong>Using Histograms and Scatter Plots</strong>
        <p>Examples and code snippets.</p>
      </li>
      <li><strong>Exporting Visualizations</strong>
        <p>Saving your plots to files.</p>
      </li>
    </ul>
    
    <h3>7. Time Series Data Handling</h3>
    <ul>
      <li><strong>Parsing Dates During Data Import</strong>
        <pre><code>df = pd.read_csv("timeseries.csv", parse_dates=["date"])
</code></pre>
      </li>
      <li><strong>Setting the Date Column as Index</strong>
        <pre><code>df.set_index("date", inplace=True)
</code></pre>
      </li>
      <li><strong>Resampling and Aggregating Time Series Data</strong>
        <pre><code>weekly = df.resample("W").mean()
print(weekly)
</code></pre>
      </li>
      <li><strong>Time Shifting and Rolling Windows</strong>
        <p>Examples of time series manipulations.</p>
      </li>
    </ul>
    
    <h3>8. Advanced Data Manipulation Techniques</h3>
    <ul>
      <li><strong>Using lambda and map for Column Operations</strong>
        <pre><code>df["Age_plus_5"] = df["Age"].map(lambda x: x + 5)
print(df)
</code></pre>
      </li>
      <li><strong>MultiIndex DataFrames</strong>
        <p>Creating and manipulating hierarchical indexes.</p>
      </li>
      <li><strong>Stacking and Unstacking Data</strong>
        <p>Examples with code snippets.</p>
      </li>
      <li><strong>Using query() for Advanced Filtering</strong>
        <pre><code>result = df.query("Age > 25")
print(result)
</code></pre>
      </li>
    </ul>
    
    <h3>9. Optimizing Pandas Performance</h3>
    <ul>
      <li><strong>Understanding Vectorized Operations</strong>
        <p>Comparing loops vs. vectorized solutions.</p>
      </li>
      <li><strong>Memory Management Tips</strong>
        <p>Optimizing data types and using chunk processing.</p>
      </li>
      <li><strong>Working with Large Datasets</strong>
        <p>Techniques for handling big data in Pandas.</p>
      </li>
      <li><strong>Profiling and Debugging Pandas Code</strong>
        <p>Tools and strategies for optimization.</p>
      </li>
    </ul>
    
    <h3>10. Review and Practical Pandas Project</h3>
    <ul>
      <li><strong>Mini-Project: Exploratory Data Analysis on a Public Dataset</strong>
        <pre><code>import pandas as pd
import matplotlib.pyplot as plt

# Load dataset
df = pd.read_csv("public_data.csv", parse_dates=["date"])
print(df.head())

# Clean and transform
df.fillna(method="ffill", inplace=True)
df.set_index("date", inplace=True)

# Aggregate and visualize
monthly = df.resample("M").mean()
monthly.plot(title="Monthly Averages")
plt.show()
</code></pre>
      </li>
      <li><strong>Interactive Coding Exercises</strong>
        <p>Practice tasks for data cleaning and aggregation.</p>
      </li>
      <li><strong>Group Discussion: Challenges in Data Analysis</strong>
        <p>Sharing insights and solutions.</p>
      </li>
      <li><strong>Recap and Q&amp;A Session</strong>
        <p>Summarize key points and answer questions.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 8 -->

  <!-- Module 9 -->
  <div class="module" id="module9">
    <h2>Module 9: Data Visualization with Python</h2>
    <p><strong>Introduction:</strong> Module 9 covers techniques to visualize data using Matplotlib and Seaborn. Create charts, graphs, and dashboards to communicate insights effectively.</p>
    
    <h3>1. Introduction to Data Visualization</h3>
    <ul>
      <li><strong>Importance of Data Visualization</strong>
        <p>Overview of why visualization matters in Data Science.</p>
        <pre><code># Visualization helps in understanding data patterns.
</code></pre>
      </li>
      <li><strong>Popular Python Visualization Libraries</strong>
        <p>Matplotlib, Seaborn, Plotly, etc.</p>
      </li>
      <li><strong>Setting Up Your Visualization Environment</strong>
        <pre><code>pip install matplotlib seaborn
</code></pre>
      </li>
      <li><strong>Basic Plotting Concepts and Terminology</strong>
        <p>Introduction to figures, axes, and plots.</p>
      </li>
    </ul>
    
    <h3>2. Getting Started with Matplotlib</h3>
    <ul>
      <li><strong>Basic Line Plot</strong>
        <pre><code>import matplotlib.pyplot as plt
plt.plot([1, 2, 3], [4, 5, 6])
plt.title("Basic Line Plot")
plt.xlabel("X Axis")
plt.ylabel("Y Axis")
plt.show()
</code></pre>
      </li>
      <li><strong>Understanding Figure and Axes</strong>
        <p>Explanation with code snippets.</p>
      </li>
      <li><strong>Customizing Plots (colors, markers, line styles)</strong>
        <pre><code>plt.plot([1, 2, 3], [4, 5, 6], color="red", marker="o", linestyle="--")
plt.show()
</code></pre>
      </li>
      <li><strong>Saving Figures to Files</strong>
        <p>How to export your plots.</p>
      </li>
    </ul>
    
    <h3>3. Creating Bar Charts and Histograms</h3>
    <ul>
      <li><strong>Bar Chart Example</strong>
        <pre><code>plt.bar(["A", "B", "C"], [10, 15, 7])
plt.title("Bar Chart Example")
plt.show()
</code></pre>
      </li>
      <li><strong>Horizontal Bar Charts</strong>
        <pre><code>plt.barh(["A", "B", "C"], [10, 15, 7])
plt.show()
</code></pre>
      </li>
      <li><strong>Histogram for Distribution Analysis</strong>
        <pre><code>import numpy as np
data = np.random.randn(1000)
plt.hist(data, bins=30)
plt.title("Histogram")
plt.show()
</code></pre>
      </li>
      <li><strong>Customizing Axes and Labels</strong>
        <p>Tips to improve plot readability.</p>
      </li>
    </ul>
    
    <h3>4. Scatter Plots and Bubble Charts</h3>
    <ul>
      <li><strong>Basic Scatter Plot</strong>
        <pre><code>import numpy as np
x = np.random.rand(50)
y = np.random.rand(50)
plt.scatter(x, y)
plt.title("Scatter Plot")
plt.show()
</code></pre>
      </li>
      <li><strong>Customizing Marker Size and Color</strong>
        <pre><code>sizes = np.random.randint(10, 200, size=50)
colors = np.random.rand(50)
plt.scatter(x, y, s=sizes, c=colors, cmap="viridis")
plt.colorbar()
plt.show()
</code></pre>
      </li>
      <li><strong>Adding Annotations</strong>
        <p>Example: Annotate a specific point on the plot.</p>
      </li>
      <li><strong>Using Bubble Charts to Represent Additional Data Dimensions</strong>
        <p>Enhance scatter plots with size variations.</p>
      </li>
    </ul>
    
    <h3>5. Working with Seaborn for Advanced Visualizations</h3>
    <ul>
      <li><strong>Introduction to Seaborn</strong>
        <pre><code>import seaborn as sns
</code></pre>
      </li>
      <li><strong>Creating a Simple Seaborn Plot</strong>
        <pre><code>tips = sns.load_dataset("tips")
sns.scatterplot(x="total_bill", y="tip", data=tips)
plt.title("Tips Dataset Scatter Plot")
plt.show()
</code></pre>
      </li>
      <li><strong>Using Seaborn’s Style and Color Palettes</strong>
        <p>Examples of different themes.</p>
      </li>
      <li><strong>Visualizing Categorical Data with Seaborn</strong>
        <p>Techniques for categorical plots.</p>
      </li>
    </ul>
    
    <h3>6. Plotting Time Series Data</h3>
    <ul>
      <li><strong>Line Plot for Time Series Data</strong>
        <pre><code>import pandas as pd
dates = pd.date_range("2023-01-01", periods=100)
values = np.random.randn(100).cumsum()
plt.plot(dates, values)
plt.title("Time Series Plot")
plt.xlabel("Date")
plt.ylabel("Cumulative Value")
plt.show()
</code></pre>
      </li>
      <li><strong>Handling Date Formats in Plots</strong>
        <p>Using matplotlib’s date formatters.</p>
      </li>
      <li><strong>Customizing Tick Labels for Clarity</strong>
        <p>Improve date readability.</p>
      </li>
      <li><strong>Using Pandas Plotting Capabilities</strong>
        <p>Leverage built-in plotting from DataFrames.</p>
      </li>
    </ul>
    
    <h3>7. Subplots and Multi-Plot Figures</h3>
    <ul>
      <li><strong>Creating Multiple Subplots</strong>
        <pre><code>fig, axs = plt.subplots(2, 2, figsize=(10, 8))
axs[0, 0].plot([1, 2, 3], [1, 4, 9])
axs[0, 0].set_title("Plot 1")
axs[0, 1].bar(["A", "B", "C"], [5, 3, 6])
axs[0, 1].set_title("Plot 2")
axs[1, 0].scatter(x, y)
axs[1, 0].set_title("Plot 3")
axs[1, 1].hist(data, bins=30)
axs[1, 1].set_title("Plot 4")
plt.tight_layout()
plt.show()
</code></pre>
      </li>
      <li><strong>Sharing Axes and Colorbars Across Subplots</strong>
        <p>Coordinating plot elements.</p>
      </li>
      <li><strong>Customizing Layouts and Spacing</strong>
        <p>Using <code>plt.tight_layout()</code> and other options.</p>
      </li>
      <li><strong>Exporting Multi-Plot Figures</strong>
        <p>Saving combined plots.</p>
      </li>
    </ul>
    
    <h3>8. Interactive Visualizations</h3>
    <ul>
      <li><strong>Introduction to Plotly</strong>
        <p>Overview and installation.</p>
        <pre><code>pip install plotly
</code></pre>
      </li>
      <li><strong>Creating a Simple Interactive Plot with Plotly</strong>
        <pre><code>import plotly.express as px
df = px.data.iris()
fig = px.scatter(df, x="sepal_width", y="sepal_length", color="species")
fig.show()
</code></pre>
      </li>
      <li><strong>Interactivity Features (hover, zoom, select)</strong>
        <p>Discussion on interactive options.</p>
      </li>
      <li><strong>Embedding Interactive Plots in Web Pages</strong>
        <p>How to integrate Plotly charts.</p>
      </li>
    </ul>
    
    <h3>9. Best Practices in Data Visualization</h3>
    <ul>
      <li><strong>Choosing the Right Chart for Your Data</strong>
        <p>Guidelines and examples.</p>
      </li>
      <li><strong>Ensuring Readability and Clarity</strong>
        <p>Focus on fonts, labels, and colors.</p>
      </li>
      <li><strong>Avoiding Misleading Visualizations</strong>
        <p>Tips and common pitfalls.</p>
      </li>
      <li><strong>Documenting Your Visualizations for Reproducibility</strong>
        <p>How to keep track of your plots and settings.</p>
      </li>
    </ul>
    
    <h3>10. Review and Visualizations Project</h3>
    <ul>
      <li><strong>Mini-Project: Create a Dashboard of Visualizations</strong>
        <pre><code>import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
df = sns.load_dataset("tips")

# Create subplots
fig, axs = plt.subplots(2, 2, figsize=(12, 10))

# Scatter plot
sns.scatterplot(x="total_bill", y="tip", data=df, ax=axs[0, 0])
axs[0, 0].set_title("Total Bill vs Tip")

# Histogram
sns.histplot(df["total_bill"], bins=20, ax=axs[0, 1])
axs[0, 1].set_title("Total Bill Distribution")

# Box plot
sns.boxplot(x="day", y="total_bill", data=df, ax=axs[1, 0])
axs[1, 0].set_title("Total Bill by Day")

# Bar chart
sns.barplot(x="day", y="tip", data=df, ax=axs[1, 1])
axs[1, 1].set_title("Average Tip by Day")

plt.tight_layout()
plt.show()
</code></pre>
      </li>
      <li><strong>Hands-On Exercises with Different Datasets</strong>
        <p>Practice with various data sources.</p>
      </li>
      <li><strong>Group Discussion: Effective Visualizations</strong>
        <p>Share and critique visualization designs.</p>
      </li>
      <li><strong>Final Q&amp;A Session on Visualization Techniques</strong>
        <p>Answer remaining questions.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 9 -->

  <!-- Module 10 -->
  <div class="module" id="module10">
    <h2>Module 10: Introduction to Machine Learning Concepts</h2>
    <p><strong>Introduction:</strong> This module introduces basic machine learning concepts and terminology. Learn about supervised and unsupervised learning, model training, evaluation metrics, and more to build the foundation for future AI projects.</p>
    
    <h3>1. Overview of Machine Learning</h3>
    <ul>
      <li><strong>What is Machine Learning?</strong>
        <p>Definition and examples.</p>
        <pre><code># Machine learning is about making predictions based on data.
</code></pre>
      </li>
      <li><strong>Types of Machine Learning</strong>
        <p>Supervised, Unsupervised, and Reinforcement Learning.</p>
      </li>
      <li><strong>Real-World Applications</strong>
        <p>Examples from various industries.</p>
      </li>
      <li><strong>Machine Learning Workflow Overview</strong>
        <p>Steps from data collection to deployment.</p>
      </li>
    </ul>
    
    <h3>2. Understanding Data and Feature Engineering</h3>
    <ul>
      <li><strong>Role of Data in Machine Learning</strong>
        <p>The importance of quality data.</p>
      </li>
      <li><strong>Feature Extraction and Selection</strong>
        <p>Examples and techniques.</p>
      </li>
      <li><strong>Data Preprocessing Steps</strong>
        <p>Cleaning, scaling, and encoding data.</p>
      </li>
      <li><strong>Using Pandas for Feature Engineering</strong>
        <p>Practical examples using Pandas.</p>
      </li>
    </ul>
    
    <h3>3. Supervised Learning Fundamentals</h3>
    <ul>
      <li><strong>Definition and Examples</strong>
        <p>Regression and classification tasks.</p>
      </li>
      <li><strong>Understanding Training and Testing Data</strong>
        <p>Splitting data into training and test sets.</p>
      </li>
      <li><strong>Simple Linear Regression Example</strong>
        <pre><code>import numpy as np
from sklearn.linear_model import LinearRegression
X = np.array([[1], [2], [3]])
y = np.array([2, 4, 6])
model = LinearRegression().fit(X, y)
print(model.predict([[4]]))
</code></pre>
      </li>
      <li><strong>Evaluating Model Performance (RMSE, R²)</strong>
        <p>Introduction to evaluation metrics.</p>
      </li>
    </ul>
    
    <h3>4. Unsupervised Learning Fundamentals</h3>
    <ul>
      <li><strong>Definition and Examples</strong>
        <p>Clustering and dimensionality reduction.</p>
      </li>
      <li><strong>K-Means Clustering Example</strong>
        <pre><code>from sklearn.cluster import KMeans
data = np.array([[1, 2], [1, 4], [1, 0],
                 [4, 2], [4, 4], [4, 0]])
kmeans = KMeans(n_clusters=2).fit(data)
print(kmeans.labels_)
</code></pre>
      </li>
      <li><strong>Exploring Data Structure without Labels</strong>
        <p>How to discover patterns in data.</p>
      </li>
      <li><strong>Using PCA for Dimensionality Reduction</strong>
        <p>Introduction to Principal Component Analysis.</p>
      </li>
    </ul>
    
    <h3>5. Model Training and Evaluation</h3>
    <ul>
      <li><strong>Splitting Data into Training and Test Sets</strong>
        <pre><code>from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
</code></pre>
      </li>
      <li><strong>Training a Model</strong>
        <p>Example: training a regression model.</p>
      </li>
      <li><strong>Evaluating with Metrics</strong>
        <p>Accuracy, precision, recall, and more.</p>
      </li>
      <li><strong>Cross-Validation Techniques</strong>
        <p>Improve your model’s generalizability.</p>
      </li>
    </ul>
    
    <h3>6. Introduction to Classification Tasks</h3>
    <ul>
      <li><strong>Binary vs. Multi-class Classification</strong>
        <p>Different types of classification problems.</p>
      </li>
      <li><strong>Example: Logistic Regression</strong>
        <pre><code>from sklearn.linear_model import LogisticRegression
X = np.array([[1], [2], [3], [4]])
y = np.array([0, 0, 1, 1])
model = LogisticRegression().fit(X, y)
print(model.predict([[2.5]]))
</code></pre>
      </li>
      <li><strong>Confusion Matrix and ROC Curve</strong>
        <p>Visualizing classification performance.</p>
      </li>
      <li><strong>Practical Considerations in Classification</strong>
        <p>Challenges and common pitfalls.</p>
      </li>
    </ul>
    
    <h3>7. Overfitting, Underfitting, and Model Tuning</h3>
    <ul>
      <li><strong>Understanding Overfitting vs. Underfitting</strong>
        <p>Visual examples and discussion.</p>
      </li>
      <li><strong>Regularization Techniques (L1, L2)</strong>
        <p>Preventing over-complex models.</p>
      </li>
      <li><strong>Hyperparameter Tuning (Grid Search, Random Search)</strong>
        <p>Finding the best model settings.</p>
      </li>
      <li><strong>Validation Curves and Learning Curves</strong>
        <p>Visualizing model performance trends.</p>
      </li>
    </ul>
    
    <h3>8. Introduction to Evaluation Metrics</h3>
    <ul>
      <li><strong>Regression Metrics: MSE, MAE, R²</strong>
        <pre><code>from sklearn.metrics import mean_squared_error
mse = mean_squared_error(y_test, model.predict(X_test))
print(mse)
</code></pre>
      </li>
      <li><strong>Classification Metrics: Accuracy, F1-Score</strong>
        <p>Understanding classification performance.</p>
      </li>
      <li><strong>Confusion Matrix Visualization</strong>
        <p>How to interpret a confusion matrix.</p>
      </li>
      <li><strong>Interpreting Metric Results</strong>
        <p>Discussion on how to choose metrics.</p>
      </li>
    </ul>
    
    <h3>9. Introduction to Model Deployment Concepts</h3>
    <ul>
      <li><strong>From Training to Production</strong>
        <p>Concepts on deploying machine learning models.</p>
      </li>
      <li><strong>Saving and Loading Models</strong>
        <pre><code>import joblib
joblib.dump(model, "model.pkl")
model_loaded = joblib.load("model.pkl")
</code></pre>
      </li>
      <li><strong>Using Models in Real-Time Applications</strong>
        <p>Integration into production systems.</p>
      </li>
      <li><strong>Challenges and Best Practices in Deployment</strong>
        <p>Considerations for production environments.</p>
      </li>
    </ul>
    
    <h3>10. Review and Mini Machine Learning Project</h3>
    <ul>
      <li><strong>Mini-Project: Build a Simple Model</strong>
        <pre><code>import pandas as pd
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LinearRegression
from sklearn.metrics import mean_squared_error

# Sample dataset
data = {'size': [750, 800, 850, 900, 950],
        'price': [150000, 160000, 165000, 170000, 175000]}
df = pd.DataFrame(data)

X = df[['size']]
y = df['price']

X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2)
model = LinearRegression().fit(X_train, y_train)
predictions = model.predict(X_test)
print("MSE:", mean_squared_error(y_test, predictions))
</code></pre>
      </li>
      <li><strong>Group Discussion on Model Results</strong>
        <p>Review performance and insights.</p>
      </li>
      <li><strong>Interactive Q&amp;A Session</strong>
        <p>Answer questions and clarify doubts.</p>
      </li>
      <li><strong>Recap of Key Machine Learning Concepts</strong>
        <p>Summarize the main points.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 10 -->

  <!-- Module 11 -->
  <div class="module" id="module11">
    <h2>Module 11: Working with the OpenAI API</h2>
    <p><strong>Introduction:</strong> In Module 11, learn how to integrate AI-powered services using the OpenAI API. This module covers account setup, making API calls, and incorporating advanced language models into your projects.</p>
    
    <h3>1. Introduction to OpenAI API</h3>
    <ul>
      <li><strong>What is the OpenAI API?</strong>
        <p>Overview and real-world applications.</p>
        <pre><code># The OpenAI API provides access to advanced language models.
</code></pre>
      </li>
      <li><strong>Use Cases in Data Science and AI Applications</strong>
        <p>Examples of how the API is used.</p>
      </li>
      <li><strong>Getting Started: Documentation and Resources</strong>
        <p>Where to find help and examples.</p>
      </li>
      <li><strong>Understanding API Terms and Limitations</strong>
        <p>Important notes on usage and quotas.</p>
      </li>
    </ul>
    
    <h3>2. Setting Up Your OpenAI Account</h3>
    <ul>
      <li><strong>Signing Up and Creating an Account</strong>
        <p>Step-by-step guide (with screenshots if available).</p>
      </li>
      <li><strong>Generating and Securing Your API Key</strong>
        <p>How to get and store your API key securely.</p>
      </li>
      <li><strong>Understanding API Pricing and Limits</strong>
        <p>Overview of costs and usage limits.</p>
      </li>
      <li><strong>Configuring Environment Variables for Security</strong>
        <pre><code># In your terminal:
export OPENAI_API_KEY="your_api_key_here"
</code></pre>
      </li>
    </ul>
    
    <h3>3. Making Your First API Call</h3>
    <ul>
      <li><strong>Installing the OpenAI Python Library</strong>
        <pre><code>pip install openai
</code></pre>
      </li>
      <li><strong>Basic API Call Example</strong>
        <pre><code>import openai
openai.api_key = "your_api_key_here"

response = openai.Completion.create(
    engine="text-davinci-003",
    prompt="Translate 'Hello, world!' into French.",
    max_tokens=60
)
print(response.choices[0].text.strip())
</code></pre>
      </li>
      <li><strong>Understanding Request Parameters</strong>
        <p>Explanation of parameters like <code>max_tokens</code> and <code>prompt</code>.</p>
      </li>
      <li><strong>Handling API Responses and Errors</strong>
        <p>Strategies for parsing JSON responses and managing errors.</p>
      </li>
    </ul>
    
    <h3>4. Customizing API Requests</h3>
    <ul>
      <li><strong>Modifying Prompts for Different Tasks</strong>
        <p>Examples: summarization, translation, question answering.</p>
      </li>
      <li><strong>Tuning Parameters (max_tokens, temperature, top_p)</strong>
        <pre><code>response = openai.Completion.create(
    engine="text-davinci-003",
    prompt="Summarize the following text: ...",
    temperature=0.5,
    max_tokens=100
)
</code></pre>
      </li>
      <li><strong>Iterative Prompt Engineering</strong>
        <p>Techniques to refine your prompts for better results.</p>
      </li>
      <li><strong>Using Stop Sequences to Control Output</strong>
        <p>How to signal the API to stop generating text.</p>
      </li>
    </ul>
    
    <h3>5. Integrating the OpenAI API into Applications</h3>
    <ul>
      <li><strong>Building a Command-Line Interface (CLI) Tool</strong>
        <pre><code>def ask_openai(question):
    response = openai.Completion.create(
        engine="text-davinci-003",
        prompt=question,
        max_tokens=60
    )
    return response.choices[0].text.strip()

user_question = input("Ask a question: ")
print(ask_openai(user_question))
</code></pre>
      </li>
      <li><strong>Developing a Simple Web App Prototype</strong>
        <p>Conceptual overview using Flask (if desired).</p>
      </li>
      <li><strong>Error Handling and Retries in API Calls</strong>
        <p>Strategies for robust integration.</p>
      </li>
      <li><strong>Logging and Monitoring API Usage</strong>
        <p>Keeping track of your API calls.</p>
      </li>
    </ul>
    
    <h3>6. Advanced API Usage and Fine-Tuning</h3>
    <ul>
      <li><strong>Exploring Additional Endpoints (edits, embeddings)</strong>
        <p>Overview of other API functionalities.</p>
      </li>
      <li><strong>Understanding Model Fine-Tuning Concepts</strong>
        <p>How to tailor models to your data.</p>
      </li>
      <li><strong>Case Study: Building a Chatbot with the OpenAI API</strong>
        <p>Real-world application example.</p>
      </li>
      <li><strong>Best Practices for API Integration</strong>
        <p>General guidelines for secure and efficient integration.</p>
      </li>
    </ul>
    
    <h3>7. Security and Rate Limiting Considerations</h3>
    <ul>
      <li><strong>Securing Your API Key</strong>
        <p>Never hard-code your API key; use environment variables.</p>
      </li>
      <li><strong>Handling Rate Limits and Quota Exceedance</strong>
        <p>Strategies to manage rate limiting.</p>
      </li>
      <li><strong>Implementing Caching Strategies for Frequent Calls</strong>
        <p>How caching can reduce API load.</p>
      </li>
      <li><strong>Monitoring API Usage and Costs</strong>
        <p>Tools to track your spending.</p>
      </li>
    </ul>
    
    <h3>8. Practical Exercises with OpenAI API</h3>
    <ul>
      <li><strong>Task: Build a Text Summarizer</strong>
        <pre><code>def summarize_text(text):
    response = openai.Completion.create(
        engine="text-davinci-003",
        prompt=f"Summarize this: {text}",
        max_tokens=80
    )
    return response.choices[0].text.strip()

sample_text = "Your long text goes here..."
print(summarize_text(sample_text))
</code></pre>
      </li>
      <li><strong>Task: Create a Translation Tool</strong>
        <p>Develop a function to translate text using the API.</p>
      </li>
      <li><strong>Task: Implement a Question Answering Function</strong>
        <p>Use the API to build a Q&amp;A tool.</p>
      </li>
      <li><strong>Group Work: Sharing API Use Cases</strong>
        <p>Discuss and compare different applications.</p>
      </li>
    </ul>
    
    <h3>9. Troubleshooting and Debugging API Calls</h3>
    <ul>
      <li><strong>Common API Error Codes and Their Meanings</strong>
        <p>Overview of typical errors.</p>
      </li>
      <li><strong>Techniques for Debugging API Requests</strong>
        <p>Methods to isolate and fix issues.</p>
      </li>
      <li><strong>Logging and Reporting Issues</strong>
        <p>Best practices for debugging.</p>
      </li>
      <li><strong>Using API Documentation for Problem Solving</strong>
        <p>How to leverage the docs when stuck.</p>
      </li>
    </ul>
    
    <h3>10. Review and API Integration Project</h3>
    <ul>
      <li><strong>Mini-Project: Develop an AI Assistant App</strong>
        <pre><code>import openai
openai.api_key = "your_api_key_here"

def ai_assistant(prompt):
    response = openai.Completion.create(
        engine="text-davinci-003",
        prompt=prompt,
        temperature=0.7,
        max_tokens=100
    )
    return response.choices[0].text.strip()

while True:
    user_input = input("You: ")
    if user_input.lower() in ["exit", "quit"]:
        break
    print("AI:", ai_assistant(user_input))
</code></pre>
      </li>
      <li><strong>Hands-On Debugging Sessions</strong>
        <p>Practice resolving common API issues.</p>
      </li>
      <li><strong>Peer Review of API Integration Code</strong>
        <p>Share your projects and learn from others.</p>
      </li>
      <li><strong>Recap and Q&amp;A on API Usage</strong>
        <p>Discuss final questions and best practices.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 11 -->

  <!-- Module 12 -->
  <div class="module" id="module12">
    <h2>Module 12: Creating End-to-End AI Solutions with DeepSeek AI &amp; Integration</h2>
    <p><strong>Introduction:</strong> In the final module, integrate all the skills learned to create complete AI-powered Data Science solutions. Learn to combine data manipulation, machine learning, and AI APIs (including DeepSeek AI) into cohesive projects.</p>
    
    <h3>1. Overview of End-to-End AI Solutions</h3>
    <ul>
      <li><strong>Defining End-to-End Workflows</strong>
        <p>From data ingestion to model deployment and UI integration.</p>
        <pre><code># End-to-end projects combine data processing, modeling, and presentation.
</code></pre>
      </li>
      <li><strong>Components of an AI Solution</strong>
        <p>Overview of data pipelines, models, and interfaces.</p>
      </li>
      <li><strong>Real-World Examples and Case Studies</strong>
        <p>Examples of complete AI projects.</p>
      </li>
      <li><strong>Planning Your Project</strong>
        <p>Strategies for successful project design.</p>
      </li>
    </ul>
    
    <h3>2. Introduction to DeepSeek AI</h3>
    <ul>
      <li><strong>What is DeepSeek AI?</strong>
        <p>Overview of its capabilities for data search and analysis.</p>
      </li>
      <li><strong>Setting Up and Accessing DeepSeek AI</strong>
        <p>Steps to register and access the API.</p>
      </li>
      <li><strong>Key Features and Use Cases</strong>
        <p>Examples of what DeepSeek AI can do.</p>
      </li>
      <li><strong>Integration Options with Python</strong>
        <p>How to incorporate DeepSeek AI into your workflow.</p>
      </li>
    </ul>
    
    <h3>3. Integrating Data Science Workflows</h3>
    <ul>
      <li><strong>Combining NumPy, Pandas, and Visualization</strong>
        <p>Review and consolidate your data manipulation skills.</p>
      </li>
      <li><strong>Using Machine Learning Models in Your Pipeline</strong>
        <p>Integrate trained models into your projects.</p>
      </li>
      <li><strong>Case Study: Analyzing a Public Dataset End-to-End</strong>
        <p>Walkthrough of a complete data analysis project.</p>
      </li>
      <li><strong>Code Integration Examples</strong>
        <p>Sample code showing how to stitch components together.</p>
      </li>
    </ul>
    
    <h3>4. Building a Data Ingestion and Preprocessing Pipeline</h3>
    <ul>
      <li><strong>Automating Data Loading and Cleaning</strong>
        <pre><code>def load_and_clean_data(file_path):
    df = pd.read_csv(file_path)
    df.fillna(method="ffill", inplace=True)
    return df

data = load_and_clean_data("data.csv")
print(data.head())
</code></pre>
      </li>
      <li><strong>Handling Data from Multiple Sources</strong>
        <p>Techniques for combining data from different formats.</p>
      </li>
      <li><strong>Scheduling Data Updates and Pipeline Automation</strong>
        <p>Automate data ingestion tasks.</p>
      </li>
      <li><strong>Error Handling in Data Pipelines</strong>
        <p>Strategies for robust data processing.</p>
      </li>
    </ul>
    
    <h3>5. Deploying Machine Learning Models in Production</h3>
    <ul>
      <li><strong>Model Serialization and Saving</strong>
        <pre><code>import joblib
joblib.dump(model, "model.pkl")
</code></pre>
      </li>
      <li><strong>Creating a Prediction API with Flask or FastAPI</strong>
        <pre><code>from flask import Flask, request, jsonify
import joblib

app = Flask(__name__)
model = joblib.load("model.pkl")

@app.route("/predict", methods=["POST"])
def predict():
    data = request.json
    prediction = model.predict([data["features"]])
    return jsonify({"prediction": prediction.tolist()})

if __name__ == "__main__":
    app.run(debug=True)
</code></pre>
      </li>
      <li><strong>Integrating with Cloud Services</strong>
        <p>Overview of deploying models to cloud platforms.</p>
      </li>
      <li><strong>Monitoring and Updating Models</strong>
        <p>Best practices for maintaining production systems.</p>
      </li>
    </ul>
    
    <h3>6. Integrating DeepSeek AI for Enhanced Search</h3>
    <ul>
      <li><strong>Using DeepSeek AI APIs for Data Insights</strong>
        <p>How to query data using DeepSeek AI.</p>
      </li>
      <li><strong>Building a Search Interface for Your Data</strong>
        <p>Example code to integrate search functionality.</p>
      </li>
      <li><strong>Combining Search with Visualization</strong>
        <p>Enhance dashboards with search capabilities.</p>
      </li>
      <li><strong>Case Study: AI-Powered Dashboard with Search Capabilities</strong>
        <p>Review a real-world example.</p>
      </li>
    </ul>
    
    <h3>7. Creating a User Interface for Your AI Solution</h3>
    <ul>
      <li><strong>Overview of UI Options (Web, Desktop, CLI)</strong>
        <p>Different approaches to build a user interface.</p>
      </li>
      <li><strong>Developing a Simple Web Dashboard</strong>
        <pre><code>import streamlit as st
import pandas as pd

st.title("AI Dashboard")
df = pd.read_csv("data.csv")
st.dataframe(df)
</code></pre>
      </li>
      <li><strong>Integrating Visualizations into the UI</strong>
        <p>How to embed charts and graphs.</p>
      </li>
      <li><strong>User Feedback and Iteration</strong>
        <p>Improving your UI based on user input.</p>
      </li>
    </ul>
    
    <h3>8. Testing and Validating the End-to-End System</h3>
    <ul>
      <li><strong>Unit Testing for Data Pipelines and Models</strong>
        <pre><code>def test_data_loading():
    df = load_and_clean_data("data.csv")
    assert not df.empty
test_data_loading()
</code></pre>
      </li>
      <li><strong>Integration Testing Across Components</strong>
        <p>Ensuring all parts work together.</p>
      </li>
      <li><strong>User Acceptance Testing (UAT)</strong>
        <p>Gathering feedback from real users.</p>
      </li>
      <li><strong>Debugging and Performance Optimization</strong>
        <p>Troubleshooting and tuning the system.</p>
      </li>
    </ul>
    
    <h3>9. Deploying Your AI Solution to Production</h3>
    <ul>
      <li><strong>Deployment Options (Local Servers, Cloud Platforms)</strong>
        <p>Overview of various deployment strategies.</p>
      </li>
      <li><strong>Setting Up CI/CD Pipelines for Updates</strong>
        <p>Automate deployment and testing.</p>
      </li>
      <li><strong>Monitoring and Logging in Production</strong>
        <p>Keep track of system performance and issues.</p>
      </li>
      <li><strong>Best Practices for Maintenance</strong>
        <p>Ensuring long-term reliability.</p>
      </li>
    </ul>
    
    <h3>10. Final Project Review &amp; Future Steps</h3>
    <ul>
      <li><strong>Capstone Project: Develop an End-to-End AI Solution</strong>
        <pre><code># Pseudocode outline:
# 1. Load and clean data
data = load_and_clean_data("data.csv")
# 2. Make predictions using a pre-trained model
prediction = model.predict(data_features)
# 3. Integrate DeepSeek AI search functionality
search_results = deepseek_search("query")
# 4. Display results in a web dashboard
import streamlit as st
st.title("Capstone AI Solution")
st.write("Predictions:", prediction)
st.write("Search Results:", search_results)
</code></pre>
      </li>
      <li><strong>Peer Presentations and Code Reviews</strong>
        <p>Share and discuss your projects with classmates.</p>
      </li>
      <li><strong>Feedback and Iterative Improvements</strong>
        <p>Use feedback to refine your solution.</p>
      </li>
      <li><strong>Next Steps in Your Data Science Journey</strong>
        <p>Suggestions for further learning and projects.</p>
      </li>
    </ul>
  </div>
  <!-- End Module 12 -->

  <p><strong>Final Note:</strong> This 12‑module guide has been structured to provide a smooth and progressive learning experience for complete beginners. Each module builds on previous lessons with detailed subtopics and code examples. Feel free to adapt, expand, or modify these modules to best suit your class needs.</p>

  <p>Happy Learning and Coding!</p>
</body>
</html>
