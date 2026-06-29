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
This machine learning project aims to predict customer subscriptions to term deposits in a Portuguese bank’s marketing campaign during the period of 2008-2010. The project applies the **CRISP-DM methodology**, imbalance handling techniques, and four classification models to optimise marketing performance while minimising business costs.

## 🔧 Business Problem
Banks invest significant resources into telemarketing campaigns, but only a small percentage of customers subscribe to term deposits.

This project aims to:

- Predict customers likely to subscribe
- Reduce unnecessary marketing costs
- Improve campaign targeting
- Minimise missed revenue opportunities through cost-sensitive modelling


## 🔧 Business Problem
a) Customer Segmentation
- Which demographic factors (age, job, marital status, education) and financial indicators
(balance, default, housing, loan) most strongly predict subscription likelihood?
- Which customer profiles combine high conversion potential with manageable risk?

b) Resource Optimization
- How should marketing budgets and contacts be allocated across segments and channels
(cellular vs. telephone) to maximize ROI?
- Which customer groups offer the highest return per contact or marketing dollar?

c) Campaign Timing and Contact Strategy
- How do timing variables (day of week, economic conditions) influence response rates?
- What is the optimal contact frequency to maximize conversions without causing fatigue?

d) Reach–Precision Balance
- What is the ideal trade-off between broad campaign reach and targeted precision to sustain customer trust and maximize long-term value?


## 📊 Dataset

- **Source:** Portuguese Bank Marketing Dataset (`bank-additional-full.csv`)
- **Records:** 41,188 customer observations
- **Features:** 20 input variables + 1 target variable
- **Target Variable:** `y` (Term Deposit Subscription: Yes/No)
- **Problem Type:** Binary Classification
- **Class Distribution:** Highly imbalanced (~11% positive class)

Data Wrangling and Cleaning
- Converted 

## Models Implemented
Five machine learning models:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbours (kNN)
- Artificial Neural Network (ANN)


