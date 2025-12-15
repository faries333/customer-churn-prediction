# Customer Churn Prediction

## Problem Statement
Predict whether a telecom customer is likely to churn in order to enable proactive retention strategies.

## Dataset
Telecom customer behavior dataset containing usage, service plans, and customer service interactions.

## Approach
- Exploratory Data Analysis (EDA)
- Feature Engineering & Encoding
- Baseline Logistic Regression
- Threshold tuning for recall optimization
- Random Forest modeling and evaluation
- Business-driven model selection

## Model Performance
- Final Model: Random Forest
- Churn Recall: 79%
- ROC–AUC: 0.88
- Threshold tuned to balance recall and false positives

## Key Insights
- Customer service calls are the strongest churn indicator.
- International plan customers churn at higher rates.
- Threshold tuning significantly improves business relevance.

## Tools & Technologies
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
