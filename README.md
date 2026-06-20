# Telco-Customer-Churn-Analysis
Telco Customer Churn Analysis

Executive Summary

This project performs an end-to-end exploratory data analysis (EDA) of the Telco Customer Churn dataset to identify the key factors influencing customer attrition. The dataset consists of 7,043 customer records and 21 variables covering customer demographics, account information, subscribed services, billing characteristics, and churn status. Data preprocessing involved handling missing values, converting the TotalCharges field to a numeric format, and validating data quality to ensure reliable analysis.

The analysis reveals that 1,869 out of 7,043 customers (26.54%) have churned, while 5,174 customers (73.46%) were retained, indicating that approximately one out of every four customers leaves the company. This churn rate highlights a significant opportunity for customer retention initiatives.

Demographic analysis shows that gender has a negligible impact on churn behavior, with male and female customers exhibiting nearly identical churn patterns. However, senior citizens display a notably higher churn tendency. Customers without partners and dependents are also more likely to discontinue services compared to those with family commitments, suggesting that customers with stronger household ties tend to remain with the company longer.

Contract type emerged as the most influential churn driver. Customers on month-to-month contracts account for the overwhelming majority of churn cases, while those on one-year and two-year contracts demonstrate significantly stronger retention. The visualizations clearly indicate that long-term contractual commitments substantially reduce customer attrition, making contract tenure one of the strongest predictors of customer loyalty.

Service-related features provide further insight into customer behavior. Customers using fiber optic internet services experience the highest churn levels, despite being one of the company's premium offerings. In contrast, customers who subscribe to additional services such as Online Security, Tech Support, Online Backup, and Device Protection exhibit significantly lower churn rates. Customers lacking these value-added services consistently show higher churn proportions, suggesting that deeper product adoption strengthens customer retention.

Billing and payment analysis highlights meaningful differences across payment methods. Customers paying through electronic checks exhibit the highest churn levels, whereas customers using automatic payment methods such as bank transfers and credit card payments demonstrate greater loyalty. Additionally, customers enrolled in paperless billing show higher churn rates, indicating a potential association between digital billing preferences and customer attrition.

Tenure analysis indicates a strong inverse relationship between customer lifespan and churn probability. Customers with shorter tenures are considerably more likely to churn, while long-tenured customers display substantially higher retention. This finding suggests that the early stages of the customer lifecycle represent the highest-risk period and should be the primary focus of retention campaigns.

The visualizations created throughout the analysis—including pie charts, count plots with churn segmentation, tenure distributions, and service-based churn comparisons—collectively demonstrate that churn is primarily driven by contract type, service adoption, internet service category, payment behavior, and customer tenure, rather than demographic characteristics such as gender.

Based on these findings, the company should prioritize retention efforts toward:

Month-to-month contract customers.
Fiber optic internet subscribers.
Customers without Online Security, Tech Support, Online Backup, or Device Protection services.
Customers using electronic check payment methods.
Newly acquired and low-tenure customers.

Encouraging long-term contracts, increasing adoption of value-added services, promoting automatic payment methods, and implementing targeted onboarding programs for new customers can significantly reduce churn and improve overall customer lifetime value. This analysis provides actionable insights that can support data-driven customer retention strategies and enhance business profitability.
