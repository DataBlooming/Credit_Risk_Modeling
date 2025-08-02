# Risk Modeling Python Modules

This repository contains a set of Python modules focused on different aspects of risk management, primarily in credit risk and fraud detection. The code demonstrates practical implementations of machine learning models and data analysis techniques applied to real-world financial risk scenarios, aiming to support data-driven decision making.

---

## Modules Overview

### 1. `credit_risk_modeling_ml.ipynb`  
This module covers the full pipeline for credit risk modeling using machine learning techniques such as ensemble learning, including Logistic Regression, XGBoost, Random Forest, and Voting Classifier. It includes data preprocessing, feature engineering, model training, and evaluation. The models aim to predict the creditworthiness of clients and assist in lending decision-making.

### 2. `fraud_detection_bank_transactions_ml.ipynb`  
This module implements machine learning models such as KMeans and DBSCAN (Density-Based Spatial Clustering of Applications with Noise) to detect fraudulent activities in bank transactions. It includes feature extraction from transaction data, model training, and performance evaluation specifically tailored for unlabeled data in the banking domain.

### 3. `fraud_detection_online_payment_ml.ipynb`  
Focused on online payment fraud detection, this module applies machine learning methods such as XGBoost and Random Forest to identify suspicious transactions in e-commerce and payment platforms. It handles imbalanced data and utilizes advanced classification techniques for improved accuracy.

### 4. `fraud_user_profile_analysis_stat.ipynb`  
This module performs exploratory and statistical analysis of user profiles to identify potential fraud patterns. It leverages unsupervised learning and behavioral analytics to detect anomalies in user behavior that may indicate fraudulent intent.

---

## Project Structure
---

## Project Structure
/Risk_Modeling <br>
│ <br>
├── credit_risk_modeling_ml.ipynb <br>
├── fraud_detection_bank_transactions_ml.ipynb <br>
├── fraud_detection_online_payment_ml.ipynb <br>
└── fraud_user_profile_analysis_stat.ipynb

## Requirements

- Python 3.9+  
- Common libraries: `pandas`, `numpy`, `scikit-learn`, `xgboost`, `matplotlib`

Please make sure these libraries are installed before running the code.
