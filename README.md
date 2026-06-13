# Credit Card Fraud Detection using Machine Learning
#  Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques on a highly imbalanced real-world dataset from Kaggle.
The goal is to accurately identify fraud transactions while minimizing false negatives.

#  Dataset Information
- Source: Kaggle Credit Card Fraud Dataset
- Total transactions: 284,807
- Fraud cases: 492 (highly imbalanced ~0.17%)
- Features: PCA-transformed features (V1–V28), Time, Amount
- Target: Class (0 = Normal, 1 = Fraud)
# Workflow
- Data loading and exploration
- Handling class imbalance using undersampling
- Feature scaling (Time, Amount)
- Train-test split
- Model training and evaluation
# Models Used
- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

# Results

Logistic Regression	0.94
XGBoost	0.936
Random Forest	0.928

# Key Insights
- Logistic Regression performed slightly better than complex models due to linear separability in PCA-transformed data.
- XGBoost and Random Forest also performed strongly.
- Class imbalance significantly affects model performance, making evaluation metrics critical.
