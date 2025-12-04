Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. Fraud detection is a critical challenge in the financial sector, as fraudulent activities can cause huge financial losses. The goal of this project is to build an efficient model that can accurately distinguish between legitimate and fraudulent transactions.

Data Preprocessing

Handle missing values (if any)

Normalize/scale the Amount feature

Split data into train/test sets

 Handling Imbalanced Data

We apply:

Undersampling
or

Oversampling using SMOTE (Synthetic Minority Oversampling Technique)
to balance the fraud and non-fraud classes.

Model Selection

We use multiple machine learning models:

Logistic Regression

Decision Tree

Random Forest

XGBoost / LightGBM (optional)

Support Vector Machine

Each model is compared using recall and F1-score (since detecting fraud is more important).
 
Evaluation Metrics

Fraud detection is not about accuracy (because the dataset is imbalanced).

Important metrics:

Metric	Why it's important
Recall	Catch as many fraudulent cases as possible
Precision	Reduce false alarms (predicting fraud when it is not)
F1 Score	Balance between precision & recall
