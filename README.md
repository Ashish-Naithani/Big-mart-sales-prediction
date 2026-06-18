# BigMart Sales Prediction using XGBRegressor

## 📌 Project Overview

This project focuses on predicting BigMart product sales using Machine Learning. The objective is to predict **Item Outlet Sales** based on product and outlet-related features.

The project uses data preprocessing techniques, **One Hot Encoding**, and **XGBRegressor** for regression-based prediction.

---

## 🎯 Problem Statement

BigMart wants to predict sales for different products across various outlets.

The goal is to build a machine learning model that can estimate sales based on:

- Product details
- Outlet information
- Item characteristics
- Historical sales data

---

## 📂 Dataset Features

| Feature | Description |
|---------|-------------|
| Item_Identifier | Unique product ID |
| Item_Weight | Weight of product |
| Item_Fat_Content | Fat category of product |
| Item_Visibility | Product visibility percentage |
| Item_Type | Product category |
| Item_MRP | Maximum Retail Price |
| Outlet_Identifier | Outlet ID |
| Outlet_Establishment_Year | Outlet establishment year |
| Outlet_Size | Outlet size |
| Outlet_Location_Type | Location category |
| Outlet_Type | Outlet category |

### Target Variable
| Item_Outlet_Sales | Item sale for an Outlet | 

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost

---

# 🔄 Project Workflow

## 1. Data Collection

Loaded BigMart sales dataset using Pandas.

## 2. Data Cleaning

Performed:

- Missing value treatment
- Duplicate checking
- Data type correction

## 3. Exploratory Data Analysis

Analyzed:

- Sales distribution
- Feature relationships
- Outliers
- Data patterns

## 4. Data Preprocessing

Performed:

- Handling categorical variables
- Feature selection
- Train-test split

---

# 🔢 Feature Encoding

Machine learning models cannot understand text values directly.

Therefore, categorical columns were converted into numerical values using hot encoding.


---

# 🤖 Machine Learning Model

## XGBRegressor

XGBoost Regression algorithm was used because it provides:

- High accuracy
- Better handling of nonlinear relationships
- Reduced overfitting

---

# 📊 Model Evaluation Metrics

The model was evaluated using:

## R2 Score

Shows model accuracy.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- Model comparison

---
