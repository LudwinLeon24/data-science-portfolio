# 📱 Megaline Plan Recommendation - Sprint 9

## 🧠 Overview

This project develops a machine learning model to help **Megaline**, a mobile operator, recommend the best mobile plan for its customers — **Smart** or **Ultra** — based on their usage behavior.

## 📊 Dataset

- File: `users_behavior.csv`
- Features:
  - `calls`: Number of calls
  - `minutes`: Total call duration
  - `messages`: Number of text messages
  - `mb_used`: Internet usage (in MB)
  - `is_ultra`: Target plan (1 = Ultra, 0 = Smart)

## 🛠️ Tech Stack

- `pandas` – Data handling  
- `scikit-learn` – Data splitting, modeling, and evaluation  
- `matplotlib` / `seaborn` – Data visualization  

## ⚙️ Modeling Workflow

- Data split into train, validation, and test sets  
- Models trained:  
  - Decision Tree  
  - Random Forest  
- Evaluation using accuracy and classification reports

## 📈 Results

**✅ Validation Accuracy:** 0.790  
**✅ Test Accuracy:** 0.820

**Classification Report (Test):**

