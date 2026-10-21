# Credit Card Fraud Detection (Imbalanced Data)

## Project Overview

This project is part of the Oasis Infobyte Data Analytics Internship (Level 2 - Task 3). The objective is to build a machine learning pipeline to detect fraudulent financial transactions, addressing heavy class imbalance as the core technical challenge.

## Tech Stack

- **Language:** Python
- **Libraries:** pandas, numpy, scikit-learn, imbalanced-learn (SMOTE), matplotlib, seaborn
- **Environment:** Jupyter Notebook (VS Code)

## Workflow & Implementation

- **Exploratory Data Analysis (EDA):** Analyzed the severe class imbalance (frauds representing only 0.17% of the dataset) and mapped transaction time and amount distributions.
- **Class Imbalance Handling:** Applied Synthetic Minority Over-sampling Technique (SMOTE) strictly on the training data to generate synthetic fraud cases, achieving a perfectly balanced 50/50 training set.
- **Model Training:** Trained a baseline Logistic Regression model and an optimized Random Forest Classifier.
- **Evaluation Strategy:** Prioritized Recall and F1-Score over standard accuracy to evaluate the models, recognizing that minimizing False Negatives is critical in fraud detection.
- **Performance:** The Random Forest model achieved a high Recall (0.89) and an excellent ROC-AUC score (0.985), successfully capturing the vast majority of fraudulent transactions.
- **Insights:** Generated a Feature Importance chart identifying V14, V10, and V4 as the primary predictive indicators of fraud, and detailed the scalability requirements for production deployment.
