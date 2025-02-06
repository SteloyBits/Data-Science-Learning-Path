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
