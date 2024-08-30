# Customer Churn Analysis for E-commerce Businesses

## Executive Summary
This report presents a comprehensive analysis of customer churn for e-commerce businesses, using the Kaggle Customer Churn dataset. The project involved cleaning and preprocessing the data in Python, followed by an in-depth exploration of the key factors influencing customer churn. Pandas was utilized for statistical analysis, while Plotly was employed to create interactive visualizations of the data.

**Key Insights:**
1. Higher churn rates were observed among customer segments preferring cash on delivery, mobile category users, and customers from higher city tiers.
2. High satisfaction scores did not necessarily prevent churn.
3. Increased customer complaints were strongly correlated with higher churn rates.

**Recommendations:**
1. Implement tailored retention strategies for each high-risk customer group.
2. Conduct a thorough review of the feedback system to address underlying issues.
3. Prioritize effective complaint management to reduce churn.

## Business Problem
For e-commerce businesses, customer retention is crucial, as retaining existing customers is often more cost-effective than acquiring new ones. High churn rates can negatively impact revenue, growth, and long-term profitability. Despite various efforts to engage customers, a significant number of them still choose to leave.

**Challenge:**
Identify the specific customer segments most at risk of churn and determine the underlying reasons for their departure. By addressing these concerns, e-commerce businesses can implement effective interventions to reduce churn rates, increase customer lifetime value, and enhance overall business performance.

## Methodology

1. **Data Cleaning:**
   The process began with extracting the raw dataset from Kaggle. Key cleaning steps included handling duplicate rows, addressing missing values, and dropping unnecessary columns to ensure the dataset was relevant.

2. **Data Preprocessing:**
   This step involved grouping the columns into three categories: float, object, and ordinal, followed by removing data inconsistencies.

3. **Exploratory Data Analysis (EDA):**
   Overall churn distribution was analyzed, followed by an examination of churn distribution against each column of the three categories created during preprocessing. Interactive plots with Plotly were created to visualize key attributes affecting customer churn and gain insights into customer behavior.

## Results

1. **Churn Distribution Insights:**
   Significant variations in churn rates were observed across different customer segments. Customers preferring cash on delivery, mobile device users, and those from higher city tiers exhibited higher churn rates compared to other groups.

2. **Satisfaction Scores vs. Churn:**
   Contrary to expectations, high satisfaction scores did not correlate with lower churn rates, indicating that satisfaction alone does not necessarily prevent customers from leaving.

3. **Complaint Correlation:**
   An increase in customer complaints was strongly associated with higher churn rates, suggesting that unresolved issues and dissatisfaction play a critical role in customer attrition.

## Business Recommendations

1. **Tailored Retention Strategies:**
   Develop and implement retention strategies specifically designed for high-risk customer segments, such as those preferring cash on delivery, mobile users, and customers from higher city tiers. Personalized offers, targeted communication, and loyalty programs could help reduce churn within these groups.

2. **Review Feedback Systems:**
   Conduct a comprehensive review of the feedback and satisfaction measurement systems. Ensure that feedback mechanisms effectively capture and address customer concerns to prevent them from escalating into reasons for churn.

3. **Enhance Complaint Management:**
   Focus on improving complaint management processes to resolve issues more efficiently. Implementing better support systems and proactive issue resolution strategies can help in reducing churn rates associated with customer complaints.

