# 💊 Healthcare Retail Analytics: SQL & Power BI Executive Summary

## 📌 Project Overview
This project provides a 360-degree analysis of a healthcare retail network, transforming raw transactional data into a high-level Executive Dashboard. It focuses on sales performance, inventory health (expiry tracking), and operational efficiency across multiple pharmacy branches.

## 🛠️ Technical Skill Set
1. SQL & Data Analysis
I solved 15 complex business questions to extract critical insights, including:

Financial Reporting: Calculating total revenue, profit margins, and discount impacts.

Inventory Management: Identifying low-stock items (< 20 units) and valuation of current stock.

Predictive Expiry Tracking: Querying products expiring within a 90-day window to minimize loss.

Operational Insights: Analyzing employee transaction volume and store-wise performance comparisons.

2. Power BI & Data Modeling
Built a robust Star Schema to power a dynamic "Healthcare Retail Executive Summary" dashboard:

Data Modeling: Connected a central Fact Sales table to Dimension tables (Stores, Employees, Products).

Time Intelligence: Created a custom DAX Date Table for Month-over-Month and Year-over-Year trend analysis.

Advanced DAX: Developed measures for Total Revenue ($10K), Total Profit ($3.83M), and Low Stock counts.

## 📊 Dashboard Key Features (Visuals)
Executive KPI Cards: Real-time visibility into Revenue, Profit, and critical Low Stock alerts.

Revenue Trends: A line chart visualizing performance over the last 12 months.

Stock Level by Category: A Ring Chart (Donut) analyzing inventory distribution across 'Vitamins', 'Pharmaceuticals', etc.

Revenue by Store: Bar chart comparison identifying top-performing locations like 'CuraLife Plaza'.

Product Expiry Status: A table visual with Conditional Formatting (Red/Yellow) to highlight Expired vs. Expiring Soon products.

Interactive Slicers: Full report filtering by Store Name, Category, and Sale Date.
