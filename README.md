# E-commerce-lakehouse

E-commerce Data Engineering project using Databricks and Medallion Architecture

## 📌 Project Overview

This project implements an end-to-end e-commerce data engineering pipeline using Databricks and SQL.

The project follows the Medallion Architecture, where raw e-commerce data is progressively transformed through Bronze, Silver, and Gold layers.

The goal is to clean, transform, and aggregate the data into analytical tables that can be used to understand sales, customers, products, categories, and payment performance.

## 🏗️ Architecture

## 🛠️ Technologies Used
- Databricks
- SQL
- Delta Lake
- Medallion Architecture

## 📂 Data Layers

### Bronze Layer(Raw Ingestion)
The landing zone storing source data in its original, immutable format.
Tables:
- df_Customers
- df_OrderItems
- df_Orders
- df_Payments
- df_Products

### Silver Layer(Cleaned & Conformed)
Cleansed, deduplicated, and enriched data modeled into unified, query-ready tables.
- Deduplication & Validation.
- Handling Nulls & Outliers.

### Gold Layer(Aggregated Business Analytics)
Curated, high-performance analytical tables aggregated for BI dashboards and executive reporting.
Tables:
- Daily Sales
- Customer Performance
- Product Performance
- Category Performance
- Payment Performance

## 📊 Gold Layer Analytics
- Daily Sales:
  Daily Business Health.
- Customer Performance:
  Customer Value & Retention.
- Product Performance:
  Product Profitability & Demand.
- Category Performance:
  Category Contribution & Growth.
- Payment Performance:
  Payment Health & Reliability
