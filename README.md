# Telecom-Churn-Case-Study
---

## Telecom Customer Churn Prediction

In the highly competitive telecom industry, customer churn presents a significant business challenge, especially in markets like India and Southeast Asia where prepaid services dominate. This project focuses on predicting customer churn for a leading telecom provider by analyzing customer-level usage data over a four-month period.

### 🧠 Problem Statement  
Telecom companies face an average annual churn rate of 15–25%, and retaining high-value customers—who contribute to nearly 80% of revenue—is far more cost-effective than acquiring new ones. The goal of this project is to build predictive models to:
- Identify high-value customers at risk of churn.
- Determine the key indicators driving churn behavior.

### 📊 Data Overview  
- Data spans four months: June (6), July (7), August (8), and September (9).
- We define churn using a **usage-based** approach: customers with **zero incoming/outgoing activity and no internet usage** in the churn month.
- High-value customers are filtered based on the 70th percentile of recharge amounts in the "good" phase (months 6 & 7).

### 🔍 Approach  
1. **Data Preprocessing & Feature Engineering**: Cleaning, handling missing values, deriving key features.
2. **High-Value Customer Segmentation**: Focused modeling on customers with high recharge activity.
3. **Churn Tagging & Dimensionality Reduction**: Tagging churners and applying PCA for dimensionality reduction.
4. **Model Building**: Classification models trained with techniques to address class imbalance.
5. **Interpretability & Feature Importance**: Building additional interpretable models (e.g., logistic regression, tree-based) to identify key churn indicators.

### 📈 Business Value  
By accurately predicting churn and uncovering behavioral patterns, telecom companies can take proactive steps—such as offering personalized incentives—to reduce churn and improve customer retention.

---
