# retail-project
A data engineering project that contain making a data pipeline using Microsoft Azure services and visualize this data using Microsoft Power BI and get useful insight from it >

## 🛠️ Tools:

* **Data Ingestion:** Azure Data Factory (ADF)
* **Data Storage:** Azure Data Lake Storage (Gen2)
* **Data Processing:** Azure Databricks (PySpark)
* **Data Visualization:** Microsoft Power BI


## 🏗️ Data Pipeline:
<img width="2551" height="956" alt="image (1)" src="https://github.com/user-attachments/assets/3d04a445-af60-484e-8201-46b197b46ca8" />
# 1.Collecting Data
Collecting raw data from source tables (stores, products, and transactions) then storing them in Azure Data Lake Storage (Gen2) using Azure Data Factory (ADF)
this raw data labeled as bronze layer.

<img width="992" height="724" alt="ADF Pipeline" src="https://github.com/user-attachments/assets/d9db0100-d1f3-4324-92b3-b04bcb0b998e" />

# 2.Data processing
Using pyspark in Azure Databricks to process data
data is cleaned (handling nulls, correcting types) and tables was joined

