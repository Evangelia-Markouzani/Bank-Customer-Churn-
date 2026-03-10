# Bank-Customer-Churn
Bank churn analysis project using exploratory data analysis, visualizations, and predictive modeling to identify at-risk customers and inform retention strategiesOverview

# Overview 
This project analyzes customer churn for a bank. The goal is to understand why customers leave and provide actionable insights to improve retention. The project uses exploratory data analysis (EDA), visualizations, and predictive modeling to identify at-risk customers and inform retention strategies.

# Dataset
Contains customer information such as age, balance, number of products, country, and churn status.
Sensitive or personal data has been anonymized.
Stored in /data

# bank-churn-project/
│
├── data/                       # Raw and cleaned datasets
├── visualizations/             # Python scripts for charts
├── dashboard/                  # Tableau dashboard
├── README.md                   # Project description (this file)
└── LICENSE                     # MIT License

# Tools & Technologies
Python (Pandas, Matplotlib, Seaborn)
Tableau (Dashboard export)
Git & GitHub (Version control)

# Business Problem
Banks lose customers over time, a phenomenon known as churn. High churn reduces revenue and increases costs for acquiring new customers. Predicting which customers are likely to leave allows the bank to take proactive steps to retain them, improve customer satisfaction, and maximize lifetime value.

# Business Questions
Key questions the analysis aims to answer: 
1. What percentage of customers leave the bank?
2. Which age groups churn more?
3. Which country has the highest churn?
4. Does account balance affect churn?
5. Do customers with more products stay longer?

# Bank Churn Analysis – Insights by Business Questions
1. Churn Rate
Observation: Overall churn rate is 20% → meaning 1 in 5 customers leaves the bank.
Implication: There’s a significant retention challenge; strategies to improve loyalty are essential.

2. Age Groups and Churn
Observation: Customers aged 46–55 years are most likely to leave.
Possible Reasons: Economic conditions affecting this segment, or better offers from competitors.

3. Country with Highest Churn
Observation: Germany has the highest churn.
Possible Reasons: Customer dissatisfaction or strong competition in the market.
Implication: Focus retention campaigns and customer engagement strategies specifically in Germany.

4. Account Balance and Churn
Observation: Customers with low account balances are more likely to leave.
Implication: Target low-balance customers with personalized offers or incentives to reduce churn.

5. Product Holding and Churn
Observation: Customers with 2 products are most likely to leave.
Insight: Increasing cross-selling opportunities (encouraging customers to use 3+ products) reduces churn.

# Visualizations
Box plots: Age vs Churn, Balance vs Churn
Bar charts: Country vs Churn, Products vs Churn, Churn Rate
Tableau Dashboard: Interactive visualizations for exploring patterns in churn

# Strategic Recommendations
-Targeted campaigns for at-risk customer segments
-Cross-selling and product engagement strategies
-High-value customer management
-Regional/branch-specific retention initiatives
-Continuous monitoring and model updates

