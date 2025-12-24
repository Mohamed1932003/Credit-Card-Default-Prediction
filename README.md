# Credit Card Default Prediction 💳

## Project Overview
An end-to-end Machine Learning project to predict the probability of credit card default using the UCI Dataset. This project focuses on handling imbalanced data and preventing Data Leakage.

## Key Features
- **Data Cleaning:** Handled undocumented categorical values.
- **Leakage Prevention:** Implemented Scikit-Learn **Pipelines** for robust cross-validation.
- **Feature Engineering:** Used **RobustScaler** for financial outliers.
- **Handling Imbalance:** Applied **SMOTE** (Synthetic Minority Over-sampling Technique).
- **Optimization:** Hyperparameter tuning of **XGBoost** using Grid Search.

## Results
- **Overall Accuracy:** 79%
- **F1-Score (Default Class):** 0.53
- **Recall (Default Class):** 0.53

## Technologies Used
Python, Scikit-Learn, XGBoost, Imbalanced-Learn, Pandas, Matplotlib.
