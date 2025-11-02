# retail-project
A data engineering project that contain making a data pipeline using Microsoft Azure services and visualize this data using Microsoft Power BI and get useful insight from it >

## 🛠️ Tools:

* **Data Ingestion:** Azure Data Factory (ADF)
* **Data Storage:** Azure Data Lake Storage (Gen2)
* **Data Processing:** Azure Databricks (PySpark)
* **Data Visualization:** Microsoft Power BI


## 🏗️ Data Pipeline:
<img width="2551" height="956" alt="image (1)" src="https://github.com/user-attachments/assets/3d04a445-af60-484e-8201-46b197b46ca8" />

### 1.Collecting Data
Collecting raw data from source tables (stores, products, and transactions) then storing them in Azure Data Lake Storage (Gen2) using Azure Data Factory (ADF)
this raw data labeled as bronze layer.

<img width="992" height="724" alt="ADF Pipeline" src="https://github.com/user-attachments/assets/d9db0100-d1f3-4324-92b3-b04bcb0b998e" />

### 2.Data processing
Using pyspark in Azure Databricks to process data
data is cleaned (handling nulls, correcting types) and tables was joined

### 3.Gold layer 
data is organized in 2 tables (summary gold, products gold) working on top contries for fast response

## Data visualize
Using Microsoft Power BI the final report contains 2 pages summarizing data to visual insights

### Page 1:Summary of financial and geographical performance
This page summarize overall performance

* **KPIs:**Total amount ,total products count , store name.
* **Visuals:** A geographical map (`Map`) for Total amount, (`Pie chart`) for total count of products , (`Clustered Column chart`) for some by store name and quantity of products

### Page 2:Analysis of country with products
 
* **KPIs:**Total quantity by country ,total amount , sum of price. 
* **Visuals:** A (`Table`) that gives detailed insights about every country and total amount of each product , (`Pie chart`) about sum of quantity between countries , (`Stacked bar chart`) between countries and catagories

  ## 🏁 Conclusion:
Using Cloud Services this project turns raw data to usfel insights by Azure Data Factory, Azure Databricks, and Azure Data Lake Storage.

The final result is 2 pages Power BI that turns complex data into usfel insights. 

  ## 👤 Author:
  Omar Farg
