Customer Shopping Behavior Analysis – Data Analytics Project
Overview

This project demonstrates a complete end-to-end Data Analytics workflow using Python, SQL (MySQL), and Power BI. The objective of this project is to analyze customer shopping behavior, clean and transform data, perform exploratory data analysis (EDA), run SQL queries to extract insights, and build an interactive Power BI dashboard for visualization.

This project showcases practical data analytics skills used in real-world business scenarios.

Dataset

The dataset used in this project contains customer shopping behavior information, including:

Customer demographics
Product categories
Purchase amounts
Payment methods
Shopping frequency
Transaction details

File included:

customer_shopping_behavior.csv

Tools and Technologies
Python
Pandas
MySQL
SQL
Power BI
Jupyter Notebook
Project Steps
1. Data Loading
Loaded dataset using Pandas
Displayed dataset structure
Checked data types
Reviewed initial records
2. Exploratory Data Analysis (EDA)
Generated summary statistics
Analyzed data distributions
Identified patterns and trends
3. Data Cleaning
Handled missing values
Standardized column names
Ensured data consistency
4. SQL Analysis (MySQL)
Imported cleaned dataset into MySQL
Created database and tables
Executed SQL queries to analyze data

Example analysis performed:

Total sales calculation
Average purchase amount
Sales by product category
Customer spending patterns

5. Power BI Dashboard
Connected Power BI to the dataset
Created interactive visualizations
Designed dashboard layout
Added filters and slicers
Presented key business insights
Dashboard Features

The Power BI dashboard includes:

Total Sales Overview
Sales by Category
Customer Demographics Analysis
Payment Method Distribution
Sales Trends
Interactive Filters

File included:

customer_behavior_dashboard.pbix

Key Results
Identified top-performing product categories
Analyzed customer purchasing behavior
Detected popular payment methods
Observed spending trends
Generated insights to support business decisions
Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── customer_shopping_behavior.csv
├── Customer_Shopping_Behavior_Analysis.ipynb
├── sql_customer_behavior.sql
├── customer_behavior_dashboard.pbix
└── README.md
How to Run the Project
Step 1: Clone the Repository

git clone https://github.com/your-username/customer-shopping-behavior-analysis.git

cd customer-shopping-behavior-analysis

Step 2: Install Required Libraries

pip install pandas mysql-connector-python

Step 3: Run the Python Notebook

jupyter notebook

Open:
Customer_Shopping_Behavior_Analysis.ipynb

Step 4: Run SQL Queries
Open MySQL Workbench
Import the dataset into a database
Run the SQL script:

sql_customer_behavior.sql

Step 5: View the Power BI Dashboard

Open the file:

customer_behavior_dashboard.pbix
