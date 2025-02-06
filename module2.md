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
