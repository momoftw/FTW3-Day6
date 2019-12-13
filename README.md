# FTW3 Day6: Advanced Classification Techniques

## Problem: 
Predict Census data if income is above or below 50k.
 
## Data Treatment
- Dummified income, workclass, education level, marital status, occupation, relationship, race, sex, and native country
- log-transformed capital gain and loss

## XGBoost Classifier
- Accuracy: 0.79
- Precision: 0.79
- Recall: 0.60

## XGBoost with Generation of Synthetic Samples using SMOTE
- Accuracy: 0.87
- Precision: 0.84
- Recall: 0.91

## XGBoost with Generation of Synthetic Samples using SMOTE and Principal Component Analysis
- Accuracy: 0.88
- Precision: 0.88
- Recall: 0.88

## XGBoost with Generation of Synthetic Samples using SMOTE and Principal Component Analysis + Hyperparameter Optimization using AUC
- Accuracy: 0.90
- Precision: 0.89
- Recall: 0.91
