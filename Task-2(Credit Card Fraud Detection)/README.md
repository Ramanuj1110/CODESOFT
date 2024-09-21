# Fraudulent Credit Card Transactions Detection 💳
Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset contains transaction data, including features such as transaction amount, time, and others (V1 to V28). The goal is to classify transactions as either fraudulent or genuine, addressing class imbalance and evaluating model performance using appropriate metrics.

Author : 
Ramanuj Kumar

Batch : 
Sep-Oct

Domain : 
Data Science

Dataset

The dataset used for this project consists of credit card transaction records. Key features include:

    Time: Time elapsed from the first transaction in the dataset
    V1-V28: Principal component analysis (PCA) transformed features
    Amount: Transaction amount
    Class: Target variable indicating whether the transaction is fraudulent (1) or genuine (0)

Project Steps

    Data Loading: Load the credit card transaction dataset and inspect its structure.
    Data Preprocessing:
        Handle missing values, outliers, and duplicate records.
        Normalize numerical features like Amount to prepare for model training.
        Split the data into training and testing sets.
    Exploratory Data Analysis (EDA): Visualize and analyze the distribution of data, identify patterns, and check for any significant differences between fraudulent and genuine transactions.
    Handling Class Imbalance:
        Apply techniques such as oversampling (SMOTE) or undersampling to balance the dataset, as fraudulent transactions are rare.
    Model Selection and Training:
        Train machine learning models such as Random Forest, Logistic Regression, and others to classify transactions.
        Implement cross-validation to ensure model robustness.
    Model Evaluation:
        Evaluate models using metrics like accuracy, precision, recall, F1-score, and ROC AUC.
        Assess the impact of false positives and false negatives on the detection system.

Tools and Libraries Used

    Pandas: For data cleaning and manipulation
    NumPy: For numerical computations
    Matplotlib and Seaborn: For data visualization
    Scikit-learn: For machine learning and model evaluation
    Imbalanced-learn: For handling imbalanced datasets (oversampling/undersampling)

Key Insights

    Class imbalance is a critical issue when dealing with fraudulent transactions, requiring specialized handling techniques.
    Features like Amount and the PCA-transformed components play a significant role in distinguishing fraudulent from genuine transactions.
    The choice of metrics, especially precision and recall, is vital to minimize the cost of false negatives and false positives.

Conclusion

The project successfully classifies fraudulent credit card transactions using machine learning. By preprocessing data, addressing class imbalance, and evaluating multiple models, this project provides a comprehensive approach to fraud detection.
