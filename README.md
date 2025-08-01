# 🛒 E-Commerce Data Analysis Project (SQL + Python)

## 📌 Project Overview
This project demonstrates the integration of Python and SQL for comprehensive e-commerce data analysis. Leveraging `pandas`, `matplotlib`, `seaborn`, and MySQL, the project transforms raw datasets into actionable insights. Key operations include data cleaning, table creation, advanced SQL querying, and visualizations.

## 🧰 Technologies & Tools Used
- **Python Libraries:** pandas, matplotlib, seaborn, numpy
- **Database:** MySQL (via `mysql-connector`)
- **Environment:** Local file system for CSV ingestion

## 📂 Data Source
The analysis uses multiple CSV files stored under the folder `Documents/eCOMMERS`, covering:
- Customers
- Orders
- Sellers
- Products
- Geolocation
- Order Items
- Payments

## 🏗️ Workflow Summary
1. Load & preprocess CSV files
2. Clean column names and handle null values
3. Generate MySQL tables and insert records
4. Run categorized SQL queries from basic to advanced
5. Visualize key metrics using bar plots and seaborn charts

---

## 🔎 Solved Queries

### 🧮 Basic Queries
1. **Unique Cities:** Extracted all distinct cities from `customers`.
2. **Orders in 2017:** Counted total orders where `order_purchase_timestamp` falls in 2017.
3. **Sales by Category:** Summed `payment_value` grouped by product category.
4. **Installment Orders:** Calculated percentage of orders paid via installments.
5. **Customer Distribution:** Visualized customer count per state using bar chart.

### 📊 Intermediate Queries
1. **Monthly Orders (2018):** Counted and visualized orders per month in 2018.
2. **Average Products per Order:** Computed average product count per order by city.
3. **Revenue by Category (%):** Calculated percentage contribution of each product category to total revenue.
4. **Price vs. Frequency:** Analyzed correlation between product price and frequency of purchase.
5. **Seller Revenue Ranking:** Ranked sellers by their total revenue contributions.

### 🧠 Advanced Queries
1. **Moving Avg of Order Value:** Computed 3-period moving average of payments per customer.
2. **Cumulative Sales per Month:** Aggregated monthly revenue across all years.
3. **YOY Growth:** Calculated year-over-year growth rates in total sales.
4. **Customer Retention:** Evaluated customers making repeat purchases within 6 months of their first.
5. **Top Spenders:** Identified top 3 customers (per year) with highest spending.

---

## 📈 Key Visuals
- Customer distribution by state
- Monthly order volumes
- Seller revenue comparisons
- Spending trends per customer

## ✅ Results & Learnings
- Demonstrated strong SQL query design across complexity levels
- Used Python for data handling, statistical analysis, and graphical representation
- Applied window functions, subqueries, and joins efficiently
- Uncovered key business insights such as revenue hotspots, customer patterns, and seller performance


