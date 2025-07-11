# Global Superstore Sales & Profit Analysis

A data analytics project aimed at uncovering actionable business insights from the Global Superstore dataset. This project identifies profitable regions, customer segments, product categories, and highlights areas causing losses—helping business stakeholders make informed decisions.



## Problem Statement

> To analyze historical sales and order data to determine **which products, regions, categories, and customer segments the company should target or avoid**, based on their contribution to overall sales and profitability.



## Tools & Technologies Used

- **Python** (Pandas, Seaborn, Matplotlib) – Data Cleaning & EDA  
- **Power BI** – Interactive Dashboard & Visualization  
- **Excel** – Data inspection  



## Dataset

- Source: [Global Superstore](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- Fields include: Order ID, Product Name, Category, Sales, Profit, Discount, Region, Customer Segment, and more.
- Time Period: Multi-year sales data



## Key Visualizations in Power BI Dashboard

- **Sales & Profit by Region**
- **Category and Sub-Category Performance**
- **Customer Segment Profitability**
- **Discount vs Profit Correlation**
- **Monthly Sales & Profit Trends**
- **Top 10 Products by Sales**
- **KPIs:** Total Sales, Total Profit, Avg. Discount, Most Profitable Segment

---

## Exploratory Data Analysis (Python)

- Cleaned and preprocessed date/time columns, removed duplicates, handled missing values.
- Visualized patterns in sales, profit, discount, and category performance.
- Generated actionable insights using groupby summaries and charts.

---

## Business Insights

| Area          | Insight                                                                 |
|---------------|-------------------------------------------------------------------------|
| Region        | **West and East** generate the highest sales; South underperforms       |
| Products      | **Tables and Bookcases** have high sales but negative profits           |
| Segments      | **Corporate segment** is the most profitable; Home Office is the lowest |
| Discounting   | High discounts (>30%) often lead to negative profits                    |
| Time Trends   | Sales peak in **Nov-Dec**, indicating seasonal buying patterns          |



## Business Recommendations

- Increase focus and investment in **West & East regions**
- Reassess pricing and discounting strategy for **loss-making products like Tables**
- Prioritize **B2B sales to Corporate segment**
- Control excessive discounting to protect margins
- Align promotions with **holiday seasons** for higher ROI

