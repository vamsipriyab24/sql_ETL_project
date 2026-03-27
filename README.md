# sql_datawarehouse_ETL_project
Task - to build a modern data warehouse with mySQL, including ETL processes, data modelling and analytics.

Welcome to the Data Warehouse & Analytics Portfolio! 🚀

This repository showcases a complete, end-to-end data solution—bridging the gap between raw data engineering and actionable business intelligence. Built to demonstrate industry-standard best practices, this project covers everything from architecting a robust data warehouse to delivering high-impact insights.

---
Data Architecture
The data architecture for this project follows Medallion Architecture Bronze, Silver, and Gold layers:
<img width="584" height="326" alt="Screenshot 2026-03-27 150027" src="https://github.com/user-attachments/assets/127b189d-cf97-4db9-9ac3-6074ee81533d" />
Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.
---
 Project Requirements
Building the Data Warehouse (Data Engineering)
Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications
Data Sources: Import data from two source systems (ERP and CRM) provided as CSV files.
Data Quality: Cleanse and resolve data quality issues prior to analysis.
Integration: Combine both sources into a single, user-friendly data model designed for analytical queries.
Scope: Focus on the latest dataset only; historization of data is not required.
Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
BI: Analytics & Reporting (Data Analysis)
Objective
Develop SQL-based analytics to deliver detailed insights into:

Customer Behavior
Product Performance
Sales Trends
These insights empower stakeholders with key business metrics, enabling strategic decision-making.
---
Project Overview
This project involves:

Data Architecture: Designing a Modern Data Warehouse Using Medallion Architecture Bronze, Silver, and Gold layers.
ETL Pipelines: Extracting, transforming, and loading data from source systems into the warehouse.
Data Modeling: Developing fact and dimension tables optimized for analytical queries.
Analytics & Reporting: Creating SQL-based reports and dashboards for actionable insights

