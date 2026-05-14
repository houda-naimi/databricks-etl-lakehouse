# Databricks ETL Lakehouse

End-to-end Data Lakehouse solution built on **Databricks** using the Medallion Architecture (Bronze, Silver, Gold).  
This project demonstrates real-world data engineering pipelines using **Spark, PySpark, SQL, Delta Lake, and Unity Catalog**.

---
## Project Goals

- Build a scalable Lakehouse architecture
- Implement an end-to-end ETL pipeline
- Ensure data quality across layers
- Prepare data for analytics and reporting
---
## Technologies Used

![Databricks](https://img.shields.io/badge/Databricks-EA1000?style=for-the-badge&logo=databricks&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-2C2D72?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=postgresql&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge)
![Unity Catalog](https://img.shields.io/badge/Unity_Catalog-6A5ACD?style=for-the-badge)

![Databricks](https://img.shields.io/badge/Databricks-EA1000?style=flat-square&logo=databricks&logoColor=white)

---
## Architecture

This project follows the **Medallion Architecture**, which organizes data into three layers:

### Bronze Layer
- Raw data ingestion from source systems (CSV, files, etc.)
- Schema inference and storage as **Delta tables**
- Acts as the landing zone for raw data

### Silver Layer
- Data cleaning and standardization
- Type casting and data validation
- Deduplication and quality checks

### Gold Layer
- Dimensional data modeling (business transformations)
- Aggregated and curated datasets
- Ready for BI tools and analytics

---
## Data Flow

Source Files → Bronze (Raw Data) → Silver (Cleaned Data) → Gold (Business Data Models)

---
