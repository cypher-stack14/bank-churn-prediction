# Bank Churn Prediction Using Machine Learning 

## Overview

This project aims to predict customer churn for a bank using machine learning techniques. By identifying at-risk customers, the bank can improve retention strategies and enhance customer satisfaction.

## Problem statement

The bank wants to create more value out of its customer data. Analyze the data and propose how internal and external utilization of the analysis results increases the banks revenues.

## Features
- Data preprocessing and exploratory data analysis (EDA).
- Utilized SMOTE for balancing highly imbalanced datasets.
- Built and compared multiple machine learning models:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - SVM
  - Decision Tree
  - KNN
  - Gradient Boosting Classifier
- Model Evaluation Using accuracy and AUC-ROC metrics.
- Dashboard visualization with Power BI.

## Technologies Used
- **Programming Languages**: Python
- **Libraries**:
  - Pandas, NumPy for data processing
  - Scikit-learn, Matplotlib, Seaborn for machine learning and visualization
- **Tools**:
  - Power BI for dashboards
  - Google Colab for development

## Data Source
- The dataset used for this project is **Churn_Modelling.csv** from [Kaggle](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)).
- Contains customer demographic, account, and transaction information.

## Data Description

**RowNumber:** Row number for the row in the data table.

**CustomerId:** Unique Identification number of the customer.

**Surname:** Surname (Lastname) of the customer.

**CreditScore:** Credit Score of the customer.

**Geography:** Geographical location (country) of the customer.

**Gender:** Gender of the customer (Male / Female).

**Age:** Age of the customer.

**Tenure:** Number of years the customers has been associated with the bank.

**Balance:** The amount of balance in the customer's account.

**NumOfProducts:** The number of product.

**HasCrCard:** Denotes if the customer owns a credit card with the bank.

**IsActiveMember:** Denotes if the customer is active with the bank.

**EstimatedSalary:** Estimated salary of the customer.

**Exited:** Denotes if the customer has churned (exited) from the bank or not.

## Results
- **Accuracy**: 89%
- **Best Fitted Model:** Random Forest
- **AUC-ROC Score**: 95%
- Significantly improved the bank’s ability to identify at-risk customers.
