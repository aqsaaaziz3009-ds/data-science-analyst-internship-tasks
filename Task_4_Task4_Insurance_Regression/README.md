## **Task 4: Predicting Insurance Claim Amounts**

### **Objective**
The objective of this task is to predict medical insurance claim amounts based on personal and health-related attributes using a regression model.

---

### **Dataset**
The dataset used for this task is the **Medical Cost Personal Dataset**.

**Dataset Details:**
- Features include age, BMI, smoking status, number of children, and region.
- Target Variable:
  - Charges (Medical Insurance Cost)

---

### **Libraries Used**
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

### **Task Workflow**

#### **1. Data Loading and Cleaning**
- Dataset is loaded and checked for missing values.
- Categorical features are converted into numeric format.

#### **2. Exploratory Data Analysis**
- Visualized relationships between age, BMI, smoking status, and insurance charges.

#### **3. Model Training**
- A Linear Regression model is trained to predict insurance costs.

#### **4. Model Evaluation**
- Model performance is evaluated using MAE and RMSE.

---

### **Key Insights**
- Smoking status has a strong impact on insurance charges.
- Higher BMI and age are associated with higher medical costs.

---

### **Files Included**
- `Task4_Insurance_Regression.ipynb`
