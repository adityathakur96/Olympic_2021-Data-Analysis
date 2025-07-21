# 🏅 Olympic Sales Data Engineering Project – End-to-End ETL with Microsoft Azure

📌 Project Summary

In this project, I developed an end-to-end ETL pipeline to process and analyze Olympic sales data using the Microsoft Azure ecosystem. The project demonstrates cloud-based data engineering using tools such as:

* Azure Databricks for scalable data transformation with PySpark

* Azure Data Factory (ADF) for orchestrating ETL pipelines

* Azure Data Lake Storage Gen2 (ADLS) for storing raw and processed data

* Azure Synapse Analytics for querying and analyzing the final transformed data

This project showcases the implementation of a complete data pipeline—starting from raw data ingestion to meaningful insights—using Apache Spark with Python.


📁 Dataset Overview

This project uses a collection of Olympic event datasets that simulate real-world sports and sales data for analysis. The dataset consists of multiple CSV files covering athletes, teams, coaches, entries by gender, and medals.


Each file provides a different perspective of the Olympic data:

* Athletes.csv: Details of individual athletes, including their names, disciplines, genders, and nationalities.

* Coaches.csv: Information on coaches participating in different Olympic disciplines.

* EntriesGender.csv: Gender-wise participation statistics by country and discipline.

* Medals.csv: Medal records for events, listing athletes, countries, event names, and medal types (Gold, Silver, Bronze).

* Teams.csv: Lists teams representing different countries across disciplines.


These files were uploaded to Azure Data Lake Storage Gen2 and served as the raw input for the ETL pipeline. Though fictional, the dataset closely mimics real-world Olympic reporting data and was ideal for testing cloud-based data engineering workflows.


🧱 Pipeline Flow

# 1. Extraction & Ingestion

* Raw data is uploaded to Azure Data Lake Storage Gen2.

* Azure Data Factory pipelines are created to automate the flow of data from raw ("bronze") layers to processed ("silver" and "gold") layers.

# 2. Transformation

* Data is processed and transformed using PySpark in Azure Databricks.

* Key transformations include data cleaning, deriving new columns, aggregating sales by region/sport, and filtering based on conditions.

# 3. Loading & Analysis

* Transformed data is stored back into ADLS Gen2.

* Azure Synapse Analytics is used to query the transformed datasets using SQL scripts to extract valuable insights.





⚠️ Note: This project was built using a Microsoft Azure free trial. As the trial period has ended, the Azure resources (Databricks workspace, Data Factory pipelines, Synapse instance, and ADLS) are no longer active.

However, the entire pipeline was successfully implemented and tested. Below are screenshots from the actual project execution: **

* Azure Data Factory pipeline overview.

* Databricks notebook showing transformations using PySpark.

* ADLS directory structure (raw & processed data).

* Synapse SQL script execution with results.



** The ScreenShots of corresponding project are in the folder called Images. 



