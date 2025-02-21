
# Data Warehouse and Analytics Project

Welcome to the **Data Warehouse and Analytics Project** repository! 📊
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project, it highlights industry best practices in SQL and analytics.

---
## 🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture drawio](https://github.com/user-attachments/assets/18bcd163-278c-4c14-b408-1b44adf29a2e)

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## 🛠️ Important Tools used in the Project:
- **[Datasets](datasets/):** Access to the project dataset (csv files). 
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database. 
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.
- **[DrawIO](https://www.drawio.com/):** Design data architecture, models, flows, and diagrams.
- **[Notion Project Steps](https://www.notion.so/Data-Warehouse-Project-18f19c934bb4800da2f7cf781db308fe?pvs=4):** Access to All Project Phases and Tasks.


---

## 🚀 Project Requirements

### Building the Data Warehouse 

#### Objective
Build a modern SQL Server data warehouse to centralize sales data, enabling analytical reporting and data-driven decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Clean and resolve any data quality issues before analysis.
- **Integration**: Merge both sources into a single, structured data model optimized for analytical queries.
- **Scope**: Focus only on the latest dataset; historical data storage is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
---

### BI: Analytics & Reporting 

#### Objective
Develop SQL-based analytics to generate key business insights on:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

🎯 These insights will provide stakeholders with essential metrics to drive strategic decision-making.

---


## 🛡️ License

This project is licensed under the [MIT License](LICENSE).

## 🌟 About Me

Hey there I'm **Charles-emil Fouché** ! Curently working as Sales Man in Darty. I’m on a mission to transition  from Sales Man to a Data Analyst !

Let's stay in touch! Feel free to connect with me:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/charles-emil-fouche/)

