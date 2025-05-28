# 🎮 Video Game Sales Analysis – Project 6

## 📊 Project Overview

This project is part of the integrated bootcamp curriculum, where I applied all the skills acquired during the first part of the course in a real-life analytical case study. 

I worked as a data analyst for **Ice**, an international online video game store. The goal was to identify patterns that determine whether a video game is likely to succeed. These insights help the company detect promising projects and plan marketing campaigns effectively.

We assumed it is **December 2016**, and the company is preparing a marketing strategy for 2017 based on historical data.

---

## 🧰 Tools & Technologies

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- Jupyter Notebook
- Statistical hypothesis testing
- Data cleaning & preprocessing

---

## 🔍 Project Objectives

- Clean and preprocess historical video game sales data.
- Identify sales trends across platforms and genres.
- Analyze the impact of critic and user reviews.
- Build user profiles for different regions.
- Test hypotheses to extract meaningful business insights.

---

## 🗂️ Dataset Description

The dataset includes sales and metadata for video games. Columns:

- `name`: Game title  
- `platform`: Console or system (e.g., PS4, Xbox One)  
- `year_of_release`: Release year  
- `genre`: Game genre  
- `na_sales`, `eu_sales`, `jp_sales`, `other_sales`: Sales in millions by region  
- `critic_score`: Score by critics (0–100)  
- `user_score`: Score by users (0–10)  
- `rating`: ESRB rating (e.g., E, T, M)

---

## 🧹 Step 1–2: Data Cleaning & Preparation

- Renamed columns to lowercase.
- Converted data types where necessary (e.g., `year_of_release` to integers).
- Handled missing values:
  - Left some missing values where relevant (e.g., future release dates marked as `TBD`).
  - Explained why data might be missing (e.g., older games with no review scores).
- Calculated total global sales per game (`global_sales`).

---

## 📈 Step 3: Exploratory Data Analysis (EDA)

- Analyzed how many games were released each year to determine relevance of historical data.
- Identified top platforms by total sales and their lifespan.
- Focused analysis on data from **2013–2016** to build a realistic model for 2017.
- Plotted sales distributions and boxplots by platform.
- Assessed the impact of critic/user scores on sales through scatter plots and correlation coefficients.
- Analyzed genre profitability and identified genres with high and low average sales.

---

## 🌎 Step 4: Regional User Profiles

For each region (NA, EU, JP):

- Identified top 5 platforms and their market share.
- Identified top 5 genres.
- Evaluated how **ESRB ratings** influenced regional sales.

---

## 📐 Step 5: Hypothesis Testing

### Hypothesis 1:
> H0: The average user ratings for Xbox One and PC are the same.  
> H1: The average user ratings for Xbox One and PC are different.  
- Method: Two-sample t-test (independent samples)  
- Significance level: α = 0.05  

### Hypothesis 2:
> H0: The average user ratings for Action and Sports genres are the same.  
> H1: The average user ratings for Action and Sports genres are different.  
- Method: Two-sample t-test  
- Significance level: α = 0.05  

Results and conclusions are discussed in the notebook.


