# 💳 Task 4 - Credit Card Fraud Detection

## 📌 Project Overview
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques.

The goal is to build a classification model that can accurately identify whether a transaction is fraudulent or legitimate.

## 🎯 Objective
- Perform data preprocessing and cleaning
- Handle imbalanced dataset
- Conduct Exploratory Data Analysis (EDA)
- Train and evaluate classification models
- Improve fraud detection accuracy

## 📊 Dataset Description
The dataset contains transaction details including:
- Transaction amount
- Time
- PCA-transformed features (V1, V2, V3, …)
- Class (0 = Legitimate, 1 = Fraud)

The dataset is highly imbalanced, with very few fraudulent transactions.

## 🔍 Steps Performed
- Loaded dataset using Pandas
- Checked for missing values
- Analyzed class imbalance
- Performed data visualization
- Applied resampling techniques (if used)
- Split dataset into training and testing sets
- Trained classification models
- Evaluated model performance

## 🤖 Machine Learning Algorithms Used
- Logistic Regression
- Random Forest Classifier
- Decision Tree Classifier

## 📈 Model Evaluation Metrics
Due to class imbalance, the following metrics were used:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 🚀 Outcome
Successfully developed a machine learning model capable of detecting fraudulent transactions with high precision and recall.
