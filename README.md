# FraudDetection
Comparing multiple algorithms for performance against credit card transaction data

## Overview
This project focuses on detecting fraudulent credit card transactions using machine learning models. The dataset used is highly imbalanced, with fraudulent transactions accounting for only 0.172% of the total transactions. Various techniques, including oversampling methods and cross-validation strategies, are employed to address the class imbalance and improve model performance.

## Features
- Exploratory Data Analysis (EDA) to understand the dataset.
- Implementation of multiple machine learning models:
  - Logistic Regression (L1 and L2 Regularization)
  - K-Nearest Neighbors (KNN)
  - Decision Trees
  - Random Forest
  - XGBoost
  - Support Vector Machines (SVM)
- Handling class imbalance using:
  - Random Oversampling
  - SMOTE Oversampling
  - ADASYN Oversampling
- Cross-validation techniques:
  - RepeatedKFold
  - StratifiedKFold
- Hyperparameter tuning for optimal model performance.

## Dataset
The dataset includes credit card transactions made by European cardholders over two days in September 2013. It contains the following features:
- **Time**: Seconds elapsed between the first transaction and subsequent transactions.
- **Amount**: Transaction amount.
- **Class**: Target variable (1 for fraud, 0 for non-fraud).
- **V1 to V28**: Principal components obtained using PCA to ensure confidentiality.

## How to Run
1. Clone this repository to your local machine.
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt