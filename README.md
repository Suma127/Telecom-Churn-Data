# Project Summary
Developed an end-to-end Customer Churn Analysis Dashboard using Power BI to identify customer attrition trends and support retention strategies. Performed data analysis, created DAX measures, designed KPI dashboards, and generated actionable business insights from telecom customer data.
## Telecom-Churn-Data
This project analyzes customer churn patterns using Power BI. The objective is to identify customer retention trends, calculate churn metrics, and generate business insights that help reduce customer attrition.
- Developed an interactive Power BI dashboard to analyze telecom customer churn trends.
- Created DAX measures for Total Customers, Churned Customers, Churn Rate, and Retention Rate.
- Performed data cleaning, transformation, and KPI development.
- Generated actionable insights to identify customer attrition patterns and support retention strategies.
- Built visualizations to monitor customer behavior and business performance.
## Tools Used

- Power BI
- DAX
- Excel / CSV
- Data Cleaning
- Data Visualization

## Dataset

Telecom Customer Churn Dataset

Dataset contains customer information such as:

- State
- Account Length
- Area Code
- International Plan
- Voice Mail Plan
- Customer Service Calls
- Total Day Calls
- Total Day Charges
- Total Evening Calls
- Total Evening Charges
- Churn Status

## Dashboard Features

- Total Customers KPI
- Total Churned Customers KPI
- Churn Rate KPI
- Total Calls Analysis
- Total Charges Analysis
- Churn Distribution Analysis

## Screenshots
<img width="1323" height="736" alt="image" src="https://github.com/user-attachments/assets/ea9c5c54-7322-47d6-83d6-c6f834b4de10" />
<img width="1302" height="723" alt="image" src="https://github.com/user-attachments/assets/56d60d0e-313b-4ae7-ad16-b58f0b8260de" />



## Key Insights
- Total Customers: 667
- Churned Customers: 95
- Churn Rate: 14.24%
- Retention Rate: 85.76%

## Business Impact
This dashboard helps organizations:
- Monitor customer retention
- Identify churn trends
- Analyze customer behavior
- Support customer retention strategies
- Future Enhancements
- Churn by State Analysis
- Churn by Customer Service Calls
- Churn by International Plan
- Predictive Churn Modeling using Machine Learning

## KPIs Created

### Churn Rate

Churn Rate =
DIVIDE(
    [Total Churned Customers],
    [Total Customers]
)
### Total Churned Customers


Total Churned Customers =CALCULATE(COUNTROWS('churn-bigml-20'),'churn-bigml-20'[Churn] = TRUE())
### Total Customers

```DAX
Total Customers =
COUNTROWS('churn-bigml-20')


