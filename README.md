## 🧠 CUSTOMER DATA PREPROCESSING & FEATURE ENGINEERING
## 📌 Project Overview

This project demonstrates a complete end-to-end data preprocessing and feature engineering pipeline applied to a customer transaction dataset.
The goal is to transform raw, unstructured, and inconsistent data into a clean, reliable, and machine-learning-ready dataset.

The workflow follows industry-standard data science practices and is suitable for academic evaluation, hackathons, and ML foundation project

-----------------

## 🎯 Objectives

Clean raw customer and transaction data

Handle missing values and outliers

Engineer meaningful features

Prepare a final dataset ready for ML models

-----------------


## 📁 Final Output File

processed_customer_data.csv

-----------------


## 📊 Dataset Summary

The dataset contains information related to customers, transactions, behavior, and time-based activity.

## 👤 Customer Demographics

Age

Gender

City

Annual Income

-----------------



## 🛒 Transaction Details

Quantity

Price

Discount

Purchase Date

-----------------


## ⭐ Customer Behavior

Loyalty Score

Rating

Activity Status

-----------------


## 📅 Time-Based Fields

Signup Date

Last Purchase Date

-----------------


## 🚨 Problems in Raw Data

During initial analysis, the following issues were identified:

❌ Missing values in key numerical columns

❌ Outliers affecting numerical distributions

❌ Categorical variables not ML-compatible

❌ Date columns unusable in raw form

❌ ID columns causing potential data leakage

These issues made the raw dataset unsuitable for machine learning models.

-----------------


## 🛠️ Techniques Used

## 1️⃣ Data Cleaning

Removed duplicate records

Standardized column formats

Converted date columns to datetime

-----------------


## 2️⃣ Missing Value Handling

Numerical → Median Imputation

Categorical → Mode Imputation

Added missing-value indicator columns

✔ Median imputation worked best due to skewed numerical data.

-----------------


## 3️⃣ Outlier Treatment

IQR (Interquartile Range) method

Winsorization for extreme values

Outlier flag feature added

## 4️⃣ Feature Engineering

New meaningful features were created:

days_since_signup

days_since_last_purchase

total_purchase_value

purchase_per_day

signup_year, signup_month

These features improve data interpretability and predictive power.

-----------------


## 5️⃣ Encoding

Ordinal Encoding for ordered categorical features

One-Hot Encoding for nominal categorical features

-----------------


## 6️⃣ Scaling & Transformation

Normalization / Min-Max Scaling

Log transformation for skewed numerical features

✔ Scaling after imputation produced stable and consistent results.

-----------------


## 📦 Final Deliverables

✅ Cleaned dataset

✅ Feature-engineered dataset

✅ ML-ready CSV file

✅ Reproducible preprocessing code

✅ Short academic summary

-----------------


## 🏆 Key Highlights

✔ End-to-end preprocessing pipeline

✔ Real-world data issues handled

✔ Strong feature engineering logic

✔ Clean and structured code

✔ Academic + practical relevance

-----------------

## 📊 Data Profiling Report

📄 **Download Profiling PDF**  
👉 [Click here to download](https://raw.githubusercontent.com/tushar123851/customer-purchase-propensity-set-A/main/profiling_report/profiling_report.pdf)

-----------------

## 🛠️ Tech Stack

| Category | Tools |
|--------|------|
| Language | Python 3.11+ |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| ML Preprocessing | Scikit-learn |
| Statistics | SciPy |


-----------------


## 📥 Download Complete Project

📦 Download Full Project (ZIP):

👉 [https://github.com/tushar123851/customer-purchase-propensity-set-A/archive/refs/heads/main.zip]

📂 View Repository:

👉 [https://github.com/tushar123851/customer-purchase-propensity-set-A]

-----------------


## 👤 Author

Tushar Vala

📊 Data Science Enthusiast
🐍 Python | Pandas | Machine Learning

-----------------


## 📝 Conclusion

This project showcases a practical and industry-aligned data science workflow focused on data quality, feature relevance, and reproducibility.

It reflects the core skills required for hackathons, college submissions, and entry-level data science roles, making it a strong foundation for future machine learning projects.
