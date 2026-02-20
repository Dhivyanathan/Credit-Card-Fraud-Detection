💳 Credit Card Fraud Detection using Machine Learning
📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. The dataset is highly imbalanced, with fraudulent transactions representing less than 1% of total records.

The goal is to build a classification model that prioritizes detecting fraud while managing false positives effectively.

📊 Dataset Description

Features: PCA-transformed transaction features (V1–V28)

Additional Features:

Time

Amount

Target Variable:

Class (0 = Genuine, 1 = Fraud)

Fraud cases are extremely rare, creating a class imbalance challenge.

🛠 Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

Imbalanced-learn (SMOTE)

🔍 Project Workflow
1️⃣ Data Exploration

Analyzed class distribution

Identified severe class imbalance

Scaled transaction amount

2️⃣ Data Preparation

Stratified train-test split

Feature scaling using StandardScaler

Applied SMOTE to balance training data

3️⃣ Model Training

Implemented:

Logistic Regression

Random Forest Classifier

4️⃣ Model Evaluation

Metrics used:

Precision

Recall

F1-Score

Confusion Matrix

📊 Results

Achieved high Recall (~91%), ensuring most fraud cases were detected

Observed trade-off between precision and recall

Explored threshold tuning strategies to reduce false positives

⚖️ Business Interpretation

In fraud detection:

False Negatives = Financial Loss

False Positives = Customer Inconvenience

The model was optimized to prioritize fraud detection while exploring strategies to balance alert precision.

🚀 Future Improvements

ROC-AUC & Precision-Recall curve analysis

Threshold optimization

Hyperparameter tuning

XGBoost implementation

Anomaly detection models

Deployment using Streamlit
