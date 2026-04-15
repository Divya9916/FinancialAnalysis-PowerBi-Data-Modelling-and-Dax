# Credit Card Financial Analysis Project

## Project Overview
This project involves a comprehensive financial analysis of credit card transactions and customer demographics using Power BI. By applying advanced DAX (Data Analysis Expressions), the project transforms raw financial data into an interactive dashboard that monitors key performance indicators (KPIs) such as revenue, transaction volume, and interest earned. The analysis focuses on identifying customer behavior patterns, credit utilization, and risk assessment to drive data-driven financial decision-making.

## Repository Structure
<img width="581" height="338" alt="image" src="https://github.com/user-attachments/assets/3623687b-ba06-4c60-82fb-db33f15e0cec" />


## Technical Workflow
1. Data Modeling & Preparation
Multi-Source Integration: Connected and merged four distinct datasets (Transactions and Customer details) into a unified star-schema data model.
ETL via Power Query: Performed data cleaning, handled null values, and standardized currency and date formats for chronological analysis.
Relationship Management: Established one-to-many relationships between customer demographics and their respective transaction histories.

2. Advanced DAX Implementation
The core analytical engine of this project relies on custom DAX measures, including:
Time Intelligence: Calculated Weekly Revenue, Month-to-Date (MTD), and Year-to-Date (YTD) growth rates to track financial performance over time.
Risk Categorization: Created a "High Risk Client Flag" using conditional logic:
Conditions: Total Revolving Balance > 90% of Credit Limit AND Average Utilization Ratio > 0.8.
Customer Segmentation: Developed measures to group customers by age, income level, and card category (Blue, Silver, Gold, Platinum).
Metric Calculation: Built dynamic KPIs for Total Revenue, Total Interest, Total Transaction Amount, and Average Utilization Ratio.

3. Interactive Visualization
Dynamic Dashboards: Created visual reports that allow users to filter by Gender, Card Category, and Education level.
KPI Cards: Real-time tracking of critical financial health metrics.
Trend Analysis: Visualized revenue by week and customer segment to identify seasonal peaks and high-value demographics.

## Key Insights
Demographic Performance: Identified that graduates and business professionals contribute significantly to the total revenue share.

Utilization Trends: High-income clients generally maintain higher credit limits but exhibit lower utilization ratios, indicating responsible credit management.

Risk Monitoring: The High-Risk Flag allows for proactive monitoring of clients whose revolving balances near their credit limits, helping in delinquency prevention.

## Final Deliverables
Processed .pbix File: A fully functional Power BI report with optimized data models and DAX measures.

Financial Analysis Report (PDF): A detailed presentation outlining the project methodology, DAX formulas used, and visual findings.

## Tools Used
Power BI Desktop: For data modeling
Power Query: For data extraction, transformation, and loading (ETL).

# Author
Divya Sharma Email: divya649sharma99@gmail.com  
GitHub: github.com/Divya9916 
LinkedIn: www.linkedin.com/in/divya9916

# License
This project is open source and available under the MIT License.
