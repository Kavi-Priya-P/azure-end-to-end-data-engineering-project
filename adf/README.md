# Azure Data Factory

This folder contains screenshots of the pipelines used in the project.

## 📌 Pipelines Included
### 1. Initial Load Pipeline
- Copies full data from SQL/CSV to ADLS Raw (Bronze)
- Executes Databricks notebook for processing

### 2. Incremental Load Pipeline
- Detects new/updated records using watermark column
- Sends incremental data to ADLS Raw
- Triggers Databricks transformation job

Screenshots:
- ADF - GitToCopyData Pipeline
- InitialLoad_Successful
- ADF - Incremental Pipeline - Initial Load
- ADF - Incremental Pipeline - Incremental Load
