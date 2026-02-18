💳 Credit Card Fraud Detection Using Machine Learning

📌 Project Overview

- Credit Card Fraud Detection is a machine learning project that aims to identify fraudulent credit card transactions from genuine ones.
Due to the highly imbalanced nature of fraud data, this project focuses on data preprocessing, handling class imbalance, and model evaluation using appropriate metrics.

- The model helps financial institutions reduce losses by detecting fraudulent transactions in real time.

🎯 Objective

- Analyze credit card transaction data

- Preprocess and normalize numerical features

- Handle severe class imbalance

- Train classification models to detect fraud

- Evaluate model performance using precision, recall, and F1-score

📁 Dataset

Credit Card Transactions Dataset

Target Variable:

- Class

- 0 → Genuine transaction

- 1 → Fraudulent transaction

Features:

- V1 to V28 – PCA-transformed features

- Amount – Transaction amount

⚠️ The dataset is highly imbalanced, with fraud cases forming a very small percentage of total transactions.

🛠️ Technologies & Tools

- Python

- Pandas & NumPy – Data manipulation

- Matplotlib & Seaborn – Data visualization

- Scikit-learn – Machine learning models & evaluation

- Imbalanced-learn (SMOTE) – Handling class imbalance

🔄 Project Workflow

- Data Loading

- Exploratory Data Analysis (EDA)

- Feature Scaling

- Handling Class Imbalance

- Train-Test Split

- Model Training

- Model Evaluation

- Result Analysis

🧹 Data Preprocessing

- Standardization of transaction Amount

- Stratified train-test split

- Oversampling using SMOTE to balance fraud and non-fraud classes

🤖 Machine Learning Models Used

- Logistic Regression

- Random Forest Classifier

These models were chosen to compare linear and ensemble-based classification approaches.

📊 Evaluation Metrics

Due to class imbalance, accuracy alone is not sufficient. The following metrics are used:

- Precision – Correctly predicted frauds out of total predicted frauds

- Recall – Correctly detected frauds out of actual frauds

- F1-Score – Balance between precision and recall

- Confusion Matrix – Visual performance analysis

🔑 Recall is especially important to minimize missed fraudulent transactions.
