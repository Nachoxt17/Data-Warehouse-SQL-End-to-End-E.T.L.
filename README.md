# Data Warehouse SQL End-to-End E.T.L.

This project presents a complete data warehouse solution, integrating CRM and ERP data into a structured, multi-layer (Bronze, Silver, Gold) ETL pipeline. Using SQL, we design and build data models including star schemas to support high-quality business reporting. Final datasets are visualized with Tableau dashboards, offering actionable insights and clear business value.

## Project Features:

💾 Data architecture and layer design (Bronze, Silver, Gold).
⚙️ SQL-based ETL pipelines: data extraction, transformation, loading.
🔗 Integration of CRM and ERP data sources.
📊 Star schema and dimensional modeling.
📈 Tableau dashboard visualizations for business insights.

## Technologies Used:

1. **Bronze Layer**: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. **Silver Layer**: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. **Gold Layer**: Houses business-ready data modeled into a star schema required for reporting and analytics.

---
## Description

This project involves:

1. **Data Architecture**: Designing a Modern Data Warehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the warehouse.
3. **Data Modeling**: Developing fact and dimension tables optimized for analytical queries.
4. **Analytics & Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## Project Requirements

#### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

#### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Customer Behavior**
- **Product Performance**
- **Sales Trends**
