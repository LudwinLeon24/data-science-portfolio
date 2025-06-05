# 🧠 Customer Churn Prediction – Beta Bank

This project predicts whether a customer will leave Beta Bank, using historical data and machine learning models to help reduce customer churn.

## 📁 Dataset

- `Churn.csv`: includes customer info such as:
  - CreditScore, Geography, Gender, Age, Tenure, Balance
  - NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary
  - `Exited`: target (1 = left, 0 = stayed)

## 🧪 Process Overview

1. **Data Preprocessing**  
   - Dropped ID columns, encoded categoricals  
   - Split into training/test sets

2. **Baseline Model**  
   - Trained without addressing class imbalance  
   - F1 Score below 0.59

3. **Imbalance Handling**  
   - Used **RandomOverSampler** and **SMOTE**  
   - Tested multiple models and hyperparameters

4. **Final Model**  
   - F1 Score: **0.61** ✅  
   - AUC-ROC: **0.86**

## ⚙️ Tools

- Python,
- pandas, 
- scikit-learn, 
- imbalanced-learn, 
- matplotlib,
- seaborn,

## 👤 Author

**Ludwin León** – Data Science Portfolio

