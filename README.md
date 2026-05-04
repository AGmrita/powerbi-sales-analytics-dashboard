# Power BI Sales Analytics Dashboard
Power BI Sales Dashboard project with star schema data modelling, DAX-based KPIs, and interactive visualizations for business insights.

## Overview

This project is an **end-to-end Sales Analytics Dashboard** built using Microsoft Power BI. It provides actionable insights into **sales performance, customer behavior, and product trends** using structured data modelling and interactive visualizations.

The dashboard enables stakeholders to quickly analyze **revenue trends, top products, and product performance** for better decision-making.

## Objectives

- Analyze overall sales performance
-Identify **top products and highest sales amount**
-Track **sales trends over time based on total orders**
-Understand **country and category-level performance**
-Build an interactive dashboard for business users

## Dataset

The project uses a star schema structure:

-**fact_sales** → Transaction-level sales data
-**dim_customers** → Customer details
-**dim_products** → Product details

## Data Modelling
-Implemented a Star Schema
-Established relationships:
-fact_sales[customer_key] → dim_customers[customer_key]
-fact_sales[product_key] → dim_products[product_key]
-Ensured optimized model for performance and scalability

## Key Metrics (DAX Measures)

The following KPIs were created using DAX:

-**Total Sales** = SUM of sales amount
-**Total Orders** = Count of transactions
-**Total Quantity** = Sum of quantity sold
-**Average Order Value (AOV)**
-**Top 5 Customer** (using ranking logic)

## Dashboard Features
-📈 **Sales Trend Analysis** (time-based insights)
-🏆 **Top 5 Products**
-🌍 **Geographical Sales Distribution**
-📦 **Category and Subcategory-wise Performance**
-🎛 **Interactive Filters** (Slicers):
    -Order Date
    -Country
    -Product Category
    -Gender

This Power BI Sales Dashboard empowers to deliver accurate and interactive sales insights.

