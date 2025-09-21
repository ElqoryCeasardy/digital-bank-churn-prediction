# 📌 Digital Bank Customer Churn Prediction

This project analyzes customer churn in digital banking using machine learning.  
The goal is to identify key factors influencing churn and provide business recommendations.

---

## 📖 Project Overview
- Dataset: Digital Bank Customers (10,000+ rows, 13 features)  
- Target: `Exited` (1 = churn, 0 = retained)  
- Industry Context: High churn impacts retention costs and profitability  

---

## ❓ Problem Statement
Customer churn is costly for digital banks because acquiring new customers is far more expensive than retaining existing ones.  
This project aims to:
- Identify main churn drivers  
- Build predictive models  
- Provide actionable retention strategies  

---

## 🔍 Key Insights
- Customers with **3–4 products** = higher churn  
- **Female churn rate** higher (25% vs 16% male)  
- **Germany** = highest churn risk (33%)  
- Older customers (**45+**) churn more  
- Inactive + high balance = most risky segment  

---

## 🤖 Model Performance
- **Best Model**: HistGradientBoosting  
- **ROC-AUC**: 0.86  
- **PR-AUC**: 0.70  
- **Recall@Top-10%**: 0.82  

---

## 💡 Business Recommendations
- High-Risk → RM call ≤48h, fee waiver, reactivation, product simplification  
- Medium-Risk → digital nudges, education, light incentives  
- Low-Risk → loyalty & referral program  

---
