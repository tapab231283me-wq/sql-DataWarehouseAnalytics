Welcome to my SQL Data Warehouse Analytics project.
This repository demonstrates end-to-end SQL analytics on a data warehouse, including exploratory data analysis, business KPI generation, trend analysis, ranking, segmentation, and analytical reporting.

All project credit goes to Baraa Khatib Salkini.
This project is created as a learning-based implementation of his work, aimed at practicing and applying real-world SQL data warehousing and analytics concepts.

##Project Overview:

The objective of this project is to transform raw warehouse data into meaningful business insights using SQL.
It focuses on analyzing sales, customers, and products through structured queries and reusable reporting views.

The project simulates how analytics teams work with a Gold-layer data warehouse to support decision-making.

##Data Model:

The analytics are built on a star schema consisting of:

Fact Table

fact_sales – transactional sales data

Dimension Tables

dim_customers – customer demographics and attributes

dim_products – product and category information

All queries operate on the Gold layer, optimized for analytics and reporting.

Key Analytics Covered
Exploratory Data Analysis (EDA)

Database schema and metadata exploration

Customer geography and demographics

Product categories and pricing structure

Order date ranges and sales history

Business KPIs

Total sales and revenue

Total orders, products, and customers

Average selling price

Customers who placed orders

Magnitude & Distribution Analysis

Customers by country and gender

Products by category

Revenue contribution by product category

Distribution of items sold across regions

Trend & Time-Series Analysis

Yearly and monthly sales performance

Customer and quantity trends over time

Cumulative revenue analysis

Moving averages for price and sales

Ranking & Performance Analysis

Top and worst-performing products

Top revenue-generating customers

Year-over-year product performance

Comparison with historical averages

Segmentation Analysis

Customer segmentation (VIP, Regular, New)

Product cost-based segmentation

Customer lifecycle and recency analysis

SQL Techniques Used:

Common Table Expressions (CTEs)

Window Functions (RANK, LAG, SUM OVER, AVG OVER)

Aggregations and Grouping

Date and Time Functions

CASE statements for segmentation

Analytical Views for reusable reporting

##Reporting Layer:

The project includes analytical views such as:

gold_report_customers

##These views:

Aggregate customer-level metrics

Capture lifecycle, recency, and spending behavior

Enable direct consumption by BI tools or dashboards

##Key Outcomes:

Clear visibility into overall business performance

Identification of high-value customers and products

Insights into customer behavior and lifecycle

Scalable SQL patterns for analytics and reporting

##How to Use This Project:

Load the schema and data into SQL Server

Run the exploratory and analytical queries

Create reporting views for reusable insights

Extend the project with dashboards or additional metrics

##License:
this project is licensed under the [MIT License](Lincense).

##About me:

Tapa Ankitha
Aspiring Data Analyst / Data Engineer
Focused on SQL, data warehousing, and analytics
