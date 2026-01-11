# End-to-End Sales Data Warehouse & Power BI Analytics (Bronze–Silver–Gold)

## Project Overview
This project simulates a real-world sales analytics pipeline where source data is ingested from files, cleaned, transformed, and modeled in a layered SQL data warehouse before being used for business reporting in Power BI.

The goal is to convert raw operational sales data into trusted, analytics-ready datasets for decision-making.

## Architecture & Data Flow
### Bronze Layer — Raw File Ingestion
- Sales data loaded from source files (CSV/Excel)
- Stored without transformation for traceability
### Silver Layer — Data Cleaning & Standardization
- Cleaned Bronze data
- Removed duplicates and nulls
- Standardized formats and data types
### Gold Layer — Business Views for Analytics
- SQL views created by joining Silver tables
- Fact and dimension-style structures
- Optimized for BI reporting
Power BI connects only to Gold-layer views to ensure consistent KPIs and reporting accuracy.
---

## Tools Used
- SQL (Data warehouse and transformations)
- Power BI (Data modeling and dashboards)

