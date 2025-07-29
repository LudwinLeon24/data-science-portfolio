# Swift Lift Taxi – Hourly Demand Forecast

This project aims to predict the number of hourly taxi orders using historical data from March to August 2018. The goal was to build a model with RMSE ≤ 48 to support operational planning.

# Key Steps

- Resampled data by hour and cleaned duplicates
- Extracted time-based features (hour, weekday, month)
- Trained and compared three models:
  - **Linear Regression** (RMSE: 36.34)
  - **Random Forest** (RMSE: 22.89)
  - **LightGBM** (RMSE: 21.97 ✅)

# Result

The **LightGBM** model outperformed others and meets the RMSE requirement, making it suitable for production use.

# Tools

- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `scikit-learn`: Linear Regression, Random Forest
- `LightGBM`
- `train_test_split`, `RMSE`
