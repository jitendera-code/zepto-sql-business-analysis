# 🛒 Zepto Inventory & Pricing Analysis (SQL + Power BI)

## 📌 Project Overview

This project presents an end-to-end data analysis of Zepto’s inventory dataset using SQL and Power BI. The goal is to derive business insights related to pricing, discounts, stock availability, and category performance.

The project includes:

* Data cleaning and transformation using SQL
* Exploratory data analysis
* Business insights generation
* Interactive Power BI dashboard for decision-making

---

## 🎯 Objectives

* Analyze category-wise revenue performance
* Evaluate discount strategies across products
* Identify stock availability and inventory risks
* Determine high-value and low-performing categories
* Support business decisions with data-driven insights

---

## 🗂️ Dataset Details

The dataset contains product-level information such as:

* SKU ID
* Category
* Product Name
* MRP (Maximum Retail Price)
* Discount %
* Discounted Selling Price
* Available Quantity
* Weight (grams)
* Stock Status (In Stock / Out of Stock)

--- https://github.com/jitendera-code/zepto-sql-business-analysis/blob/main/zepto_v2.csv

## 🧹 Data Cleaning (SQL)

Performed using SQL:

* Removed records with zero MRP
* Converted price values from paise to rupees
* Handled missing/null values
* Standardized column formats
* Verified data consistency

---

## 📊 Key Business Insights

### 💰 Revenue Analysis

* Cooking Essentials and Munchies generate the highest revenue (~₹337K each)
* Beverages and Health & Hygiene contribute the least revenue

---

### 📦 Inventory & Stock Health

* Overall Stock Health: **87.86%**
* Out of Stock: **12.14%**
* Categories like Beverages and Biscuits show weaker stock health → potential inventory issue

---

### 🏷️ Discount Analysis

* Fruits & Vegetables offer the highest average discount (~15.5%)
* Most categories operate within low discount range (below 10%)
* Majority products fall under **Low Discount Tier (<10%)**

---

### 📈 Product Distribution

* Cooking Essentials and Munchies have the highest number of products
* Product distribution is uneven across categories

---

### ⚠️ Business Risks Identified

* Categories with low stock health may lead to revenue loss
* High-discount categories may impact profitability
* Inventory imbalance across categories

---

## 📊 Dashboard Features (Power BI)

* KPI Cards:

  * Total Revenue
  * Total Products
  * Stock Health %
  * Out of Stock %

* Visualizations:

  * Revenue by Category
  * Product Distribution by Category
  * Average Discount % by Category
  * Discount Tier Analysis
  * Stock Health Indicator (Conditional Formatting)

* Filters:

  * Category
  * Stock Status

---https://github.com/jitendera-code/zepto-sql-business-analysis/blob/main/Screenshot%202026-04-25%20020558.jpg

## 🛠️ Tools & Technologies

* SQL (PostgreSQL)
* Power BI
* Excel / CSV


## 🚀 Key Learnings

* Data cleaning and transformation using SQL
* Business-oriented data analysis
* Building interactive dashboards in Power BI
* Translating data into actionable insights


## 📌 Conclusion

This project demonstrates how data analysis can help optimize pricing strategies, improve inventory management, and support business decision-making in a retail environment.



## 👤 Author

**Jitender Yadav**
