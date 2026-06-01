Architecture Overview

Source Systems
1) Hospital A
2) Hospital B
3) ICD API
4) NPI API

Storage Layers
1) Landing
2) Bronze
3) Silver
4) Gold

Processing
1) Azure Data Factory
2) Azure Databricks

Transformations
1) Data Quality Checks
2) SCD Type 2 for Patients, Encounters, Transactions

Output
1) Gold Layer for Analytics and Reporting
