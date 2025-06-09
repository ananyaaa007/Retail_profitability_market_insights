# 📊 Retail Profitability & Strategic Market Insights

## 🧠 Overview

This project presents an in-depth analysis of sales performance using a fictional Superstore dataset. It combines **Python (in Jupyter/VS Code)** for data preparation and **Tableau Desktop** for interactive data visualization. The final goal is to deliver actionable insights across dimensions like region, product categories, customer behavior, discounts, and shipping costs.

🚀 The outcome is a **fully interactive dashboard** hosted on [Tableau Public](https://public.tableau.com/app/profile/ananya.srivastava2798/viz/retail_profitability_market_insights_da/GlobalSaleDashboard?publish=yes), designed to support strategic decision-making.

---

## 📚 Table of Contents

1. [Dataset Overview](#dataset-overview)  
2. [Tools & Technologies](#tools--technologies)  
3. [Process](#process)  
4. [Key Visualizations](#key-visualizations)  
5. [Insights](#insights)  
6. [Dashboard](#dashboard)  
7. [File Structure](#file-structure)  
8. [How to Run](#how-to-run)  
9. [Conclusion](#conclusion)  

---

## 📦 Dataset Overview

The dataset includes:
- 📈 **50,000+ rows** and **26 columns**
- Features like:  
  - Sales, Profit, Discounts  
  - Region, Customer Segment, Product Category  
  - Shipping Cost, Order Dates, etc.

The dataset was cleaned and enhanced with:
- Derived metrics: **Profit Percentage**, **Discount Impact**, **Sales Contribution (%)**
- Missing value handling and removal of duplicates

---

## 🛠️ Tools & Technologies

### ✔ Python (Jupyter Notebook / VS Code)
- **Pandas, NumPy**: Data manipulation and preprocessing  
- **Matplotlib, Seaborn**: Exploratory visualizations

### ✔ Tableau Desktop & Tableau Public
- For creating interactive dashboards with filters, dual axes, and tooltips

---

## 🔄 Process

### 1. Data Cleaning & Preparation
- Loaded and explored the raw dataset (`superstore.csv`)
- Cleaned null values and corrected data types
- Generated new columns like `Profit Margin` and `% Contribution to Sales`

### 2. Exploratory Data Analysis
- Investigated relationships:
  - Discounts vs Profit
  - Regional shipping patterns
  - Category-wise profit drivers

### 3. Tableau Dashboard Creation
- Built 8 individual visualizations and assembled them into an interactive dashboard

---

## 📊 Key Visualizations

| No. | Visualization | Purpose |
|-----|---------------|---------|
| 1️⃣ | **Sales by Region** | Highlights sales performance by geographic region |
| 2️⃣ | **Profit by Product Category** | Understand which product lines drive profit |
| 3️⃣ | **Sales vs Profit (Scatter Plot)** | Visualize profitability across different sales levels |
| 4️⃣ | **Discount vs Profit** | Analyze how discounts influence profit |
| 5️⃣ | **Shipping Cost by Region** | Identify regions with high logistical cost |
| 6️⃣ | **Sales & Profit by Year** | Track annual trends in sales and profit |
| 7️⃣ | **Top 10 Customers** | Find the most valuable customers |
| 8️⃣ | **Category Contribution (%)** | Understand each category's share of total sales |

---

## 🔍 Insights

- 💡 **Central region** leads in sales but has high shipping costs.
- 💰 **Technology** is the most profitable category.
- 📉 Excessive **discounting reduces profit** — strategic discounting is key.
- 👥 A small group of customers drives a large percentage of revenue (Pareto insight).

---

## 📌 Dashboard

> 🔗 Access the **interactive Tableau dashboard** here:  
[👉 View Dashboard on Tableau Public](https://public.tableau.com/app/profile/ananya.srivastava2798/viz/retail_profitability_market_insights_da/GlobalSaleDashboard?publish=yes)

Features:
- Filters by Region, Category, Customer
- Tooltips for individual data points
- Cohesive design with KPI focus

---

## 📁 File Structure

Retail-Profitability-Strategic-Market-Insights/
├── data/
│ ├── superstore.csv # Raw data
│ └── superstore_eda_cleaned.csv # Cleaned and processed data
├── notebooks/
│ ├── 01_Data_Understanding_and_Cleaning.ipynb
│ └── 02_Exploratory_Data_Analysis.ipynb
├── tableau_dashboard/
│ └── GlobalSaleDashboard.twbx # Tableau packaged workbook (optional)
├── .gitignore
├── README.md
 
