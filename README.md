# Customer Churn Prediction

## Problem Statement
Customer churn directly impacts revenue in subscription-based businesses.  
This project aims to predict whether a telecom customer is likely to churn so that proactive retention actions can be taken.

---

## Dataset
Telecom customer behavior dataset containing:
- Call usage patterns (day, evening, night, international)
- Service plans (international, voice mail)
- Customer service interaction frequency

Target variable:
- `Churn` (1 = churned, 0 = retained)

---

## Project Structure
```
customer-churn-prediction/
│
├── data/
│   ├── raw/
│   │   └── telco_churn.csv
│   └── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_modeling.ipynb
│
├── screenshots/
│   ├── churn_distribution.png
│   ├── confusion_matrix_rf.png
│   └── roc_curve_rf.png
│
├── reports/
│   └── business_insights.pdf
│
├── README.md
└── requirements.txt


```

---

## Approach
1. Exploratory Data Analysis (EDA)
2. Feature engineering and encoding
3. Baseline Logistic Regression
4. Threshold tuning for recall optimization
5. Random Forest modeling
6. Business-driven model selection

---

## Final Model Performance
- **Model:** Random Forest
- **Threshold:** 0.35
- **Churn Recall:** 79%
- **ROC–AUC:** 0.88
- **Goal:** Balance churn detection and retention cost

---

## Business Insights
- Customers with frequent customer service calls are at the highest risk of churn.
- International plan users churn at higher rates.
- Higher international usage and charges increase churn probability.
- Threshold tuning significantly improves business relevance of predictions.

---

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn

---

## Future Improvements
- Hyperparameter tuning
- XGBoost comparison
- Model deployment as an API
