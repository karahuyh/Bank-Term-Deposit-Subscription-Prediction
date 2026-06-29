<div align="center">

# Bank Term Deposit Subscription Prediction
### Predicting customer subscription likelihood using machine learning and cost-sensitive classification

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-0F766E?style=for-the-badge)
![CRISP-DM](https://img.shields.io/badge/CRISP--DM-455A64?style=for-the-badge)
![SMOTE](https://img.shields.io/badge/SMOTE-0EA5A4?style=for-the-badge)
![Random Forest](https://img.shields.io/badge/Random%20Forest-2E7D32?style=for-the-badge)
![SVM](https://img.shields.io/badge/SVM-7C3AED?style=for-the-badge)

</div>

## 💻 Project Overview
A machine learning project that predicts whether a customer will subscribe to a term deposit during a direct marketing campaign. The project applies the **CRISP-DM methodology**, advanced data preprocessing, imbalance handling techniques, and multiple classification algorithms to optimise marketing performance while minimising business costs.

## 🔧 Business Problem
Banks invest significant resources into telemarketing campaigns, but only a small percentage of customers subscribe to term deposits.

This project aims to:

- Predict customers likely to subscribe
- Reduce unnecessary marketing costs
- Improve campaign targeting
- Minimise missed revenue opportunities through cost-sensitive modelling

## 📊 Dataset

- **Source:** Portuguese Bank Marketing Dataset (`bank-additional-full.csv`)
- **Records:** 41,188 customer observations
- **Features:** 20 input variables + 1 target variable
- **Target Variable:** `y` (Term Deposit Subscription: Yes/No)
- **Problem Type:** Binary Classification
- **Class Distribution:** Highly imbalanced (~11% positive class)

## Models Implemented
Five machine learning models:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbours (kNN)
- Artificial Neural Network (ANN)

