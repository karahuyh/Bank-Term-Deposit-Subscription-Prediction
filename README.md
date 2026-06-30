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

## 🔧 Business Context and Strategic Importance
Term deposits are a key source of stable funding of banks, supporting liquidity, lending and profitability. During the  2008-2019 global financial crisis and eurozone debt crisis, Portuguese banks relied heavily on attracting long-term deposits to strengthen financial stability and meet increased capital requirements. 

## 💼 Business Value of Predictive Modeling
Predictive modeling improves the efficiency of term deposit marketing by identifying customers most likely to subcribe. This helps banks to reduce:
- unnecessary marketing contacts,
- lower operating costs,
- optimize resource allocation,
- personalize customer engagement and
- increase campaign ROI through targeted marketing strategies

## 💰 Business Objectives 
This project aims to:

- Increase campaign ROI by identifying customers with a subscription probability above 30%, aiming for conversion rates of 25–35%.
- Improve marketing efficiency by allocating resources to high-value customer segments, reducing marketing costs by 20–30% while maintaining or improving subscription rates.
- Reduce customer contact fatigue by cutting unnecessary marketing contacts by at least 40%, improving customer relationships and ensuring continued campaign effectiveness.


## 🔧 Business Question
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
### Dataset Overview

- **Source:** Portuguese Bank Marketing Dataset (`bank-additional-full.csv`)
- **Records:** 41,188 customer observations
- **Features:** 20 input variables + 1 target variable (
- **Target Variable:** `y` (Term Deposit Subscription: Yes/No)
- **Problem Type:** Binary Classification
- **Class Distribution:** Highly imbalanced (~11% positive class)

<div align="center">

<img width="450" height="284" alt="Screenshot 2026-06-30 at 4 00 38 PM" src="https://github.com/user-attachments/assets/23b4f070-c3ca-44af-a1d7-941252913788" />

</div>

### 🧹 Dataset Cleaning
#### 📋 Incomplete Data
- Verified the dataset for missing values and confirmed that no incomplete records were present.
- No imputation or row removal was required, allowing all observations to be retained for analysis.

#### ✔️ Inaccurate and Duplicated Data
- Removed duplicate records to maintain data integrity and prevent biased model training.
- Identified and treated outliers using percentile capping (1st–99th percentile) and the IQR method to reduce the influence of extreme values while preserving overall data distribution.
- Validated data types and categorical values to ensure consistency before feature encoding.

### 🔍 Data Analysis
## Models Implemented
Five machine learning models:
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- k-Nearest Neighbours (kNN)
- Artificial Neural Network (ANN)


