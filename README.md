# 🏦 Credit Risk Analysis Dashboard (Tableau)

This project uses a credit risk dataset to explore borrower demographics, loan performance, and predictive risk factors using interactive Tableau dashboards. It is designed to help financial analysts, risk managers, and business stakeholders explore trends in loan defaults and lending behavior.

## 📊 Project Overview

The goal is to build two intuitive dashboards using Tableau Public:

- **Dashboard 1: Credit Risk Overview**
  - Key performance indicators (KPIs)
  - Demographics of loan applicants
  - Risk and loan status breakdown

- **Dashboard 2: Credit Loan Risk**
  - Risk tier segmentation
  - Loan status by grade, purpose, and income
  - Full filterable loan-level table for detailed exploration

## 💡 Key Insights

- Most defaults occurred in **lower loan grades (D, E, F, G)**
- **Employment length** and **home ownership type** are important borrower traits
- Higher **interest rates** and **credit card loans** are strongly associated with high risk
- The majority of loans were given to individuals **renting homes**

## 🗂️ Dataset

- **Source**: [Kaggle - Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
- **Records**: ~32581 loan applications
- **Target Variable**: `loan_status` (0 = Non-default, 1 = Default)
- **Key Fields**: `loan_grade`, `loan_intent`, `loan_int_rate`, `person_income`, `person_home_ownership`, `loan_amnt`, `loan_percent_income`

## 🛠 Features & Filters

Both dashboards are fully interactive with filters on:
- Income group
- Loan grade
- Loan purpose
- Risk tier
- Home ownership
- Loan status

Tooltips and color coding make it easier to explore high-risk segments.

## 📁 Files

- `Credit_Risk_Analysis.twbx` — Tableau Public workbook
- `credit_risk_dataset.csv` — Raw dataset used for visuals

## 🚀 Getting Started

1. Clone this repo
2. Open the `.twbx` file in Tableau Public Desktop

## 👤 Author

- **Mani Chandana Alle** - [LinkedIn](https://www.linkedin.com/in/manichandanaalle/)
- **Chliona Pham** - [LinkedIn](https://www.linkedin.com/in/chlio59/)

