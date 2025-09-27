# Loan Default Analysis

## 📌 Overview

This repository contains two connected projects focused on **loan default analysis**:

1. **SQL Analysis (`default_loan_project.sql`)**

   * Builds a `loan_default` database and creates a `customer_details` view with engineered features (age group, income group, credit risk classification).
   * Runs SQL queries to analyze customer demographics, loan purposes, credit scores, and their relationship with default probability.

2. **Python Notebook (`Loan_Default_Final_Showcase.ipynb`)**

   * Performs exploratory data analysis (EDA) and visualization.
   * Trains machine learning models to predict loan defaults.
   * Compares key metrics between defaulters and non-defaulters.



## 📊 Key Insights Explored

* Default rate by **age group** (young, middle-aged, 50+).
* Impact of **income level** and **credit score** on default probability.
* Loan distribution and defaults by **purpose, term length, and interest rate**.
* Effect of **mortgage, co-signer, and marital status** on default behavior.

---

## 📦 Requirements

Python libraries (see `requirements.txt`):

* `pandas`, `numpy`, `matplotlib`, `seaborn`
* `scikit-learn`, `xgboost`
* `jupyter`, `sqlalchemy`

SQL database: **MySQL / MariaDB**

---

## 📜 License

This project is licensed under the MIT License — see the `LICENSE` file for details.
