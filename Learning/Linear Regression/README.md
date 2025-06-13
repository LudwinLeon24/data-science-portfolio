# Linear Regression from Scratch 🧠

This project demonstrates how to build a simple linear regression model from scratch using Python, without using machine learning libraries for modeling. It progresses through three educational steps:

## 📈 Project Steps

1. **Dummy Model**  
   A placeholder model that always predicts zero. It helps test the pipeline and sanity-checks the baseline using the R² score.

2. **Baseline Model**  
   Initializes weights (`w`) as zeros and the bias (`w0`) as the mean of the target variable.

3. **Linear Regression (Normal Equation)**  
   Implements the analytical solution using the closed-form formula to minimize the Mean Squared Error. A bias column of ones is added to the feature matrix.

## 🛠 Libraries Used

- `numpy` — For matrix operations
- `pandas` — For data handling
- `sklearn.metrics.r2_score` — To evaluate model performance

---

This project focuses on understanding the core logic and math behind linear regression before relying on external libraries like `scikit-learn`.
