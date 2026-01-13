# Data Science & Analytics Internship Tasks

## **Task 1: Exploring and Visualizing the Iris Dataset**

### **Objective**
The objective of this task is to understand how to read, summarize, and visualize a simple dataset using Python. The Iris dataset is used to perform basic data inspection and Exploratory Data Analysis (EDA) in order to identify patterns and relationships between features.

### **Dataset**
The dataset used in this task is the **Iris Dataset**, which contains measurements of iris flowers for three different species.

**Dataset Details:**
- Number of Samples: 150
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target Variable:
  - Species (Setosa, Versicolor, Virginica)

**Dataset Source:**
- Seaborn built-in dataset  
- CSV available from the UCI Machine Learning Repository  

### **Libraries Used**
- Python  
- Pandas  
- Matplotlib  
- Seaborn  

### **Task Workflow**

#### **1. Data Loading**
- The Iris dataset is loaded using the Pandas library.
- The dataset is stored in a Pandas DataFrame for analysis.

#### **2. Data Inspection**
- `.shape` is used to check the number of rows and columns.
- `.columns` is used to view feature names.
- `.head()` is used to display the first few rows of the dataset.

#### **3. Data Summarization**
- `.describe()` is used to generate basic statistical information.
- This helps in understanding the distribution and range of numerical features.

#### **4. Data Visualization**
The following visualizations are created using Matplotlib and Seaborn:

- **Scatter Plots**  
  Used to analyze relationships between different features.

- **Histograms**  
  Used to examine the distribution of numerical variables.

- **Box Plots**  
  Used to identify outliers and understand data spread.

- **Pair Plots**  
  Used to visualize relationships between all features and species.

### **Key Insights**
- Petal length and petal width are strong indicators for species classification.
- The Setosa species is clearly separable from the other two species.
- Versicolor and Virginica show some overlap in their feature values.

### **Files Included**
- `Task1_Iris_EDA.ipynb`


