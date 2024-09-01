
## Fraud Detection Using Multi-Algorithm Approach

# Overview

This project is an extensive analysis of various machine learning algorithms applied to fraud detection. The goal is to identify the most effective model for detecting fraudulent activities in financial transactions. The study uses a combination of real and synthetic data to ensure robust model validation, with a focus on preventing overfitting and improving generalization.

# Key Features

Multi-Algorithm Comparison: Evaluation of eight different machine learning models, including LightGBM, CatBoost, AdaBoost, Logistic Regression, Naive Bayes, Ridge Classifier, Linear Discriminant Analysis (LDA), and Quadratic Discriminant Analysis (QDA).
Data Validation: The models were trained and validated using both real and synthetic datasets, with an additional test on an unseen dataset comprising 1,000 fraud cases and 5,000 non-fraud cases.
Performance Metrics: The project evaluates models based on accuracy, F1 score, and cross-validation results, providing a comprehensive performance overview.
Top Performers: LightGBM and CatBoost emerged as the best-performing models, with near-perfect accuracy and generalization capabilities.

# Usage
Data Preparation: Load the dataset from the data/ directory and preprocess it using the provided notebooks.
Model Training: Use the notebooks/ directory to run different models and evaluate their performance.
Model Evaluation: Review the results/ directory for detailed metrics and visualizations comparing the models.
Deploying Models: The top-performing models are saved in the models/ directory and can be deployed as needed.

# Results
LightGBM:
Train Accuracy: 99.99%
Test Accuracy: 99.46%
F1 Score: 99.46%
CatBoost:
Train Accuracy: 99.81%
Test Accuracy: 99.22%
F1 Score: 99.22%
AdaBoost:
Train Accuracy: 98.28%
Test Accuracy: 98.09%
F1 Score: 98.03%
Logistic Regression:
Train Accuracy: 96.43%
Test Accuracy: 96.56%
F1 Score: 96.08%

# Contributing
Contributions are welcome! Please open an issue or submit a pull request with your suggestions or improvements.

# Liscence
All rights reserved. - Vamika Mendiratta
