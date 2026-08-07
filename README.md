# German Credit Risk Prediction

## Project Overview

This project builds an end-to-end Machine Learning pipeline to predict whether a customer is likely to have a good or bad credit risk using the German Credit dataset.

The project covers the complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and model comparison.

The primary objective is to help financial institutions identify high-risk loan applicants and support better lending decisions.

---

## Problem Statement

Banks receive thousands of loan applications every day.

Approving loans for high-risk customers may lead to financial losses, while rejecting trustworthy customers reduces business opportunities.

The objective of this project is to build a machine learning model capable of predicting customer credit risk using demographic and financial information.

---

## Dataset

**Dataset:** German Credit Dataset

Number of observations: **954**

Target Variable:

- Credit Risk
  - 1 = Good Credit
  - 2 = Bad Credit

Features include:

- Age
- Sex
- Job
- Housing
- Saving Accounts
- Checking Account
- Credit Amount
- Duration
- Purpose

---

## Machine Learning Workflow

- Data Cleaning
- Missing Value Treatment
- Exploratory Data Analysis
- One-Hot Encoding
- Train-Test Split
- Feature Scaling
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Model Evaluation
- Feature Importance Analysis
- Model Saving

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Joblib
- Google Colab

---

## Models Implemented

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | **0.82** |
| Decision Tree | **0.80** |
| Random Forest | **0.86** |
| XGBoost | **0.88** |

**Best Performing Model:** XGBoost

---

## Project Structure

```
German_Credit_Risk_Prediction/

│
├── images/
├── models/
├── results/
├── German_Credit_Risk_Prediction.ipynb
├── german_credit.csv
└── README.md
```

---

## Key Results

- Successfully predicted customer credit risk using multiple machine learning algorithms.

- Compared four classification models.

- XGBoost achieved the highest accuracy (**88%**).

- Feature importance analysis identified the most influential variables affecting credit risk.

- Saved the trained model using Joblib for future predictions.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV

- Cross-validation

- Deployment using Streamlit or Flask

- Probability calibration

- Model explainability using SHAP values

---

## Author

**Atulya Singh**

Master's in Economics

Delhi Technological University (DTU)
