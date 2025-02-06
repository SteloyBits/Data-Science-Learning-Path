<h2>Module 6: Python Standard Libraries &amp; Modules</h2>
    <p><strong>Introduction:</strong> Learn how to use Python’s built-in libraries and modules to extend your code’s capabilities. This module covers topics like file handling, OS interaction, and creating your own modules.</p>
    
<h3>1. Understanding Python Modules and Packages</h3>
    <ul>
      <li><strong>What Are Modules and Packages?</strong>
        <p>Definition and examples.</p>
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
