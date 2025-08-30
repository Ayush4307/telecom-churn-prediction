# telecom-churn-prediction
Machine learning project to predict customer churn in the telecom sector using XGBoost. Includes data preprocessing, feature engineering, model training, and SHAP-based interpretation. Achieves 86% accuracy and enables targeted retention strategies with potential to reduce churn by 15–20%.
# 📊 Telecom Customer Churn Prediction

## 🧠 Overview
This project aims to predict customer churn in the telecom sector using machine learning. By identifying customers at risk of leaving, telecom providers can implement targeted retention strategies that reduce churn and improve profitability.

## 📁 Dataset Description
The dataset contains anonymized customer records with the following features:

- **Demographics**: Age, gender, location  
- **Service Usage**: Call minutes, data usage, plan type  
- **Billing Info**: Monthly charges, payment method, tenure  
- **Customer Support**: Number of support calls, issue types  
- **Target Variable**: Churn (Yes/No)

### Preprocessing Steps
- Handled missing values  
- Normalized numerical features  
- Encoded categorical variables using one-hot encoding  

## 🔍 Methodology

### 1. Exploratory Data Analysis (EDA)
- Identified key churn drivers: high monthly charges, short tenure, frequent support calls  
- Visualized churn distribution across demographics and usage patterns  

### 2. Feature Engineering
- Created new features: tenure buckets, usage-to-charge ratio, support frequency index  
- Applied scaling and encoding for model compatibility  

### 3. Modeling
- Algorithms tested: Logistic Regression, Random Forest, XGBoost  
- Best model: **XGBoost** with  
  - Accuracy: 86%  
  - Precision: 82%  
  - Recall: 78%  
  - ROC-AUC: 0.89  
- Used stratified train-test split and cross-validation  

### 4. Interpretation
- Applied SHAP values to explain model predictions  
- Top predictors: tenure, monthly charges, support frequency  

## 💼 Business Impact
- Enables proactive retention strategies such as personalized offers and service upgrades  
- Simulated churn reduction of **15–20%**  
- Potential for significant cost savings and improved customer lifetime value  
