# Customer Churn Modelling – Data Cleaning & Analysis with Pandas

This repository contains an intermediate-level data analysis project using the **Pandas** library on the `Churn_Modelling.csv` dataset. The goal is to perform cleaning, transformation, and statistical analysis to prepare the data for further machine learning or visualization tasks.

---

## 📂 Dataset

The dataset used is `Churn_Modelling.csv`, which contains banking customer details including:
- CreditScore
- Geography
- Gender
- Age
- Tenure
- Balance
- NumOfProducts
- HasCrCard
- IsActiveMember
- EstimatedSalary
- Exited (Target Variable)

---

## 📊 What Was Done

The following Pandas-based operations and analysis techniques were used:

- `df.info()` — to inspect data types and null values
- `df.describe()` — to generate summary statistics
- Removing unnecessary columns (`drop`)
- Adding new columns
- Filling missing values (`fillna`)
- Removing null records (`dropna`)
- Applying transformations using `.apply()`
- Replacing specific values (`replace`)
- Updating columns
- Joining/merging datasets (if applicable)

---

## 🛠️ Libraries Used

- `pandas`
- `numpy` 
