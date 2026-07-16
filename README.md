# 📊 End-to-End Retail Sales Analytics | Python, SQL, Excel & Power BI

An end-to-end retail sales analytics project built using Python (Pandas), SQL, Excel, and Power BI. The project demonstrates a complete analytics workflow, including data preprocessing, SQL-based business analysis, interactive dashboard development, and business insight generation from retail sales data.

## 🔄 Project Pipeline

Raw Dataset  
↓  
Python (Data Cleaning & Validation)  
↓  
SQLite (Business Analysis)  
↓  
Excel (Reporting & Charts)  
↓  
Power BI (Interactive Dashboard)  
↓  
Key Insights

## Tools Used
- Python (Pandas)
- SQL (SQLite)
- Microsoft Excel
- Power BI
- GitHub

## Project Structure
- data/  
  ├── raw/          → Original Kaggle dataset  
  └── processed/    → Cleaned dataset generated using Python  
- python/           → Data preprocessing using Pandas  
- sql/              → Data validation and business analysis queries  
- outputs/          → Excel workbook with query outputs and charts  
- images/           → Dashboard and chart screenshots  
- solution/         → Detailed SQL questions, queries, results, and insights

## Project Workflow

1. **Extract**
   - Imported the raw Superstore dataset into Python using Pandas.

2. **Transform**
   - Validated the dataset by checking missing values, duplicate records, data types, and summary statistics.
   - Standardized column names and exported a cleaned dataset.

3. **Load**
   - Loaded the cleaned dataset into SQLite for analysis.

4. **Analyze**
   - Solved 8 business-focused SQL questions using aggregations, window functions, and analytical queries.

5. **Visualize**

   - Created Excel charts for SQL outputs.
   - Developed an interactive Power BI dashboard to explore KPIs, sales trends, customer behavior, and regional performance.

## 📊 Power BI Dashboard

### Executive Dashboard

![Executive Dashboard](images/executive_dashboard.png)

### Customer & Product Analysis

![Customer & Product Analysis](images/customer_product_dashboard.png)

## 📈 Key Insights

- Monthly sales exhibited seasonal fluctuations while maintaining an overall upward trend.
- Higher discount levels were associated with reduced profitability, highlighting opportunities to optimize pricing strategies.
- A relatively small group of customers generated a significant share of total revenue.
- Sales and profit performance varied across product categories, regions, and customer segments.
- Several products consistently generated losses despite strong sales, indicating opportunities for product portfolio optimization.

## 📂 Dataset

- **Source:** Kaggle - Sample Superstore Dataset
- **Records:** ~9,900 sales transactions
- **Domain:** Retail Sales Analytics

## Skills Demonstrated

- SQL (Joins, Aggregations, CTEs, Window Functions)
- Python (Pandas)
- ETL & Data Preprocessing
- Data Cleaning & Validation
- Exploratory Data Analysis (EDA)
- Power BI Dashboard Development
- DAX Measures
- Microsoft Excel
- Business Intelligence & Data Visualization
- Git & GitHub

## Full Analysis

The complete SQL queries, outputs, business insights, and recommendations are available in **Solution.md**.
