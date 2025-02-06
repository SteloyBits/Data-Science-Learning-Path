<h1>Data Science Learning Path for Beginners</h1>
  <p>This comprehensive 12‑module guide is designed for students with little or no technical background. It starts with basic computer and programming skills and builds up to advanced AI integrations, including use of the OpenAI API and DeepSeek AI. Each module is organized into 10 detailed topics with multiple subtopics and code examples.</p>

  <!-- Module 1 -->
  <div class="module" id="module1">
    <h2>Module 1: Getting Started with Computers &amp; Python</h2>
    <p><strong>Introduction:</strong> In Module 1, we introduce basic computer concepts, how to install Python, and run your first Python program. This module is ideal even if you have only just begun using a computer.</p>
    
  <h3> 1. Understanding Computers and Operating Systems</h3>
    <ul>
      <li><strong>What is a Computer?</strong>
        <p>Explanation of hardware and software concepts.</p>
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
</body>
</html>
