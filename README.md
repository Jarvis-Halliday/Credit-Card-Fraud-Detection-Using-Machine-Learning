**Credit Card Fraud Detection Using Machine Learning
Overview**

This project focuses on detecting fraudulent credit card transactions using Machine Learning. The objective is to build a classification model that can distinguish between legitimate and fraudulent transactions based on historical transaction data.

The project involves data preprocessing, handling class imbalance, model training, and performance evaluation using Logistic Regression.

**Problem Statement**

Credit card fraud is a major challenge for financial institutions, resulting in significant financial losses each year. Since fraudulent transactions represent a very small percentage of total transactions, detecting them accurately is a challenging classification problem.

This project aims to develop a machine learning model capable of identifying potentially fraudulent transactions while maintaining high prediction accuracy.

**Dataset**

Dataset Link : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?resource=download

The dataset contains anonymized credit card transaction records, including:


Transaction features (V1–V28)

Transaction Amount

Class Label

0 = Legitimate Transaction
1 = Fraudulent Transaction

The dataset is highly imbalanced, with fraudulent transactions representing only a small fraction of total transactions.

**Tools & Technologies**

Python, 
Pandas, 
NumPy, 
Scikit-Learn,
Matplotlib, 
Google Colab,

**Project Workflow**

**1. Data Collection & Loading**

Imported transaction dataset using Pandas. 

Explored dataset structure and data types.

**2. Data Analysis**

Examined distribution of legitimate and fraudulent transactions.

Identified class imbalance within the dataset.

**3. Data Preprocessing**

Checked for missing values.

Created a balanced dataset using undersampling techniques.

Prepared data for machine learning model training.

**4. Model Development**

Split data into training and testing datasets.

Implemented Logistic Regression for fraud classification.

**5. Model Evaluation**

Evaluated model performance on training and testing datasets.

Measured prediction accuracy to assess model effectiveness.

**Results**

Metric	Score :
Training Accuracy	94%, 
Testing Accuracy	93%

The model demonstrated strong performance with consistent accuracy on both training and testing datasets, indicating good generalization capability.

**Key Learnings**

Handling imbalanced datasets using undersampling techniques.

Data preprocessing and feature preparation.

Building classification models using Logistic Regression.

Evaluating machine learning models using train-test validation.

Applying machine learning techniques for fraud detection problems.
