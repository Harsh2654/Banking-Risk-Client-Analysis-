💼 Banking Risk Analysis & Client Segmentation Dashboard
📌 Problem Statement
Banks and financial institutions face a major challenge in assessing the risk associated with lending. The objective of this project is to build a comprehensive data-driven dashboard to analyze client profiles, evaluate risk metrics, and support smarter decision-making in loan approvals and financial services. The aim is to reduce financial loss by identifying high-risk customers before approving credit or loans.

📊 Project Objective
To build an end-to-end Banking Risk and Client Analysis Dashboard using:

Python for data cleaning and preprocessing

SQL for querying and transforming relational data

Power BI for visualization and dashboard creation

EDA (Exploratory Data Analysis) for identifying key insights and business patterns

🧾 Dataset Overview
The dataset simulates client and banking data, comprising multiple relational tables:

Clients

Client-Banking

Banking Relationship

Investment Advisor

Gender

Period

Each table is connected via primary and foreign keys, mimicking real-world banking data environments.

🧹 Data Cleaning & Feature Engineering
Performed using Python (Pandas) and Power BI Query Editor:

Created new column Engagement Timeframe to determine client activity timeline

Derived Engagement Days using DATEDIFF to calculate duration since joining

Binned Estimated Income into Income Band (Low, Mid) for better client segmentation

Generated Processing Fees based on Fee Structure, assigning logic-based multipliers

🧮 DAX Calculations & Measures
Implemented various DAX functions in Power BI:

SUM() for total financial metrics like deposits, loans, and balances

DISTINCTCOUNT() to identify unique client counts

SUMX() for advanced row-wise fee calculations

SWITCH() for conditional logic based on fee structure

DATEDIFF() to calculate engagement durations

📈 Key Performance Indicators (KPIs)
Total Clients – Number of unique banking clients

Total Loan – Combined sum of Bank Loan, Business Lending, and Credit Card Balances

Total Deposit – Aggregated deposits from different account types

Processing Fees – Computed fees based on loan types and client segmentation

Credit Card Balance – Outstanding credit for each client

Engagement Duration – How long clients have been with the bank

📊 Power BI Dashboards
Loan Analysis Dashboard

Loan distribution by client, gender, nationality

High-risk profiles based on credit card balances and business lending

Deposit Analysis Dashboard

Total deposits by account types and clients

Foreign currency trends and savings analysis

Client Engagement Dashboard

Active vs inactive clients

Engagement duration and churn indicators

Summary Dashboard

Consolidated view of all KPIs

Filtering and slicers for deeper drill-down

📌 Tools & Technologies Used
Tool/Tech	Purpose
Python	Data cleaning, preprocessing
Power BI	Interactive dashboards & data modeling
SQL	Data extraction & joins
DAX	Custom measures & KPIs
Excel	Initial data exploration (optional)

🔍 Key Insights
Identified client segments with highest loan exposure and low engagement

Discovered that private banks had higher client concentration

Highlighted nationalities and demographics with larger credit usage

Enabled banks to filter high-risk vs low-risk profiles for better lending decisions

🚀 Future Improvements
Integrate ML models to predict default risk or churn probability

Enable real-time data streaming for live dashboards

Add geographic analysis by mapping client data

Automate ETL workflows using Python scripts and Power BI Dataflows

📁 Project Structure
plaintext
Copy
Edit
📦Banking-Analysis-Project
 ┣ 📂PowerBI_Dashboard
 ┃ ┗ 📄Banking_Dashboard.pbix
 ┣ 📂SQL_Scripts
 ┃ ┗ 📄data_cleaning_queries.sql
 ┣ 📂Python_Scripts
 ┃ ┗ 📄preprocessing.py
 ┣ 📂Dataset
 ┃ ┗ 📄clients.csv
 ┃ ┗ 📄client_banking.csv
 ┣ 📄README.md
📎 Conclusion
This project demonstrates how to combine data analytics tools to solve real-world banking problems. By leveraging EDA, SQL, Power BI, and Python, we created a comprehensive dashboard that allows financial institutions to make data-backed decisions, reduce lending risk, and improve client engagement.
