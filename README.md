# 📊 Customer Churn Prediction & Retention Analytics

## 📌 Project Overview

Customer churn is a critical challenge for subscription-based businesses. This project analyzes customer behavior patterns, identifies key churn drivers, and develops machine learning models to predict customers at risk of leaving.

Using exploratory data analysis, business analytics, and predictive modeling techniques, the project provides actionable recommendations to improve customer retention and reduce revenue loss.

---

## 🎯 Business Objective

The goal of this project is to:

* Identify key factors influencing customer churn.
* Predict customers likely to churn.
* Evaluate machine learning models for churn prediction.
* Provide actionable business recommendations to improve retention.

---

## 📂 Dataset

The analysis uses the Telco Customer Churn Dataset containing over 7,000 customer records.

The dataset includes:

* Customer demographics
* Contract information
* Service subscriptions
* Billing and payment details
* Customer lifetime value (CLTV)
* Churn indicators

---

## 🛠 Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## 📊 Key Business Insights

### Contract Type Impact

| Contract Type  | Churn Rate |
| -------------- | ---------- |
| Month-to-Month | 42.7%      |
| One Year       | 11.3%      |
| Two Year       | 2.8%       |

Customers on month-to-month contracts exhibit significantly higher churn risk.

### Customer Tenure Impact

| Tenure Group | Churn Rate |
| ------------ | ---------- |
| 0–12 Months  | 47.7%      |
| 12–24 Months | 28.7%      |
| 24–48 Months | 20.4%      |
| 48–72 Months | 9.5%       |

Customer churn decreases substantially as tenure increases.

### Technical Support Impact

Customers without technical support experienced a churn rate of 41.6%, compared to only 15.2% for customers receiving support.

### Payment Method Risk

Electronic check users showed the highest churn rate at 45.3%.

---

## 🤖 Machine Learning Results

### Logistic Regression

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 79.74% |
| Precision | 63.69% |
| Recall    | 55.35% |
| F1 Score  | 59.23% |
| ROC-AUC   | 84.22% |

### Random Forest

| Metric    | Value  |
| --------- | ------ |
| Accuracy  | 79.46% |
| Precision | 64.21% |
| Recall    | 51.34% |
| F1 Score  | 57.06% |
| ROC-AUC   | 84.46% |

### Selected Model

Logistic Regression was selected as the preferred model due to its stronger Recall and F1 Score, making it more effective at identifying customers at risk of churn.

---

## 📈 Top Predictors of Churn

* Customer Tenure
* Contract Type
* Dependents
* Fiber Optic Internet Service
* Monthly Charges
* Total Charges
* Streaming TV
* Multiple Lines

---

## 🎯 Business Recommendations

* Encourage migration from month-to-month plans to long-term contracts.
* Strengthen customer onboarding during the first year.
* Expand technical support adoption.
* Improve retention campaigns for high-risk customer segments.
* Review pricing strategies for customers with higher monthly charges.

---

## 📁 Files Included

* 01_Churn_Analysis.ipynb
* 02_Churn_Prediction_Model.ipynb
* churn_cleaned.csv

---

## 🚀 Outcomes

This project demonstrates:

* Data Cleaning
* Exploratory Data Analysis
* Customer Analytics
* Machine Learning
* Predictive Modeling
* Customer Retention Strategy
* Business Intelligence

The project combines business analytics and machine learning to help organizations proactively identify at-risk customers and improve retention outcomes.
