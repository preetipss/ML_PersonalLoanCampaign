# Personal Loan Campaign Prediction

## Overview

This project develops a machine learning classification model to predict whether an existing customer is likely to accept a personal loan offer. The objective is to help the marketing team identify high-potential customers, improve campaign effectiveness, and reduce marketing costs through targeted outreach.

---

## Business Problem

AllLife Bank is a fast-growing financial institution that wants to increase the conversion rate of its personal loan campaigns.

Rather than marketing to every customer, the bank wants to identify customers who are most likely to accept a loan offer using historical customer data.

---

## Objective

Build a predictive classification model that:

- Predicts whether a customer will accept a personal loan offer.
- Identifies the key factors influencing loan acceptance.
- Provides actionable business recommendations for targeted marketing campaigns.

---

## Dataset

The dataset contains **5,000 customer records** with **14 features** including:

- Age
- Experience
- Income
- Family Size
- Education
- Mortgage
- Credit Card Spending (CCAvg)
- Securities Account
- CD Account
- Online Banking
- Credit Card Usage
- Personal Loan (Target Variable)

---

## Project Workflow

- Data Loading
- Data Exploration
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Analysis
- Decision Tree Model
- Pre-pruned Decision Tree
- Post-pruned Decision Tree
- Model Evaluation
- Feature Importance
- Business Recommendations

---

## Machine Learning Models

The following models were developed and compared:

- Decision Tree (Default)
- Decision Tree (Pre-pruned)
- Decision Tree (Post-pruned)

The final model was selected based on its ability to generalize well on unseen data.

---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

The notebook also compares training and testing performance to ensure the model is not overfitting.

---

## Key Insights

The most influential factors affecting loan acceptance include:

- Income
- Education
- Family Size

Customers with:

- Higher income
- Graduate/Professional education
- Larger family size

were significantly more likely to accept a personal loan offer.

---

## Business Recommendations

- Target high-income customers for future campaigns.
- Prioritize customers with Graduate or Professional education.
- Focus marketing efforts on customers with larger families.
- Use the predictive model to reduce unnecessary marketing costs.
- Improve campaign conversion through data-driven targeting.

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Repository Structure

```
ML_PersonalLoanCampaign/
│
├── ML_PersonalLoanCampaign.ipynb
├── README.md
├── requirements.txt
├── images/
└── data/ (optional)
```

---

## Results

The final Decision Tree model demonstrated strong predictive performance while maintaining good generalization on unseen data, making it suitable for supporting targeted personal loan marketing campaigns.

---

## Future Improvements

- Random Forest
- XGBoost
- LightGBM
- Hyperparameter Optimization
- SMOTE (if class imbalance exists)
- Model Deployment using Flask/FastAPI
- Interactive Dashboard using Streamlit

---

## Author

**Preeti Sahu**

Data Analytics | Machine Learning | PySpark | SQL | Power BI | GenAI
