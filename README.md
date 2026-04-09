# retail-sales-analysis
Project Overview :
This project performs an end-to-end data analysis on an online retail dataset to uncover key business insights related to sales performance, customer behavior, and product trends.
The goal is to simulate a real-world data analyst workflow — from raw data to actionable insights.

Dataset Description :
The dataset contains transactional data of an online retail store with the following columns:
InvoiceNo – Unique invoice number
StockCode – Product code
Description – Product name
Quantity – Number of items purchased
InvoiceDate – Date and time of purchase
UnitPrice – Price per unit
CustomerID – Unique customer identifier
Country – Customer location

Tools & Technologies :
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook / VS Code
Git & GitHub

Project Workflow :
1. Data Loading
Loaded dataset using Pandas
Handled encoding issues using latin1
2. Data Cleaning
Removed missing values (CustomerID)
Filtered invalid data (Quantity ≤ 0, UnitPrice ≤ 0)
Converted InvoiceDate to datetime format
Cleaned text fields
3. Feature Engineering
Created new column:
Revenue = Quantity × UnitPrice
4. Exploratory Data Analysis (EDA)
Top selling products
Revenue by country
Monthly sales trends
Visualization using plots
5. Customer Analysis
Top customers by revenue
Orders per customer distribution
Customer purchase behavior
6. Business Insights
Identified high-revenue products
Found top-performing countries
Observed seasonal sales trends
Recognized high-value customers

End-to-end retail sales data analysis using Python
