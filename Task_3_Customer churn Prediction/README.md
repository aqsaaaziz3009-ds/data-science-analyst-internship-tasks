Task 3: Customer Churn Prediction (Bank Customers)

## Objective
The objective of this task is to predict whether a bank customer is likely to leave the bank (churn) based on their personal and account-related information.

## Dataset
Churn Modelling Dataset

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

The target variable is:
- **Exited**
  - 1 → Customer left the bank (Churn)
  - 0 → Customer stayed with the bank

### Steps Performed ###

1. **Data Loading**
   - Loaded the dataset using the pandas library.

2. **Data Exploration**
   - Checked dataset shape, columns, and basic information.
   - Analyzed the target variable distribution.

3. **Data Preprocessing**
   - Removed unnecessary columns such as customer ID.
   - Encoded categorical variables like Geography and Gender.
   - Split the dataset into features (X) and target (y).

4. **Model Training**
   - Trained a classification model to predict customer churn.

5. **Model Evaluation**
   - Evaluated the model using accuracy score.
   - Used confusion matrix to analyze correct and incorrect predictions.

6. **Feature Importance Analysis**
   - Analyzed which features contribute the most to customer churn.
   - 
### Results and Insights
- Customers with higher age and lower account activity are more likely to churn.
- Balance and number of products also play an important role in churn prediction.
- The model provides useful insights for banks to identify at-risk customers.

### Conclusion
This task demonstrates how machine learning classification techniques can be used to predict customer churn. The insights gained from this analysis can help banks take preventive actions to retain customers and reduce churn.

