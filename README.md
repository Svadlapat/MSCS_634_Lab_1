# MSCS_634_Lab_1

Data Visualization, Data Preprocessing and Statistical Analysis

Name: Sai sarath

Course: Advanced Big Data and Data Mining
Lab Assignment: Lab 1 – Data Visualization, Preprocessing and Statistical Analysis

# Overview

The objective of this lab is to explore and analyze a dataset using Python and Jupyter Notebook. The lab focuses on applying fundamental data mining and data analysis techniques including data visualization, preprocessing, and statistical analysis.

Using the Python libraries Pandas, NumPy, Matplotlib, and Seaborn, the dataset was explored to understand its structure, identify patterns, detect potential outliers, and prepare the data for further analysis.

# Dataset
The dataset used in this lab is a Superstore Sales dataset, which contains information about customer orders, shipping details, product categories, and sales transactions.

Key Features in the Dataset:
Row ID
Order ID
Order Date
Ship Date
Ship Mode
Customer ID
Customer Name
Segment
Country
City
State
Postal Code
Region
Product ID
Category
Sub-Category
Product Name
Sales

# Tools and Technologies Used

Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Seaborn
GitHub Codespaces

These tools were used for data manipulation, visualization, and statistical analysis.

# Data Visualization

Several visualizations were created to better understand patterns and relationships within the dataset.

Scatter Plot:
A scatter plot was created to analyze the relationship between Postal Code and Sales. This visualization helps identify how sales vary across different geographical areas.

Bar Chart:
A bar chart was generated to show total sales by product category. This visualization helps compare the performance of different product categories.

Histogram:
A histogram was used to visualize the distribution of sales values. This provides insight into how frequently different sales amounts occur.

Box Plot:
A box plot was created to detect outliers in sales values. It highlights extreme sales transactions and the spread of the data.

Pie Chart:
A pie chart was used to represent the distribution of customer segments, showing the proportion of Consumer, Corporate, and Home Office customers.

# Data Preprocessing

Before performing analysis, several preprocessing techniques were applied.

Handling Missing Values:
The dataset was checked for missing values using Pandas functions. Missing values were identified and handled appropriately to ensure data quality.

Outlier Detection:
The Interquartile Range (IQR) method was used to identify outliers in the Sales column. This technique helps detect unusually high or low values that may affect analysis.

Data Reduction:
Irrelevant or unnecessary columns such as Row ID, Customer Name, and Product Name were removed to simplify the dataset and focus on relevant attributes.

Data Scaling:
Min-Max Scaling was applied to normalize the Sales values. Scaling helps ensure that numerical values fall within a consistent range and improves analytical consistency.

# Statistical Analysis

Several statistical techniques were applied to understand the dataset.

1.Dataset Overview:

The dataset structure was examined using:
df.info() to view data types and structure
df.describe() to summarize numerical statistics

2.Measures of Central Tendency:

The following metrics were calculated for the Sales column:
Mean
Median
Mode
Minimum
Maximum

These metrics help understand the central behavior of the data.

3.Measures of Dispersion

To measure variability in the data, the following metrics were calculated:
Range
Variance
Standard Deviation
Interquartile Range (IQR)

These statistics provide insight into how spread out the sales values are.

2.Correlation Analysis

Correlation analysis was performed to understand relationships between numerical attributes such as Sales and Postal Code.

# Key Insights

Sales transactions vary significantly across different regions and postal codes.
The Consumer segment represents the largest portion of customers.
Some sales transactions appear as outliers, indicating unusually large purchases.
Sales values are positively skewed, meaning most transactions have smaller values while a few have very large sales amounts.

# Conclusion
This lab provided practical experience with data analysis techniques using Python. Through visualization, preprocessing, and statistical analysis, the dataset was explored to uncover patterns and insights.
The techniques learned in this lab form an essential foundation for more advanced data mining and machine learning tasks.
