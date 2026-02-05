# Financial Fraud Detection Using Machine Learning

## Overview
This project focuses on detecting fraudulent financial transactions using machine learning techniques. The dataset contains transaction-level information such as transaction amount, balance details, transaction type, and fraud labels.

## Dataset
The dataset used is a large-scale financial transaction dataset containing millions of records. It includes both legitimate and fraudulent transactions, making it suitable for classification problems with class imbalance.

## Approach
- Performed basic data cleaning and checked for missing values
- Created new features such as balance changes and log-transformed transaction amount
- Removed identifier columns not useful for prediction
- Encoded categorical variables
- Trained a Random Forest classifier with class balancing

## Model Evaluation
The model was evaluated using:
- Precision, Recall, and F1-score
- ROC-AUC score
- Feature importance analysis

## Key Findings
- Transaction amount and balance changes are strong indicators of fraud
- Transfer and cash-out transactions are more likely to be fraudulent
- Class imbalance handling significantly improves fraud detection

## Conclusion
This project demonstrates a practical application of machine learning in financial fraud detection and highlights the importance of feature engineering and evaluation metrics in imbalanced datasets.

## Author
Kartik Ghuge
