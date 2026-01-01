# Financial Fraud Detection using Machine Learning

## Overview
This project builds a machine learning model to detect fraudulent financial transactions using a large-scale transaction dataset.

## Dataset
- 6.3M transactions
- Highly imbalanced fraud data
- Features include transaction amount, type, balances, and time

## Approach
- Data cleaning and feature engineering
- XGBoost classifier
- Calibration and validation split
- Focus on recall and ROC-AUC

## Evaluation Metrics
- Precision, Recall, F1-score
- ROC-AUC
- Confusion Matrix
- Precision-Recall Curve

## Key Insights
- Fraud mostly occurs in TRANSFER and CASH_OUT transactions
- Large amounts and sudden balance drops are strong indicators

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn

## How to Run
1. Clone the repository
2. Install requirements
3. Open the notebook and run all cells
