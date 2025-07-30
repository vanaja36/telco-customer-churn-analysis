# Telco Customer Churn Analysis 📉

This end-to-end data analysis project explores why customers are leaving a telecom company and provides actionable insights to reduce churn. Using Python and exploratory data analysis (EDA), this project dives into customer behavior and identifies churn triggers like contract type, tenure, and payment method.

## 📌 Executive Summary

Customer churn — when customers stop doing business with a company — is a critical problem in the telecom industry. Reducing churn increases revenue and lowers acquisition costs.

This project uses a dataset of **7,043 customers** to:
- Explore churn patterns with data visualization
- Identify at-risk customer segments
- Recommend data-backed strategies to retain customers

**Goal**: Enable data-driven business decisions to minimize churn and improve customer lifetime value.

## 🎯 Problem Statement

The telecom industry faces high customer attrition, especially among:
- Month-to-month subscribers
- Electronic check users
- Short-tenure customers

By identifying these patterns early, businesses can intervene with targeted strategies. This project uses EDA techniques to reveal such patterns and propose solutions.

## 📈 Dataset Overview

- 📁 File: `customer churn.csv`
- 📊 Records: 7,043 rows
- 🧩 Features: Customer demographics, services used, billing info, and churn label

**Target Variable**: `Churn` (Yes/No)

**Key Features**:
- `Contract`: Month-to-month, One year, Two year
- `PaymentMethod`: Electronic check, Credit card, Bank transfer, etc.
- `Tenure`: Number of months the customer has stayed
- `SeniorCitizen`, `InternetService`, `MultipleLines`, `OnlineSecurity`

## 🧪 Tools & Libraries Used

- **Python** (Jupyter Notebook)
- `Pandas` – Data manipulation
- `Seaborn`, `Matplotlib` – Data visualization
- `NumPy` – Numerical operations

## 🔍 EDA Methodology

### 1. Data Cleaning
- Handled missing values (`TotalCharges`)
- Converted datatypes (e.g., tenure to integer)
- Encoded binary categories

### 2. Univariate & Bivariate Analysis
- Explored distributions of key columns (contract type, payment method)
- Compared churn rates across customer groups

### 3. Visual Insights
- Bar charts, heatmaps, and tenure curves to illustrate patterns
- Correlation analysis between features and churn

---

## 📊 Key Findings

| Factor              | Churn Rate | Insight |
|---------------------|------------|---------|
| Month-to-Month      | 42%        | Highest churn among contract types |
| Electronic Check    | 45%        | Most churn-prone payment method |
| Tenure < 1 year     | 50%        | New customers most likely to churn |
| Senior Citizens     | 41%        | Higher churn than average |
| Fiber Optic Users   | 30%        | Slightly higher churn than DSL users |

## 💡 Business Recommendations

Based on the EDA:

- 🔒 **Promote Long-Term Contracts**  
  Offer incentives to convert month-to-month users to yearly contracts. This could cut churn from 42% to under 10%.

- 💳 **Discourage Electronic Checks**  
  Recommend secure alternatives like bank transfers or credit cards via app notifications or billing offers.

- 🕰 **Target Early-Stage Customers**  
  Focus retention campaigns within the first 6–12 months of a customer’s tenure.

- 👴 **Senior-Citizen Loyalty Programs**  
  Offer better support or discounts to reduce churn in senior customers (41% churn rate).

