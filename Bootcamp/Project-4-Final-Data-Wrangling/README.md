# 🛒 Instacart Exploratory Data Analysis  

## 📘 Project Overview

This project focuses on performing an exploratory data analysis (EDA) using a cleaned and modified version of the **Instacart** dataset. The main goal was to understand customer purchasing behavior through data pre-processing and visualization.

I worked with the following CSV files:

- `instacart_orders.csv`
- `products.csv`
- `order_products.csv`
- `aisles.csv`
- `departments.csv`


## 🧹 Data Preprocessing

I performed thorough data cleaning to ensure accuracy and consistency:

- ✅ **Data type correction:** Converted key columns such as `order_id`, `user_id`, and `product_id` to integer types for optimized performance.
- ✅ **Missing values handling:** Managed missing values (e.g., in `days_since_prior_order`) based on their context.
- ✅ **Duplicate removal:** Identified and removed exact duplicates and duplicate rows based on key combinations.
- ✅ **Column renaming and reordering (when necessary)** for clarity and easier analysis.

All cleaning steps were documented in the Jupyter Notebook.


## 📊 Exploratory Data Analysis (EDA)

The EDA phase aimed to answer specific business-driven questions through descriptive statistics and visualizations.

### 📅 Order Behavior
- Verified valid value ranges for `order_hour_of_day` (0–23) and `order_dow` (0–6).
- Plotted the distribution of orders by hour of day and day of week.
- Analyzed distribution of `days_since_prior_order` to understand purchase frequency.

### 📦 Product Insights
- Compared order times between Wednesday and Saturday using histograms.
- Analyzed total number of orders per customer.
- Identified the **top 20 most frequently ordered products** by name and ID.

### 🔁 Reordering Patterns
- Explored number of items per order and its distribution.
- Highlighted **top 20 products with the most reorders**.
- Calculated the **reorder rate per product** (i.e., how often each product is reordered).
- Calculated **average reorder rate per user**.
- Identified the **top 20 products most frequently added first to carts**.


## ✅ Key Takeaways

This project helped me to:

- Strengthen my skills in **pandas**, **matplotlib**, and **seaborn**
- Apply data cleaning techniques to real-world, messy datasets
- Extract actionable insights about **consumer purchasing behavior**
- Understand reordering trends and customer engagement in e-commerce


## 📂 Files Included

- `instacart_orders.csv`
- `products.csv`
- `order_products.csv`
- `aisles.csv`
- `departments.csv`
- `instacart_eda.ipynb` – Jupyter Notebook with full analysis
- `README.md` – Project summary and documentation


## 🔧 Tools & Libraries

- Python 3.10
- pandas
- matplotlib
- seaborn
- Jupyter Notebook


