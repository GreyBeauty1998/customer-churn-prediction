# 📉 Customer Churn Prediction – Telecom Industry

This project explores how machine learning can be applied to predict customer churn for a telecom company using a real-world dataset. It walks through data cleaning, preprocessing, model building, evaluation, and key insights generation.

---

## 🔍 Project Overview

- **Objective**: Predict which customers are likely to cancel their service (churn)
- **Dataset**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **ML Models Used**: Logistic Regression, Random Forest
- **Tools**: Python, pandas, scikit-learn, Google Colab

---

## 📊 Business Problem

Churn is a critical problem in the subscription business model. Accurately identifying at-risk customers allows telecom companies to take proactive retention measures. This project aims to build a reliable churn prediction system based on customer demographics and service usage patterns.

---

## ⚙️ Workflow Summary

1. **Data Cleaning**: Handled missing values, corrected data types (e.g., 'TotalCharges' from text to float), dropped irrelevant columns  
2. **Data Encoding**: Used one-hot encoding for all categorical variables  
3. **Model Training**:
   - Logistic Regression (Baseline)
   - Random Forest Classifier (Improved generalization)
4. **Evaluation Metrics**:
   - Accuracy
   - Precision/Recall/F1-score
   - Confusion Matrix

---

## 🧠 Results

- **Best Accuracy**: ~78.7%
- **Logistic Regression**: High precision for non-churn, moderate recall for churn
- **Random Forest**: Slight improvement in prediction balance, better fit for complex interactions

---

## 📁 Project Structure

