# Azure End-to-End Data Engineering Project

## 📌Project Overview
This project demonstrates an end-to-end Azure Data Engineering pipeline built using Azure Data Factory, Azure Data Lake Gen2, Azure Databricks, PySpark, and Delta Lake.
It follows the Medallion Architecture (Bronze → Silver → Gold) and simulates real-world enterprise data engineering scenarios such as incremental loading, data transformations, and Slowly Changing Dimensions (SCD Type 2).

The goal of this project is to showcase developer-focused Azure Data Engineering skills aligned with current industry expectations.

## 🏗️ Architecture Overview
**Source → Azure Data Factory → ADLS Gen2 → Azure Databricks → Delta Lake (Bronze/Silver/Gold)**

-Azure Data Factory orchestrates ingestion

-Azure Data Lake Gen2 stores raw and processed data

-Azure Databricks performs transformations using PySpark

-Delta Lake ensures optimized, reliable data storage

## 🧱 Medallion Architecture

**🟤 Bronze Layer**

-Raw data ingestion from source

-Minimal transformations

-Schema preserved as received

**⚪ Silver Layer**

-Data cleansing and validation

-Deduplication

-SCD Type 2 implementation

-Business-ready datasets

**🟡 Gold Layer**

-Aggregated and curated data

-Fact and dimension tables

-Optimized for analytics and reporting


## ⚙️ Technologies Used
**Cloud:** Microsoft Azure

**Orchestration:** Azure Data Factory

**Storage:** Azure Data Lake Storage Gen2

**Processing:** Azure Databricks

**Big Data:** PySpark, Spark SQL

**Storage Format:** Delta Lake

**Version Control:** Git & GitHub

## 🔄 Data Ingestion (Azure Data Factory)
-Designed parameterized pipelines

-Implemented **incremental loading** using watermark logic

-Configured datasets, linked services, and triggers

-Ingested data into Bronze layer in ADLS Gen2

## 🔁 Data Transformation (Azure Databricks)
-Read data from ADLS Gen2

-Applied transformations using PySpark

-Implemented:

    -Incremental processing
 
    -Delta Lake MERGE operations
 
    -SCD Type 2 logic

-Stored curated data in Silver and Gold layers

## 🕰️ Slowly Changing Dimensions (SCD Type 2)

-Maintains historical records of dimension changes

-Uses effective start/end dates and active flags

-Implemented using PySpark and Delta Lake

## 🎯 Key Outcomes

-Built a complete Azure Data Engineering pipeline from scratch

-Applied real-world data engineering concepts

-Strengthened hands-on skills in ADF, Databricks, PySpark, and Delta Lake

-Designed a project aligned with Azure Data Engineer (Developer) roles

## 👩‍💻 Author

**Kavi Priya P**

Azure Data Engineer

📍 Chennai, India

🔗 LinkedIn: https://www.linkedin.com/in/kavi-priya-pandian/

🔗 GitHub: https://github.com/Kavipriya-Pandian
