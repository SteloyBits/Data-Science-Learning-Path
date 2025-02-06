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