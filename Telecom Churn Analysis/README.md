# Churn Analysis Dashboard 

## Project Overview
This project explores customer churn behavior in the telecom industry using SQL for data extraction, analysis, and cleaning, followed by dashboard visualization in Power BI. It identifies churn drivers, customer segments, and revenue impact to support business decisions.

## Tools Used
SQL (MySQL) for exploratory analysis, feature creation, and data normalization
Power BI for interactive dashboard creation
DAX for dynamic KPIs and calculated metrics

## Key Analytical Areas
- Gender-based churn percentages
- Churn distribution by contract type, age, marital status, and state
- Churn reason analysis including competitor offerings, support quality, and service usage
- Feature-wise customer service usage patterns (e.g., Streaming TV, Internet, etc.)
 
## Data Cleaning Process
Text columns with nulls, blanks, or irrelevant strings are normalized using SQL CASE statements. Services like Streaming, Support, and Internet are standardized to “Yes/No” or “None” values. This ensures accurate filters and grouping in Power BI visuals.

## Insights Derived
- Customers with shorter tenure and lower monthly charges show higher churn
- Premium support and bundled services positively influence retention
- Competitor offers and dissatisfaction with support drive churn
- Specific contract types (e.g., Month-to-Month) correlate with higher churn
- ARPU and Lost Revenue metrics quantify financial impact clearly

## Business Impact
The project enables marketing, customer service, and strategic teams to
- Develop targeted retention strategies
- Monitor churn rates across customer personas
- Quantify lost revenue and churn risk in real time

