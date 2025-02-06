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
