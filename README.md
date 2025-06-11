# customer-churn-analysis
Jupyter Notebook project exploring factors that influence customer churn using Python and machine learning.
Customer Churn Analysis

Author: Shakirah Benson

This project explores key drivers of customer churn on an e-commerce platform. Using Python and machine learning, the analysis identifies which customer behaviors are most correlated with churn, segments users into actionable groups, and builds a predictive model to support retention strategies.

---

Objectives

- Analyze churn trends based on behavioral and satisfaction metrics
- Visualize key relationships between tenure, order count, satisfaction, and churn
- Identify at-risk and high-value customer segments
- Predict churn using a Random Forest Classifier
- Calculate and rank Customer Lifetime Value (CLV) for strategic targeting

---

## Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset) and includes customer information such as:

- Tenure  
- Order count  
- Satisfaction scores  
- Preferred payment method  
- Churn status  

---

## Tools & Techniques

- **Python**: pandas, matplotlib, seaborn, scikit-learn
- **Data Cleaning**: Imputation, type conversion, normalization
- **EDA**: Correlation analysis, boxplots, histograms, bar charts
- **Modeling**: K-Means clustering, Random Forest classification
- **Customer Lifetime Value (CLV)**: Derived from cashback × churn probability

---

## Key Insights

- Customers with fewer than 5 orders and low satisfaction scores are the most likely to churn.
- Complaints strongly correlate with churn, suggesting a need for better support resolution.
- Segment 2 (high-tenure, high-satisfaction, high-order customers) has the highest CLV and should be prioritized.
- The Random Forest model achieved **86% accuracy**, supporting use as an early warning system.

---

## Next Steps

- Tune the classifier to improve recall for churned customers.
- Incorporate additional features like browsing behavior or support interaction.
- Test A/B retention strategies on churn-risk segments.
- Build a real-time dashboard to track churn drivers and CLV trends.

---

## Files Included

- `ChurnAnalysis.ipynb`: Main notebook containing code, visualizations, and modeling
- `README.md`: Project overview and summary
---

## Contact
Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/shakirahbenson) or email at sbaneesa@gmail.com.
