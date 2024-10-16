# credit-card-fraud-detection
# Credit Card Fraud Detection

## Overview
This project aims to develop a machine learning model that detects fraudulent credit card transactions. By analyzing transaction data, the model predicts whether a transaction is legitimate or fraudulent, helping financial institutions mitigate risks associated with fraud.

## Dataset
The dataset used in this project contains credit card transactions, which have been split into 23 parts for easier handling. Each part includes the following columns:
- **id**: Unique identifier for each transaction.
- **V1 - V28**: Anonymized features representing various transaction attributes.
- **Amount**: The transaction amount.
- **Class**: Binary label indicating whether the transaction is fraudulent (1) or not (0).

##Models Used
-Logistic Regression: A baseline model for predicting fraud.
-Random Forest: An ensemble method that improves prediction accuracy.

##Results
The Random Forest Classifier achieved an accuracy of 100% on the test set, with excellent precision, recall, and F1-score. The confusion matrix indicates that the model effectively identifies fraudulent transactions without misclassifying legitimate ones.

##Acknowledgments
Special thanks to Kaggle for providing the dataset.
Thanks to the scikit-learn and XGBoost libraries for their robust machine learning algorithms.
