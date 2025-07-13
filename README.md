# 🏢 Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 🚀  
This project showcases a complete data warehousing and analytics solution — from raw data ingestion to business insights. Designed as a **portfolio project**, it demonstrates industry-standard practices in **data engineering**, **ETL pipelines**, and **analytical modeling**.

---

## 🏗️ Data Architecture

The architecture follows the **Medallion Architecture** approach, utilizing three layers:

- **🔹 Bronze Layer**:  
  Stores raw data directly from source systems (e.g., CSV files) with minimal transformation. Data is ingested into a SQL Server database.

- **⚪ Silver Layer**:  
  Performs data cleansing, standardization, and normalization to prepare for data analysis.

- **🟡 Gold Layer**:  
  Contains business-ready data, modeled in a **star schema** (fact/dimension tables) optimized for reporting and BI tools.

---
## 📖 Project Overview

This project includes:

- **📐 Data Architecture**:  
  Designing a modern Data Warehouse using the Medallion Architecture.

- **⚙️ ETL Pipelines**:  
  Extracting, transforming, and loading data from source systems into the warehouse.

- **🗃️ Data Modeling**:  
  Building **fact** and **dimension** tables with surrogate keys, using techniques such as `ROW_NUMBER()`, optimized for analytical queries.

---
