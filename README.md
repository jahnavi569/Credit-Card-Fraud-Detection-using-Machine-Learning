#  Credit Card Fraud Detection using Machine Learning
##  Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques on a highly imbalanced real-world dataset from Kaggle.
The goal is to accurately identify fraudulent transactions while minimizing false negatives, which is critical in financial fraud detection systems.

##  Dataset Information
- Source: Kaggle Credit Card Fraud Dataset  
- Total Transactions: 284,807  
- Fraud Cases: 492 (~0.17%)  
- Features: PCA-transformed features (V1–V28), Time, Amount  
- Target Variable:  
  - `0` → Normal Transaction  
  - `1` → Fraudulent Transaction  

##  Workflow
- Data loading and exploration  
- Handling class imbalance using undersampling  
- Feature scaling (Time and Amount)  
- Train-test split  
- Model training and evaluation  
- Performance comparison of models  

##  Models Used
- Logistic Regression  
- Random Forest Classifier  
- XGBoost Classifier  

##  Results

 Model                ROC-AUC Score 
-----------------------------------  
 Logistic Regression  0.9829         
 Random Forest        0.9846         
 XGBoost              0.9851          

##  Observations
- XGBoost achieved the best performance with the highest ROC-AUC score (0.9851).
- Random Forest also performed very closely to XGBoost.
- Logistic Regression showed strong performance despite being a simple linear model.
- All models performed well due to effective preprocessing and handling of class imbalance.

##  Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib / Seaborn  
