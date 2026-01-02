# End-to-End Azure Data Engineering Project (Medallion Architecture)

## Project Overview

In this project, I built an industry-ready Azure data engineering pipeline from start to finish, applying modern cloud best practices and the **Medallion Architecture (Bronze → Silver → Gold)**.

The goal was to simulate a real-world production data platform, from raw data ingestion to analytics-ready datasets and business intelligence reporting using core Azure services and scalable design patterns.

This project is part of my personal challenge to strengthen my Azure data engineering skills, build portfolio-grade solutions, and deepen my understanding of production data systems.

---

## Architecture Overview

The pipeline follows a layered Medallion Architecture:

- **Bronze Layer**: Raw data ingestion (CSV / Parquet)
- **Silver Layer**: Cleaned, validated, and transformed data
- **Gold Layer**: Aggregated, analytics-ready datasets optimized for reporting

### High-Level Flow

1. Data ingestion using **Azure Data Factory**
2. Storage in **Azure Data Lake Storage Gen2**
3. Transformations using **Azure Databricks (PySpark & Delta Lake)**
4. Curated data modelled in **Azure SQL Database**
5. Business insights visualised using **Power BI**

---

## What I Built

### 🔹 Data Ingestion
- Automated ingestion pipelines using **Azure Data Factory**
- Source data ingested into ADLS Gen2
- Data stored efficiently in **Parquet format**

### 🔹 Data Processing & Transformation
- Implemented **Medallion Architecture** in Azure Databricks
- Used **PySpark** for:
  - Data cleaning and validation
  - Schema enforcement
  - Deduplication and error handling
- Leveraged **Delta Lake** for reliable, scalable transformations

### 🔹 Data Modeling
- Designed a **star schema** in **Azure SQL Database**
- Created fact and dimension tables optimized for analytics
- Ensured consistency between Gold layer and reporting layer

### 🔹 Analytics & Visualization
- Built interactive **Power BI dashboards**
- Created calculated measures using **DAX**
- Connected Power BI directly to Azure SQL for reporting

---

## Technologies Used

- **Azure Data Factory (ADF)** – Data orchestration & ingestion  
- **Azure Databricks** – Data processing with PySpark  
- **Delta Lake** – Reliable data storage & versioning  
- **Azure Data Lake Storage Gen2 (ADLS)** – Scalable data storage  
- **Azure SQL Database** – Analytics-ready relational layer  
- **Power BI** – Data modeling & visualization  
- **Medallion Architecture** – Data platform design framework  

---

## Key Skills Demonstrated

- Designing production-grade Azure data pipelines
- Implementing Medallion Architecture end to end
- Building scalable ETL workflows
- Writing PySpark transformations
- Data modeling with star schemas
- Power BI reporting and DAX calculations
- Cloud cost-awareness and optimization
- Data validation and error handling

---

## Learning Reference

This project was inspired by hands-on learning resources and tutorials, which I adapted and implemented independently to reinforce real-world understanding:

🔗 Reference tutorial repository:  
https://github.com/manish040596/azure-data-engineering-project



📌 *Feel free to explore the repository, review the architecture, and connect with me to discuss Azure data engineering or cloud analytics.*
