# Azure Healthcare Data Engineering Project

## Project Overview

This project demonstrates an end-to-end Healthcare Data Engineering pipeline built on the Microsoft Azure cloud platform using Azure Data Factory, Azure Databricks, ADLS Gen2, and PySpark.

The solution ingests healthcare data from APIs and CSV sources, processes it through the medallion architecture layers (Landing, Bronze, Silver, Gold), and stores the transformed data in Parquet and Delta formats for analytics and reporting.


## Technologies Used

- Azure Data Factory (ADF)
- Azure Data Lake Storage Gen2 (ADLS Gen2)
- Azure Databricks
- PySpark
- Azure Key Vault
- Git & GitHub
- Parquet Format
- Delta Lake

---

## Project Architecture

Source Systems/API/CSV Files
        ↓
Azure Data Factory
        ↓
Landing Container
        ↓
Azure Databricks (PySpark Transformations)
        ↓
Bronze Layer
        ↓
Silver Layer
        ↓
Gold Layer

---

## Data Sources Used

### API Sources
- ICD Codes API
- NPI Registry API

### File-Based Sources
- CPT Codes CSV
- Claims Data CSV

---

## Key Implementations

- Incremental Load
- Full Load Pipelines
- SCD Type 2 Implementation
- Parquet File Conversion
- Delta Lake Storage
- Metadata Driven Pipelines
- API Data Extraction
- Data Cleansing using PySpark

---

## Pipeline Details

### ADF Pipelines
- EMR Source to Landing
- Metadata-driven copy pipeline
- Copy Activities
- Parameterized Pipelines

### Databricks Processing
- ICD API Extraction
- NPI API Extraction
- Claims Processing
- CPT Codes Transformation

---

## Security

- Azure Key Vault integration used for secrets management
- Storage Account access controlled securely

---
## Learning Outcomes

Through this project, I learned:

- Azure Data Factory pipeline development
- Databricks notebook development
- PySpark transformations
- Incremental and Full Load concepts
- SCD Type 2 implementation
- Git and GitHub integration
- Cloud-based data engineering architecture

---

## Author

Vinay 
