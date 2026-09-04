# E-Commerce Data Warehouse & Analytics Project

**Author:** Amratanshu Dubey

## 📌 Project Overview

This project is an end-to-end E-Commerce Data Warehouse and Analytics solution.

The goal is to collect data from multiple sources, process and clean it using Python and SQL, build a structured Data Warehouse, and generate meaningful business insights using Power BI and Excel.

## 🎯 Project Objective

Build a scalable and reliable data pipeline that transforms raw e-commerce data into business-ready information for analytics and decision-making.

## 🏗️ Project Architecture

Data Sources
→ Python ETL
→ Bronze Layer
→ Silver Layer
→ Gold Layer
→ Power BI / Excel / FastAPI

## 📊 Data Sources

The project will use multiple data sources such as:

- CSV files
- Excel files
- API data

These sources will contain information related to:

- Customers
- Products
- Orders
- Sales
- Payments

## 🔄 Data Engineering

The data pipeline will include:

- Data ingestion using Python
- Data cleaning and validation
- Data transformation
- Data quality checks
- Loading data into SQL Server
- Incremental data loading
- ETL logging and error handling

## 🥉 Bronze Layer

The Bronze layer stores raw data received from the source systems with minimal transformation.

Purpose:

- Preserve original data
- Maintain traceability
- Support data validation and debugging

## 🥈 Silver Layer

The Silver layer contains cleaned and standardized data.

Operations include:

- Removing duplicates
- Handling missing values
- Standardizing formats
- Correcting data types
- Applying data quality rules

## 🥇 Gold Layer

The Gold layer contains business-ready data designed for analytics.

It will include:

- Fact tables
- Dimension tables
- Star schema
- Business metrics
- Analytical views

## 📈 Analytics & Reporting

Power BI and Excel will be used to analyze the warehouse data.

Key business questions include:

- What is the total revenue?
- What are the top-selling products?
- Which customers generate the most revenue?
- What are the monthly sales trends?
- Which product categories perform best?
- Which regions/customers/products need attention?

## 🛠️ Technologies Used

- **SQL Server / SSMS** – Database & Data Warehouse
- **SQL** – Data transformation and analytics
- **Python** – ETL, data ingestion and validation
- **Pandas** – Data manipulation
- **NumPy** – Data processing
- **Requests** – API data ingestion
- **Power BI** – Dashboards and visualization
- **Excel** – Ad-hoc analysis
- **FastAPI** – REST API layer
- **Git & GitHub** – Version control
- **Draw.io** – Architecture and data model diagrams
- **Notion** – Project management and documentation

## 📁 Project Structure

```text
E-Commerce_Data_Warehouse_Project/
│
├── 01_Raw_Data/
├── 02_SQL/
├── 03_Data_Warehouse/
├── 04_Power_BI/
├── 05_Excel/
├── 06_FastAPI/
├── 07_DrawIO/
├── 08_Documentation/
└── README.md
