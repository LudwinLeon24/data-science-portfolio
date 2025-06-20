# Insurance Customer Analysis and Modeling

This project is part of my Data Science Bootcamp portfolio and focuses on analyzing insurance customer data to build predictive models that can support business decision-making. It includes classification, regression, and data privacy techniques.

## 📌 Project Overview

The main objective of this project is to understand customer behavior and predict insurance benefits using different machine learning approaches. We also explore how to protect sensitive data without compromising model performance.

## 🧠 What We Did

The project is divided into four main tasks:

### 1. Similarity Search (k-NN without labels)
- Found the k most similar clients based on demographic features.
- Tested combinations with/without scaling and different distance metrics.
- Evaluated how scaling affects distance-based models.

### 2. Binary Classification (k-NN with labels)
- Predicted whether a customer receives insurance benefits.
- Built a baseline model using random predictions.
- Trained and evaluated a k-NN classifier with and without feature scaling.
- Optimized `k` based on F1 score.

### 3. Regression
- Predicted the **amount** of benefits received using linear regression.
- Implemented linear regression using both matrix operations and scikit-learn.
- Calculated and interpreted RMSE and R².

### 4. Data Obfuscation
- Applied a reversible matrix transformation to anonymize data.
- Verified that obfuscation does not alter the regression results.
- Demonstrated the recovery of original data from the transformed version.

## 🛠️ Tools & Libraries

- Python (pandas, NumPy, scikit-learn)
- Data visualization: seaborn
- Jupyter Notebook

## 🧑‍💻 Skills Demonstrated

- Data preprocessing and scaling
- Distance metrics and k-NN
- Classification metrics (F1, confusion matrix)
- Linear algebra (matrix multiplication, inversion)
- Regression evaluation (RMSE, R²)
- Data privacy techniques

## 📂 Dataset

The dataset includes anonymized customer records with the following features:
- `gender`, `age`, `income`, `family_members`
- Target variables: `insurance_benefits` and `insurance_benefits_received`

## 📈 Final Notes

This end-to-end project demonstrates how machine learning and data analysis can support insurance companies in:
- Identifying similar customers
- Predicting benefit eligibility
- Estimating benefit amounts
- Protecting client data without losing model accuracy

---

Feel free to explore the notebook and code to see the full process.


