<h2>Module 1: Getting Started with Computers &amp; Python</h2>
    <p><strong>Introduction:</strong> In Module 1, we introduce basic computer concepts, how to install Python, and run your first Python program. This module is ideal even if you have only just begun using a computer.</p>
    
<h3>1. Understanding Computers and Operating Systems</h3>
    <ul>
      <li><strong>What is a Computer?</strong>
        <p>Explanation of hardware and software concepts.</p>
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
      <li><strong>Downloading Python from the Official Website [Goto: https://www.python.org/downloads] </strong>
        <p>Step-by-step guide for installation.</p>
      </li>
      <li><strong>Verifying Your Python Installation</strong>
        <pre><code>python --version
</code></pre>
      </li>
      <li><strong>Installing a Code Editor (VSCode)</strong>
        <p>Download and basic configuration.</p>
      </li>
      <li><strong>Setting Up Virtual Environments</strong>
        <p>Creating an isolated environment for your projects.</p>
        <pre><code>python -m venv myenv
myenv\Scripts\activate    # On Linux/Mac: source myenv/bin/activate  
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
