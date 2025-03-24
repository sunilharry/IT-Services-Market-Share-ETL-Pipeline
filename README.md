# IT-Services-Market-Share-ETL-Pipeline

Problem Statement :
Gartner has market share data from 2019 to 2023 without a central way to access and analyze it. 
The goal is to create an ETL pipeline to transform the data and display insights in a dashboard.

Solution Overview :

1. ETL Pipeline
Technologies: Python, Pandas, SQL

Steps:
  I. Extract: Import data from sources
  II. Transform: Clean, merge, and standardize data
  III. Load: Save processed data into a target database

2. Dashboard :
  Built using Power BI to show :
    I. Yearly Revenue Trends
    II. Top Vendors by Market Share
    III. Regional Revenue Breakdown
    IV. Top 10 Vendors by Revenue

3. Performance and Error Handling :
    I. Indexed tables for faster queries
    II. Batch processing to improve speed
    III. Logging for error tracking
