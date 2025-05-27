# 📊 Megaline Tariff Revenue Analysis (Sprint 5 - Statistics Project)

## 🧠 Project Overview

This project is part of the Data Science Bootcamp and focuses on **statistical data analysis**. As a data analyst at the fictional telecom company **Megaline**, your task is to identify which of the company's two prepaid tariffs — `Surf` or `Ultimate` — generates more monthly revenue on average.

I perform **data cleaning, exploratory analysis, and hypothesis testing** to provide data-driven recommendations for the business team.

---

## 🎯 Business Objective

Megaline’s marketing team wants to understand which prepaid plan — **Surf** or **Ultimate** — brings in more revenue, in order to optimize the advertising budget and user acquisition strategy.

---

## 📂 Dataset Description

You are given data for 500 Megaline users throughout 2018. The project uses **5 separate CSV files** containing:

1. `users.csv`: Basic information about users (e.g. city, plan, age).
2. `calls.csv`: Records of all calls made (with duration and date).
3. `messages.csv`: SMS sent by users.
4. `internet.csv`: Internet sessions and data usage (in MB).
5. `plans.csv`: Details about Surf and Ultimate plans.

Each file contains a `user_id` to join with other tables.

---

## 📦 Tariff Plan Information

| Plan     | Monthly Fee | Minutes | SMS | Data (GB) | Extra Minute | Extra SMS | Extra GB |
|----------|-------------|---------|-----|-----------|--------------|-----------|----------|
| Surf     | $20         | 500     | 50  | 15 GB     | $0.03        | $0.03     | $10      |
| Ultimate | $70         | 3000    | 1000| 30 GB     | $0.01        | $0.01     | $7       |

- **Minutes** are rounded up per call.
- **Data** is rounded up monthly to GB from MB.

---

## 🧪 Methodology

1. **Data Preprocessing**
   - Convert data types (e.g. dates).
   - Clean missing or incorrect data.
   - Aggregate monthly usage metrics per user.

2. **Revenue Calculation**
   - Calculate monthly revenue by subtracting free allowances and applying overage charges per user.

3. **Exploratory Data Analysis**
   - Compute average, variance, and standard deviation of usage.
   - Plot histograms of minutes, SMS, and data use per plan.

4. **Hypothesis Testing**
   - Test if the average revenue differs between Surf and Ultimate users.
   - Test if NY/NJ area users have different average revenue compared to other users.



## 🧾 Key Findings

- Summary statistics and visualizations of user behavior per plan.
- Results of hypothesis tests using appropriate significance levels.
- Final recommendation on which plan is more profitable.

