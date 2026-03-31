# Data-Engineering-Project
Data Engineering Project for upskilling

I recently designed and implemented a complete data processing pipeline, covering everything from data ingestion and transformation to data modeling and analysis using Azure services. It helped me simulate a real-world data integration and analytics workflow. Here’s how I structured it
🔹 Data Source & Ingestion:
Created an on-premise MySQL database on my laptop.
Used Self-hosted Integration Runtime to enable Azure Data Factory (ADF) to access on-prem data.
Implemented Lookup + Copy Activity and Dynamic Contents in ADF to efficiently migrate data.
🔹 Data Lake & Medallion Architecture:
Designed a Medallion Architecture in Azure Data Lake Storage (ADLS) with:
Bronze Layer: Raw ingested data.
Silver Layer: Cleaned and transformed data stored as Parquet files.
Gold Layer: Aggregated and business-ready data.
🔹 Transformation & Processing:
Used Databricks (PySpark) to transform raw data into a structured format.
Created a Databricks cluster to process data efficiently.
Stored the refined data in the Silver Layer and performed further aggregations in the Gold Layer.
🔹 Data Warehousing & Analytics:
Created external tables in Synapse Analytics (serverless pool) on top of the Gold Layer.
Connected these tables to Power BI.
Modeled the data in Power BI, implementing star schema principles for optimized reporting.
Built measures and a dashboard to derive insights from the transformed data.
This project covered the entire data lifecycle, from raw ingestion to business insights, strengthening my expertise in Azure Data Factory, Databricks, Synapse, and Power BI.
#End
