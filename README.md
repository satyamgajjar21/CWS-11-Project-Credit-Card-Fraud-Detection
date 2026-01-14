# Credit Card Fraud Detection

A machine learning project that detects fraudulent credit card transactions using supervised learning techniques.  
This project focuses on handling imbalanced data, feature analysis, model training, and evaluation for fraud detection problems.

## Table of Contents
1. Overview
2. Problem Statement
3. Dataset Description
4. Features Used
5. Approach
6. Machine Learning Model
7. Handling Imbalanced Data
8. Evaluation Metrics
9. How to Run the Project
10. Results
11. Technologies Used
12. Future Improvements
13. Author

## Overview
Credit card fraud detection is a critical task in the financial domain where the goal is to identify fraudulent transactions accurately while minimizing false positives.

This project builds a machine learning model that classifies transactions as fraudulent or legitimate using historical transaction data.

The notebook demonstrates the complete pipeline from data loading to model evaluation.

## Problem Statement
Given transaction level features, predict whether a credit card transaction is fraudulent or not.

The target variable contains two classes:
0 represents legitimate transactions  
1 represents fraudulent transactions

## Dataset Description
The dataset consists of anonymized credit card transaction records.

Each row represents one transaction  
Each column represents a numerical feature derived from transaction behavior  
The target column indicates fraud status

Due to confidentiality, feature names are anonymized.

## Features Used
The dataset mainly contains numerical features such as:
1. Time related features
2. Transaction amount
3. Principal component transformed variables
4. Class label indicating fraud

All features are numeric and suitable for machine learning models.

## Approach
1. Load and explore the dataset
2. Analyze class imbalance
3. Separate features and target variable
4. Split data into training and testing sets
5. Train a classification model
6. Evaluate model performance
7. Predict fraud on unseen transactions

## Machine Learning Model
This project uses a supervised classification algorithm for fraud detection.

Logistic Regression is used as a baseline model due to its efficiency and interpretability.

The model learns patterns that distinguish fraudulent transactions from normal transactions.

## Handling Imbalanced Data
Fraud detection datasets are highly imbalanced.

This project addresses class imbalance by:
1. Analyzing class distribution
2. Using appropriate evaluation metrics
3. Focusing on recall and precision rather than accuracy alone

Additional techniques such as resampling can be explored for improvement.

## Evaluation Metrics
Model performance is evaluated using:
1. Accuracy score
2. Precision score
3. Recall score
4. F1 score
5. Confusion matrix

These metrics provide better insight into fraud detection performance.

## How to Run the Project
1. Clone the repository to your local machine
2. Ensure Python version 3.8 or higher is installed
3. Open the notebook using Jupyter Notebook or Jupyter Lab
4. Run all cells sequentially

## Results
The trained model is able to identify fraudulent transactions with reasonable performance.

Results depend on data preprocessing, class imbalance handling, and model selection.

## Technologies Used
1. Python
2. NumPy
3. Pandas
4. Scikit learn
5. Matplotlib
6. Seaborn
7. Jupyter Notebook

## Future Improvements
1. Apply advanced models such as Random Forest or XGBoost
2. Use resampling techniques like SMOTE
3. Perform hyperparameter tuning
4. Add anomaly detection methods
5. Improve recall for fraud cases

## Author
Satyam Gajjar
