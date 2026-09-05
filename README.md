# AdventureWorks Multidimensional OLAP Model

## 📌 Project Overview
This project features a Multidimensional OLAP (Online Analytical Processing) model built on top of the **AdventureWorksDW2019** Data Warehouse. Developed using **SQL Server Analysis Services (SSAS)**, the model provides an optimized structure for complex business reporting and analytical querying without the need for custom MDX scripting.

## 🏗️ Architecture & Cube Design
The solution is designed to aggregate enterprise data into structured cubes, enabling high-performance slicing and dicing of metrics across various business axes.
*   **Data Source View (DSV):** Configured to establish logical relationships between fact and dimension tables, including snowflake schema patterns.
*   **Cubes:** Includes the core `Fact Reseller Sales` cube to analyze reseller performance, sales quotas, and overarching revenue trends.
*   **Dimensions:** Utilizes shared, conformed dimensions such as `Dim Date`, `Dim Employee`, `Dim Product` (structured hierarchically with Category and Subcategory), and `Dim Customer`.
*   **Measures:** Aggregates key quantitative metrics from `FactResellerSales` and `FactSalesQuota` for immediate analytical consumption.

## 🛠️ Technologies & Tools
*   **SQL Server Analysis Services (SSAS):** Used for designing the multidimensional model, dimensions, and cube structures.
*   **SQL Server Management Studio (SSMS):** Used for extracting the underlying schema (DDL) of the data warehouse.
*   **Visual Studio:** IDE utilized for SSAS project configuration, establishing the DSV, and mapping dimension usage.

## 🖼️ Snapshots
## Fact Internet Sales Cube
<img width="775" height="756" alt="FactInternetSalesCube" src="https://github.com/user-attachments/assets/e793ad31-2a40-4272-9a86-b3b9b0d76bc6" />

## Fact Reseller Sales Cube
<img width="771" height="762" alt="FactResellerSalesCube" src="https://github.com/user-attachments/assets/8e3d8e98-e6b2-41ee-9e4d-8bb2ed29b1d6" />

