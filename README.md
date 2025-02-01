# Apple Inc. ETL Project Using Databricks DBFS and PySpark  

This project demonstrates an ETL pipeline for analyzing sample sales data for Apple Inc. The data is provided in three CSV files:  

- **Customer_Updated.csv**  
- **Products_Updated.csv**  
- **Transaction_Updated.csv**  

These files are uploaded to **Databricks DBFS** and processed using **PySpark** notebooks. The solution follows the **Factory Pattern** to modularize the Extract, Transform, and Load (ETL) processes.

---

## Project Structure  

- **source_files/**  
  - CSV files uploaded to Databricks DBFS.  
- **notebooks/**  
  - ETL Notebooks implementing each workflow in PySpark and factory classes for extraction and loading operations.  
- **README.md**  
  - Project documentation.  

---

## ETL Workflows  

This project addresses four analytical queries through separate ETL workflows:  

### 1. Customers Who Bought AirPods After Buying iPhone  
Extracts a list of customers who purchased AirPods following an iPhone purchase.  

### 2. Customers Who Bought Only iPhone and AirPods  
Filters and lists customers who exclusively purchased iPhone and AirPods (no other products).  

### 3. List All Products Bought by Customers After Their Initial Purchase  
Provides a comprehensive list of products purchased by each customer after their first transaction.  

### 4. Average Time Delay Between Buying iPhone and AirPods  
Calculates the average time delay between purchasing an iPhone and subsequently purchasing AirPods.

---

## Technology Stack  

- **Databricks**: Data analytics and processing platform  
- **Databricks DBFS**: Data storage for CSV files  
- **PySpark**: Distributed data processing  
- **Factory Pattern**: Design pattern to modularize ETL logic  

---

## Project Setup  

1. Clone this repository:  
   ```bash
   git clone https://github.com/NikhilLIv/apple-data-analysis
