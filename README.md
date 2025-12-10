# 🎶 Spotify End-to-End Data Engineering Project

This project demonstrates a complete **end-to-end data engineering pipeline** built on the Azure cloud ecosystem. It simulates real-world data ingestion, transformation, and modeling using modern data engineering best practices.

---

## 🚀 Project Overview

This project implements a **Medallion Architecture (Bronze → Silver → Gold)** using real data engineering tools and patterns, focused on reliability, scalability, and data quality.

The pipeline processes Spotify-like data from raw ingestion to analytics-ready tables.

---

## 🏗️ Architecture

The solution is built using the following layers:

- **Bronze Layer**: Raw data ingestion from Azure SQL Database to Azure Data Lake in Parquet format.
- **Silver Layer**: Data cleansing, standardization, and transformations using **Databricks + PySpark (Auto Loader & Structured Streaming)**.
- **Gold Layer**: Data modeling, quality rules, and Slowly Changing Dimensions (SCD Type 2) implemented with **Delta Live Tables**.

---

## ⚙️ Technologies Used

- Azure SQL Database  
- Azure Data Factory (ADF)  
- Azure Data Lake Storage Gen2  
- Databricks  
- PySpark  
- Delta Lake  
- Delta Live Tables (DLT)

---

## 🔄 Key Features

✅ Incremental data loads  
✅ Streaming ingestion with Auto Loader  
✅ Schema evolution handling  
✅ Checkpointing and fault tolerance  
✅ CDC with SCD Type 2 logic  
✅ Data quality expectations

---

## 🧠 What I Learned

This project helped me apply real-world concepts such as:

- Medallion architecture design  
- Streaming vs batch processing  
- Idempotent data pipelines  
- Data versioning and historical tracking  
- Building production-style data platforms

---

## 📁 Project Structure
spotify_end_to_end_project/
│── src/
│── notebooks/
│── utils/
│── resources/
│── databricks.yml
│── azure_data_factory/

## 🧪 How to Run (Optional section, you can fill later)

1. Configure Azure resources
2. Update storage and SQL connection strings
3. Run ADF pipelines
4. Execute Databricks notebooks
5. Start DLT pipeline


