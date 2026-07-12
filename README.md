# Retail Data Consolidation ETL Pipeline

An end-to-end Data Engineering project built with **Databricks** following the **Medallion Architecture (Bronze, Silver, Gold)**.

## Business Problem

**Atlikon** acquired **SportsBar**, but both companies stored data using different schemas and data standards. The acquisition introduced challenges such as:

- Schema mismatches
- Missing and inconsistent data
- Duplicate records
- No unified analytics layer

The objective was to build a reliable data platform that consolidates data from both companies into a single Lakehouse for reporting and analytics.

## Solution

Built an ETL pipeline that:

- Ingests raw data from Amazon S3
- Cleans and standardizes data
- Resolves schema differences between both companies
- Processes historical and incremental loads
- Produces analytics-ready Gold tables for dashboards

## Tech Stack

- Databricks
- Apache Spark (PySpark)
- SQL
- Delta Lake
- Amazon S3
- Python
- Medallion Architecture

## Architecture

```
Amazon S3
    ↓
 Bronze
    ↓
 Silver
    ↓
 Gold
    ↓
 Dashboards
```

## Key Skills

- ETL Development
- Data Cleaning
- Data Modeling
- Delta Lake

<img width="20005" height="11129" alt="project_architecture" src="https://github.com/user-attachments/assets/1806a154-10e5-46e3-80db-4bee7bd57500" />
<img width="835" height="455" alt="image" src="https://github.com/user-attachments/assets/b78f6fe1-e7d4-486e-bd94-84b72f8b36ec" />
<img width="1394" height="751" alt="image" src="https://github.com/user-attachments/assets/bd69b0af-da52-4014-a678-731851df3169" />



- Incremental Processing
- PySpark
- Spark SQL
