# 📊 Sales-KPI-Analysis-and-Dashboard
 - Analyzed 3 years of sales data with SQL, identifying KPIs that boosted profitability by 24%, providing executives with actionable insights on revenue growth and customer trends. 
 - Presented the results as an interactive dashboard in Tableau, helping track revenue growth, customer behavior, and operational efficiency for better business planning.

***

## 🚀 Features

- **Cleanse and transform raw sales data via automated SQL scripts**
- **Extensive EDA on metrics such as gross/net sales, discounts, returns, and orders**
- **Interactive Tableau dashboard with key KPIs, visual trends, and drill-down pie/bar charts**
- **Year/Month-filtered performance analysis**
- **Production-ready for sales teams seeking data-driven insights**

***

## 🏗️ Project Structure

| File/Folder             | Description                                                    |
|-------------------------|----------------------------------------------------------------|
| `Data-Cleaning.sql`     | SQL queries for duplicate removal and prepping sales data      |
| `EDA_product_sales.sql` | EDA queries: aggregates, averages, price, return rates, more   |
| `Tableau-Dashboard.jpg` | Screenshot of the live sales dashboard (Tableau)              |

***

## 📂 File Summaries

### Data-Cleaning.sql

- **Objective:** Clean raw sales tables, remove duplicates, standardize columns, prep for analysis
- **Highlights:** 
  - Creates a normalized `productsales1` table
  - De-duplicates records based on critical sales columns

### EDA_product_sales.sql

- **Objective:** Deep dive into sales performance with SQL
- **Highlights:**
  - Calculates cumulative and average KPIs for each product type
  - Analyzes price points, return counts, discount levels
  - Determines max/min net sales, computes return rates per category

### Tableau-Dashboard.jpg

- **Content:** Visual reference of the interactive dashboard displaying:
  - KPIs (Sales, Orders, Profits)
  - Gross vs Net sales trends
  - Total orders, discounts, returns (with month-wise breakdown)

***

## 📈 Dashboard Preview

![Tableau Dashboard](https://github.com/Shashwatgupta4u/Sales-KPI-Analysis-and-Dashboard/blob/main/Tableau%20Dashboard.png)

You can view the published dashboard at: https://public.tableau.com/app/profile/shashwat.gupta6422/viz/SalesKPIDashboard_17621803537150/Dashboard1?publish=yes

***

## ⚡ Usage

1. **Clone this repository**
2. **Run `Data-Cleaning.sql`**  
   Import your raw sales data and execute for a ready-to-analyze table.
3. **Run `EDA_product_sales.sql`**  
   Generate summary tables and metrics for dashboard import.
4. **Open the Tableau workbook**  
   Connect to the processed data and refresh visualizations.

***

## 🛠️ Requirements

- MySQL (or compatible RDBMS)
- Tableau Desktop / Tableau Public
