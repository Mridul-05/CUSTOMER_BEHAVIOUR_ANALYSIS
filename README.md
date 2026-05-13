# Customer Behavior Analysis — End-to-End Data Analytics Project
 An end-to-end data analytics project covering data ingestion, exploratory data analysis, data cleaning, SQL querying, and interactive business intelligence dashboards.

 
# Overview
This project presents a complete data analytics pipeline built to analyze customer behavior patterns and extract actionable business insights. Starting from raw data ingestion in Python, through structured querying in PostgreSQL, and culminating in an interactive Power BI dashboard — this project demonstrates a full analytics workflow aligned with real-world commercial operations.
The goal is to understand customer trends, identify key performance indicators, and present findings in a clear, business-ready format.

# Tools & Technologies
Python :Data loading, EDA, cleaning, and preprocessing
Pandas & NumPy: Data manipulation and analysis
PostgreSQL: Structured data storage and SQL querying
SQLAlchemy + psycopg2: Python–PostgreSQL connection
Power BI: Interactive dashboard and business reporting
Jupyter Notebook(VS Code): Development environment

# Project Steps
1.Data Loading

Imported the dataset using Pandas
Connected to PostgreSQL using SQLAlchemy
Loaded the cleaned DataFrame into the customer table in the Customer_Behavior database

2.Exploratory Data Analysis (EDA)

Examined dataset shape, data types, and distributions
Identified patterns across customer demographics and purchase behavior
Key questions explored:
What age groups spend the most?
Which product categories are most popular?
Are there seasonal trends in purchases?

3.Data Cleaning

Handled missing values using median review rating within each category
snake_case all column name
Standardized column formats (dates, categorical values)
Create new column purchase_frequency_days and  column age_group (feature engineering)

4.SQL Queries on PostgreSQL
Ran structured queries to extract business insights directly from the database.

5. Power BI Dashboard

Connected Power BI Desktop directly to PostgreSQL database
Built an interactive dashboard with slicers, filters, and drill-throughs

# Author
Mridul Chelladurai | mridulchella@gmail.com 

This project was built as part of a data analytics portfolio to demonstrate end-to-end data skills including Python, SQL, and business intelligence reporting.
