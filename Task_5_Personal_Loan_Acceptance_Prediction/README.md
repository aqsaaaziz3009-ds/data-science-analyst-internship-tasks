## **Task 5: Personal Loan Acceptance Prediction**

### **Objective**
The objective of this task is to predict whether a bank customer will accept a personal loan offer based on their demographic and financial information.

---

### **Dataset**
The dataset used for this task is the **Bank Marketing Dataset** from the UCI Machine Learning Repository.

**Dataset Details:**
- Features include age, job, marital status, education, balance, and campaign details.
- Target Variable:
  - Loan Acceptance (Yes / No)

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

#### **1. Data Preparation**
- Dataset is loaded and unnecessary features are removed.
- Categorical variables are encoded using one-hot encoding.
- Feature scaling is applied to improve model performance.

#### **2. Model Training**
- Logistic Regression is used to build the classification model.

#### **3. Model Evaluation**
- Model accuracy is calculated.
- Confusion matrix is used to analyze predictions.

---

### **Key Insights**
- Customers with higher balances are more likely to accept loans.
- Campaign-related features influence loan acceptance behavior.

---

### **Files Included**
- `Task5_Personal_Loan.ipynb`
