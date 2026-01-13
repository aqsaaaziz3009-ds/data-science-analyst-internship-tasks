Task 1: Exploring and Visualizing the Iris Dataset
📌 Objective

The objective of this task is to understand how to read, summarize, and visualize a simple dataset using Python. The Iris dataset is used to perform basic data inspection and Exploratory Data Analysis (EDA) in order to gain insights into feature distributions and relationships between variables.

📊 Dataset

The dataset used for this task is the Iris Dataset, which contains measurements of iris flowers. The features include sepal length, sepal width, petal length, and petal width for three different species of iris flowers.

Dataset Source:

Seaborn built-in dataset

CSV file available from the UCI Machine Learning Repository

🛠️ Libraries Used

Python

Pandas

Matplotlib

Seaborn

🔍 Task Workflow
1. Data Loading

The dataset is loaded using the Pandas library.

The CSV file (or built-in Seaborn dataset) is read into a Pandas DataFrame for further analysis.

2. Data Inspection

The structure of the dataset is explored using the following functions:

.shape to identify the number of rows and columns

.columns to view the names of the features

.head() to display the first few rows of the dataset

3. Data Summarization

Basic statistical information is obtained using .describe().

This helps in understanding the range, mean, and distribution of the numerical features.

4. Data Visualization

The following visualizations are created using Matplotlib and Seaborn:

Scatter Plots:
Used to analyze relationships between different features (e.g., sepal length vs sepal width).

Histograms:
Used to examine the distribution of numerical features and identify data spread or skewness.

Box Plots:
Used to detect outliers and understand the spread of values through medians and quartiles.

5. Results and Observations

The visualizations provide clear insights into feature relationships and distributions.

Certain features show distinct patterns that help differentiate between iris species.

Overall, the dataset is well-structured and suitable for basic exploratory analysis.

📁 Files Included

Task1_Iris_EDA.ipynb

