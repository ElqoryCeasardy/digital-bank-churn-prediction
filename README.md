📌 Digital Bank Customer Churn Prediction
📖 Project Overview

This project focuses on predicting customer churn in digital banking using machine learning.
Customer churn (when clients stop using the service) is a critical issue for banks, since acquiring new customers is much more expensive than retaining existing ones.

Through this project, I analyzed 10,000+ customer records to identify the main factors driving churn and built predictive models to support customer retention strategies.

⚙️ Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Machine Learning Models: Logistic Regression, Random Forest, LightGBM, XGBoost, HistGradientBoosting

Evaluation Metrics: ROC-AUC, PR-AUC, Recall@Top-10% (chosen due to imbalanced dataset)

🔍 Exploratory Data Analysis (EDA) – Key Insights

Product Usage: Customers with 3–4 products showed the highest churn risk.

Gender: Female customers churned more often (25%) compared to males (16%).

Geography: Customers in Germany had the highest churn rate (~33%, nearly 2× France/Spain).

Age: Older customers (45+) were more likely to churn.

Engagement: Inactive members with high balances are particularly at risk.

🤖 Model Performance

The best performing model was HistGradientBoosting with:

ROC-AUC ≈ 0.86

PR-AUC ≈ 0.70

Recall@Top-10% ≈ 0.82

👉 This means the model successfully identified the majority of high-risk customers within the top 10% scoring segment.

💡 Business Recommendations

High-Risk Customers (p ≥ 0.20)

Proactive RM calls within 48 hours

Fee waiver / product simplification

Reactivation campaigns & autopay reminders

Medium-Risk Customers (0.10 ≤ p < 0.20)

Digital nudges (in-app, WhatsApp, email)

Product education & light incentives

Low-Risk Customers (p < 0.10)

Loyalty programs & referral bonuses

Cross-sell opportunities
