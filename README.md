# E-Commerce Customer Purchase Prediction Using Logistic Regression

## Project Overview

This project focuses on predicting whether an e-commerce customer is likely to make a purchase based on their browsing activity, shopping behavior, customer information, and engagement patterns.

The project uses **Logistic Regression**, a supervised machine learning algorithm, to perform binary classification and predict customer purchase decisions.

## Project Objectives

- Analyze customer shopping behavior through Exploratory Data Analysis (EDA).
- Identify patterns and factors influencing purchase decisions.
- Handle missing values and outliers.
- Perform categorical encoding and feature scaling.
- Build a Logistic Regression classification model.
- Evaluate model performance using standard classification metrics.
- Predict purchase decisions for new customer records.

## Dataset Information

- Dataset: `Ecommerce_Purchase_Prediction_DataSet.csv`
- Total Records: 10,000
- Total Columns: 19
- Target Variable: `Purchase`

The dataset contains customer demographics, browsing behavior, shopping activity, and engagement information.

### Target Variable

| Value | Meaning |
|---|---|
| 0 | No Purchase |
| 1 | Purchase |

## Technologies and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Machine Learning Workflow

### 1. Exploratory Data Analysis
- Dataset inspection
- Statistical analysis
- Purchase distribution analysis
- Feature relationship visualization
- Missing-value analysis

### 2. Data Preprocessing
- Missing-value imputation
- Outlier handling
- Categorical feature encoding
- Numerical feature scaling

### 3. Model Development

**Algorithm:** Logistic Regression

The model is trained using an 80:20 train-test split with stratified sampling to maintain the target class distribution.

A Scikit-learn Pipeline is used to combine preprocessing and model training while preventing data leakage.

### 4. Model Evaluation

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

## Model Performance

| Evaluation Metric | Score |
|---|---:|
| Accuracy | 70.35% |
| Precision | 72.60% |
| Recall | 87.11% |
| F1-Score | 79.20% |
| ROC-AUC | 0.7400 |

These results represent the current
