# 🍕 Urban Food Delivery Analysis

## Overview
End to end data analysis project on urban food delivery 
dataset covering 8 major Indian cities with 2209 clean records.

## Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- SQL (DuckDB — Joins, Subqueries, Window Functions)
- Power BI (DAX, Data Modeling, Interactive Dashboard)
- Azure Blob Storage
- Google Colab, GitHub

## Dataset
- Raw dataset: 2570 records, 22 columns
- Final clean dataset: 2209 records, 21 columns
- Cities: Delhi, Mumbai, Chennai, Bangalore, 
  Hyderabad, Kolkata, Pune, Ahmedabad

## Steps Performed

### 1. Data Cleaning
- Dropped junk columns and duplicates
- Fixed datatypes for Order_Amount and Delivery_Time
- Standardized City, Cuisine, Payment_Mode columns
- Handled 10+ columns with missing values
- Removed 104 impossible discount entries
- Filtered outliers using IQR method

### 2. Exploratory Data Analysis
- 10 business questions answered
- Charts: Bar, Pie, Box Plot, Scatter, Heatmap

### 3. SQL Analysis (DuckDB)
- Created multi table database
- Wrote queries using GROUP BY, HAVING, 
  INNER JOIN, Subqueries, CASE WHEN
- Window functions: ROW_NUMBER, RANK, LAG

### 4. Power BI Dashboard
- 3 page interactive dashboard
- 6 DAX measures created
- Pages: Executive Overview, Customer Analysis, 
  Delivery Performance

## Key Insights
- Only 20% of orders successfully delivered — 
  major operational red flag
- Chennai has highest average order value — premium market
- Middle age group (36-45) orders most frequently
- Delivery time (64.98 mins) exceeds 45 min target by 20 mins
- Orders peak in April-May, drop sharply in June-July
- Sunny weather drives most orders surprisingly

## Business Recommendations
- Investigate 80% non-delivery rate urgently
- Target 18-25 age group with student discounts
- Focus premium campaigns on Chennai and Hyderabad
- Strengthen loyalty rewards for repeat customers
- Optimize delivery operations to meet 45 min target

## Dashboard Preview

https://github.com/user-attachments/assets/22a3c476-0b72-4d9e-be0a-32600b7e5b26

## Connect
[LinkedIn](https://www.linkedin.com/in/shivansh-sah-6790b3249/)
[GitHub](https://github.com/S8I21)
