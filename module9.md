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