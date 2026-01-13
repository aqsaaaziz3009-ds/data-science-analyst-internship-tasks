## **Task 3: Customer Churn Prediction (Bank Customers)**

### **Objective**
The objective of this task is to identify bank customers who are likely to leave the bank by analyzing customer demographics and account-related information.

---
### **Dataset**
The dataset used for this task is the **Churn Modelling Dataset**.
The dataset contains customer information such as:
- Credit score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of products
- Whether the customer has a credit card
- Whether the customer is an active member
- Estimated salary

**Dataset Details:**
- Features include age, balance, tenure, number of products, and activity status.
- Target Variable:
  - Exited (1 = Customer left, 0 = Customer stayed)

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
- Dataset is loaded and unnecessary columns are removed.
- Categorical variables such as gender and geography are encoded.

#### **2. Data Analysis**
- Customer behavior is analyzed through visualizations.
- Churn distribution is examined.

#### **3. Model Training**
- A classification model is trained to predict churn.

#### **4. Model Evaluation**
- Performance is measured using accuracy and confusion matrix.
- Feature importance is analyzed to identify key churn factors.

---

### **Key Insights**
- Older customers and inactive users are more likely to churn.
- Balance and number of products influence churn behavior.

---
### Conclusion
This task demonstrates how machine learning classification techniques can be used to predict customer churn. The insights gained from this analysis can help banks take preventive actions to retain customers and reduce churn.

### **Files Included**
- `Task3_Customer_Churn_Prediction.ipynb`




