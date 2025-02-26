# Customer Churn Prediction

## Overview
This project focuses on predicting customer churn using machine learning techniques. By analyzing customer data, we identify key factors influencing churn and develop a predictive model to help businesses retain customers effectively.

## Dataset
The dataset used in this project comes from Kaggle and contains customer information, including:
- **Demographics**
- **Service usage**
- **Payment history**

## Features & Preprocessing
- **Handling missing values** using `missingno`.
- **Feature engineering** to create meaningful attributes.
- **Encoding categorical variables** with `LabelEncoder`.
- **Scaling numerical features** using `StandardScaler`.

## Exploratory Data Analysis (EDA)
EDA was conducted using `seaborn` and `plotly` to visualize patterns and trends, revealing:
- Month-to-month contracts have a higher churn rate.
- Customers with higher total charges tend to have lower churn rates.
- Paperless billing correlates with higher churn.

## Model Training & Evaluation
Multiple models were tested, including:
- Logistic Regression
- Random Forest
- XGBoost (best performance)
- Decision Trees
- K-Nearest Neighbors
- Support Vector Classifier

Performance metrics used:
- **Accuracy Score**
- **Precision & Recall**
- **F1-Score**
- **Confusion Matrix**
- **ROC Curve**

## Key Findings
Important features influencing churn included:
- Contract type
- Tenure
- Payment method

## Business Impact
- Identify high-risk customers early.
- Implement targeted retention strategies.
- Optimize customer engagement and pricing strategies.
