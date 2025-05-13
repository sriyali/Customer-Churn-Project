# 📊 Customer Churn Prediction - Telecom Industry

This project is part of the Intellipaat Data Science course and focuses on analyzing and predicting customer churn using a telecom dataset. As a data scientist at a telecom company "Neo", the goal is to identify patterns in customer behavior and build predictive models to reduce churn rate.

---

## 🎯 Objective

- Analyze telecom customer data to discover trends related to customer churn.
- Perform data manipulation and visualization for business insights.
- Build predictive models using:
  - Linear Regression
  - Logistic Regression
  - Decision Tree
  - Random Forest
- Recommend solutions to retain customers based on the findings.

---

## 🗂️ Dataset

**Filename:** `customer_churn.csv`

**Source:** Provided by Intellipaat

**Features include:**
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `MonthlyCharges`, `TotalCharges`
- `InternetService`, `Contract`, `PaymentMethod`
- `Churn` (target variable)

---

## 🛠️ Tasks Performed

### 1️⃣ Data Manipulation
- Extract specific columns and filter records using logical conditions.
- Perform sampling and value counting.

### 2️⃣ Data Visualization
- Bar plot for Internet Service distribution.
- Histogram of tenure.
- Scatter plot between tenure and monthly charges.
- Boxplot comparing tenure across contract types.

### 3️⃣ Linear Regression
- Predict `MonthlyCharges` based on `tenure`.
- Calculate error and evaluate with RMSE.

### 4️⃣ Logistic Regression
- Simple logistic regression with `MonthlyCharges` as input and `Churn` as output.
- Multiple logistic regression using `tenure` and `MonthlyCharges`.

### 5️⃣ Decision Tree
- Classification model to predict churn using `tenure`.

### 6️⃣ Random Forest
- Classification using both `tenure` and `MonthlyCharges` to predict churn.

---

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn

---
