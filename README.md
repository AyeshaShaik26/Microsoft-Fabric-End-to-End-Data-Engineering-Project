# Microsoft Fabric End-to-End Data Engineering Project
<img width="1337" height="666" alt="Architecture_Diagram" src="https://github.com/user-attachments/assets/523687fa-d47a-4629-ae3e-39bbd69c7e00" />

## Overview

This repository demonstrates an end-to-end Data Engineering solution built using **Microsoft Fabric**. The project covers the complete data engineering lifecycle, including data ingestion, transformation, storage, modeling, analytics, and deployment using various Microsoft Fabric workloads.

The implementation follows industry-standard data engineering practices such as the Medallion Architecture (Bronze, Silver, Gold), dimensional data modeling, Delta Lake, and CI/CD deployment pipelines.

---

## Project Objectives

* Build an end-to-end data engineering solution using Microsoft Fabric.
* Implement scalable ETL pipelines.
* Process and transform data using PySpark.
* Design a dimensional data warehouse using a Star Schema.
* Store data efficiently using Delta Tables.
* Create analytical datasets for reporting.
* Deploy solutions across environments using Deployment Pipelines.

---

# Architecture

```
               Source Data
          (CSV Files / APIs)
                  │
                  ▼
      Microsoft Fabric Data Factory
                  │
                  ▼
               OneLake
                  │
                  ▼
        Bronze Lakehouse Layer
                  │
          PySpark Transformations
                  │
                  ▼
        Silver Lakehouse Layer
                  │
      Business Transformations
                  │
                  ▼
         Gold Lakehouse Layer
                  │
                  ▼
          Fabric Data Warehouse
                  │
                  ▼
           Power BI Dashboard
```

---

# Technologies Used

* Microsoft Fabric
* OneLake
* Fabric Data Factory
* Fabric Lakehouse
* Fabric Data Warehouse
* PySpark
* SQL
* Delta Lake
---

# Microsoft Fabric Components

## OneLake

* Centralized storage layer
* Unified data lake for analytics
* Supports data virtualization using shortcuts

## Data Factory

* Data ingestion pipelines
* Dynamic pipeline execution
* API integration
* Scheduled ETL workflows

## Lakehouse

* Bronze Layer
* Silver Layer
* Gold Layer
* Delta Tables
* Managed Tables

## Data Engineering

* PySpark notebooks
* Data cleansing
* Data transformation
* Data validation
* Feature engineering

## Data Warehouse

* Dimensional modeling
* Fact and Dimension tables
* SQL Analytics

## Power BI

* Interactive dashboards
* Business reporting
* KPI visualization

---

# Medallion Architecture

### Bronze Layer

* Raw data ingestion
* Source data storage
* Minimal transformations

### Silver Layer

* Cleaned datasets
* Standardized formats
* Data quality improvements

### Gold Layer

* Business-ready datasets
* Aggregated metrics
* Reporting tables

---

# Data Pipeline Workflow

1. Load source data into OneLake.
2. Ingest data using Fabric Data Factory.
3. Store raw data in the Bronze Lakehouse.
4. Transform data using PySpark notebooks.
5. Create Delta Tables.
6. Build the Silver layer.
7. Generate business-ready Gold tables.
8. Design the Star Schema.
9. Load analytical data into the Data Warehouse.
10. Create Power BI dashboards.
11. Deploy across Development, Test, and Production environments.

---

# Star Schema

### Fact Tables

* FactSales

### Dimension Tables

* DimCustomer
* DimProduct
* DimStore
* DimDate

---

# Features Implemented

* Microsoft Fabric Workspace
* OneLake Storage
* Lakehouse
* Data Factory Pipelines
* Dynamic Data Pipelines
* API Data Ingestion
* PySpark Data Transformation
* Delta Tables
* Managed Tables
* Data Virtualization
* Fabric Shortcuts
* Star Schema
* SQL Analytics
* Data Warehouse
* Power BI Reporting
* Deployment Pipelines (CI/CD)

---

# Repository Structure

```
Microsoft-Fabric-End-to-End-Data-Engineering

├── notebooks
├── pipelines
├── sql
├── sample data
├── architecture
├── screenshots
└── README.md
```

---

# Skills Demonstrated

* Microsoft Fabric
* Data Engineering
* ETL Development
* PySpark
* SQL
* Data Modeling
* Delta Lake
* Medallion Architecture
* Data Warehouse Design
* Data Factory Pipelines
---

# Screenshots

Include screenshots of:

* Microsoft Fabric Workspace
* OneLake
* Lakehouse
* Data Factory Pipeline
* PySpark Notebook
* Delta Tables
* SQL Queries
* Star Schema
* Data Warehouse
* Power BI Dashboard
* Deployment Pipeline

---
# Learning Outcomes

Through this project, I gained hands-on experience with:

* Microsoft Fabric architecture
* OneLake storage
* Data ingestion using Data Factory
* PySpark-based data transformations
* Delta Lake implementation
* Star Schema design
* Data Warehouse development
* Power BI reporting
* Deployment Pipelines
* End-to-end analytics solution development

---

# Acknowledgement

This project was developed as a hands-on learning exercise inspired by the Microsoft Fabric Data Engineering (DP-700) course by Ansh Lamba. The implementation, repository organization, documentation, and project presentation have been created by me to demonstrate my practical understanding of Microsoft Fabric concepts.

---

# Author

**Ayesha Shaik**

**Data Engineer**

### Technical Skills

* Microsoft Fabric
* Azure Data Factory
* Azure Data Lake Storage
* PySpark
* SQL
* Python
* Power BI
* Azure Data Engineering
