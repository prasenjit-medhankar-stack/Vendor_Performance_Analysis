Vendor Performance Analysis Dashboard
End-to-End Data Analytics Project using Python, SQLite, SQL, Power BI, and Data Visualization

A complete analytics solution designed to evaluate vendor performance, inventory efficiency, procurement strategy, and profitability using transactional sales and purchasing data.

Project Overview

This project demonstrates a complete data analytics workflow from raw CSV files to business intelligence dashboards.

The project includes:

Loading multiple datasets into Python
Data cleaning and preprocessing
Building a SQLite database
Performing SQL-based business analysis
Creating vendor-level KPIs
Building an interactive Power BI dashboard
Generating business recommendations

The objective is to transform raw procurement and sales data into actionable insights that help optimize vendor management, inventory control, and profitability.

Dataset Information
Datasets Used
Purchases.csv
Sales.csv
Purchase_Prices.csv
Vendor_Invoice.csv
Begin_Inventory.csv
End_Inventory.csv
Dataset Description

The datasets contain information related to:

Vendor details
Product information
Purchase transactions
Sales transactions
Freight costs
Inventory levels
Product pricing
Tools & Technologies
Tool / Technology	Purpose
Python	Data processing and automation
Pandas	Data cleaning and transformation
NumPy	Numerical operations
SQLite	Database creation and management
SQL	Data querying and analysis
Matplotlib	Data visualization
Seaborn	Statistical visualization
Power BI	Dashboard development
Jupyter Notebook	Analysis environment
Project Workflow
Data Ingestion

Raw CSV files were loaded into Python and ingested into SQLite.

Tasks Performed
Imported datasets
Validated file structure
Created database tables
Loaded data into SQLite
Exploratory Data Analysis (EDA)

Performed EDA to understand vendor behavior and business performance.

EDA Activities
Univariate Analysis
Bivariate Analysis
Distribution Analysis
Outlier Detection
Correlation Analysis
Inventory Analysis
Vendor Performance Analysis
Visualization Techniques Used
Histograms
Boxplots
Scatter Plots
Correlation Heatmaps
Bar Charts
Distribution Plots
Data Cleaning & Preprocessing

Performed:

Missing value treatment
Duplicate removal
Data type conversion
String standardization
Data validation
Feature engineering
SQL Analysis Using SQLite

The cleaned datasets were merged and analyzed using SQL.

SQL Concepts Used
SELECT Statements
WHERE Clauses
GROUP BY
ORDER BY
Aggregate Functions
Common Table Expressions (CTEs)
JOIN Operations
Filtering & Sorting
Feature Engineering

Additional business metrics were created:

Gross Profit
Gross Profit = Total Sales Dollars - Total Purchase Dollars
Profit Margin
Profit Margin = Gross Profit / Total Sales Dollars
Stock Turnover
Stock Turnover = Sales Quantity / Purchase Quantity
Sales-to-Purchase Ratio
Sales-to-Purchase Ratio = Sales Dollars / Purchase Dollars
Power BI Dashboard

An executive-level dashboard was developed to monitor vendor and inventory performance.

Dashboard Features
KPI Cards
Total Sales
Total Purchases
Gross Profit
Profit Margin
Unsold Capital
Vendor Analysis
Top Vendors by Sales
Vendor Purchase Contribution
Low Performing Vendors
Brand Analysis
Top Brands by Revenue
Low Performing Brands
Inventory Analysis
Inventory Turnover
Unsold Capital Tracking
Profitability Analysis
Vendor Profitability
Margin Distribution
Key Insights
Vendor Concentration Risk

Top vendors contribute the majority of purchase volume, creating supply chain dependency.

Bulk Purchasing Benefits

Large purchase quantities significantly reduce procurement costs.

Inventory Optimization Opportunity

Unsold inventory capital indicates opportunities for improving turnover and cash flow.

Profitability Variations

Significant differences exist between top-performing and low-performing vendors.

Brand Growth Opportunities

Several high-margin brands have low sales volumes and can benefit from targeted promotions.

Business Recommendations
Vendor Diversification

Reduce reliance on a small group of vendors.

Inventory Optimization

Improve stock turnover through better procurement planning.

Pricing Strategy Improvement

Reassess pricing of underperforming products.

Promotional Campaigns

Increase visibility of profitable low-volume brands.

Procurement Optimization

Continue leveraging bulk purchasing to maximize margins.

Dashboard Preview

(Insert your Power BI dashboard screenshot here)

How to Run the Project
Step 1: Data Ingestion

Run:

python ingestion_db.py
Step 2: Generate Vendor Summary

Run:

python get_vendor_summary.py
Step 3: Exploratory Data Analysis

Open:

Exploratory_Data_Analysis.ipynb

Run all cells.

Step 4: Power BI Dashboard

Open:

Vendor_Performance_Dashboard.pbix

Refresh the data source if required.

Project Outcome

This project demonstrates practical experience in:

Data Cleaning
Exploratory Data Analysis
SQL Development
Database Management
Business Intelligence
Power BI Dashboarding
Data Storytelling
Business Recommendation Generation
