# Telco Customer Churn Analysis

## Background
Customer churn is the rate at which customers stop doing business with a company. High churn results in revenue loss and increased marketing expenses to acquire new customers.

## Business Problem
The telecom company is experiencing a significant number of customers terminating their services. Management needs to identify the main drivers of churn to implement targeted retention strategies.

## Goal
1. Identify main/key factors contributing to customer churn.  
2. Recommend actionable strategies to reduce future churn.

## Expected Outcome
1. Top churn predictors or attributes.  
2. Visual insights showing churn trends based on various features.  
3. Recommendations for reducing churn in high-risk customer segments.

## Dataset
- Telco Customer Churn Dataset on Kaggle
- Target variable: `Churn` (Yes/No)  
- Features include:  
  - Customer demographics (customer ID, gender, senior citizen, partner, dependents)  
  - Account details (tenure, multiple lines, online security, online backup, device protection, contract, paperless billing, payment method)  
  - Services subscribed (phone service, internet service, tech support, streaming TV, streaming Movies)  
  - Charges (monthly charges, total charges)  

## Tools & Libraries
- **Python**  
- **Jupyter Notebook**  
- Libraries: `pandas`,  `matplotlib`, `seaborn`, `scikit-learn`  

## Key Insights
- Customer churn is highest among **new users within the first 15 months of joining**.
- Customers who **pay high monthly charges and have short term contracts** are at the highest risk of churning.
- Customers with **longer tenure** tend to stay.  
- Customers with **Fiber Optics service** have chured a lot.
- Customers with **no tech support** have also resulted in high churn.
- Customers with **payment method of Electronic check** have high churn rate.
- Customers who **do not have dependents** have churned high.
- Dataset has **imbalanced Churn class**.

## Machine Learning Models Used
- Logistic Regression  
- SVC Classifier  
- XGBoost Classifier
- Random Forest Classifier

📈 **Best Model:** *(Random Forest with 77% accuracy)*  

## Business Recommendations
- **Enhance onboarding** of new customers and **provide early incentives** to increase retention during first few months.
- Offer **discounts or vouchers** to customers with high monthly charges.
