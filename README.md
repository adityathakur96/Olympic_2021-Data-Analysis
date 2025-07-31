# 🏅 **Olympic21 Data Engineering Project – End-to-End ETL with Microsoft Azure**

---

## 📌 **Project Summary**

Welcome to the **Olympic21 Data Engineering Project**, an end-to-end data engineering solution based on the **Tokyo Olympic 2021 dataset**. This project demonstrates the design and implementation of a cloud-native ETL pipeline using the Microsoft Azure ecosystem, including:

- **Azure Databricks:** Scalable data transformation with PySpark  
- **Azure Data Factory (ADF):** Powerful ETL pipeline orchestration  
- **Azure Data Lake Storage Gen2 (ADLS):** Secure and scalable storage for raw & processed data  
- **Azure Synapse Analytics:** Advanced querying and analytics on transformed data  

This project highlights the journey from **raw data ingestion** to actionable insights, all powered by **Apache Spark with Python** on Azure.

---

## 📁 **Dataset Overview**

The project analyzes a suite of **Olympic event datasets** simulating real-world sports records and participation analytics. These datasets, in CSV format, cover multiple perspectives:

- **Athletes.csv:** Athlete details (name, discipline, gender, nationality)
- **Coaches.csv:** Coaches' information by discipline
- **EntriesGender.csv:** Gender-wise participation by country and sport
- **Medals.csv:** Medals records (athletes, countries, events, Gold/Silver/Bronze)
- **Teams.csv:** Team lists by country and discipline

All files are stored in **Azure Data Lake Storage Gen2** as raw input for the ETL pipeline. While fictional, the data structure closely mimics real Olympic datasets, making it ideal for learning and prototyping.

---

## 🧱 **Pipeline Flow**

### 1️⃣ **Extraction & Ingestion**
- Raw data files are uploaded to **ADLS Gen2** ("bronze" layer).
- **Azure Data Factory** pipelines automate data flow from raw to processed layers ("silver" and "gold").

### 2️⃣ **Transformation**
- Data transformation is performed in **Azure Databricks** using **PySpark**.
- **Key transformations:**
    - Data cleaning and validation
    - Deriving new columns for deeper insights
    - Aggregating participation and medal tallies by region, country, or sport
    - Filtering and joining datasets for analytics

### 3️⃣ **Loading & Analysis**
- Transformed data is stored back in **ADLS Gen2**.
- **Azure Synapse Analytics** is used to run advanced SQL queries and extract meaningful insights.

---

## 📸 **Project Implementation Screenshots**

Screenshots of the actual project execution (including pipeline overviews, code, and results) are provided in the **`Images` folder**:

- **Azure Data Factory** pipeline overview
- **Databricks notebook** showing transformations using PySpark
- **ADLS** directory structure (raw & processed data)
- **Synapse** SQL script execution with results

---

## ⚠️ **Note**

This project was built using a **Microsoft Azure free trial**. As the trial period has ended, the Azure resources (**Databricks workspace, Data Factory pipelines, Synapse instance, and ADLS**) are **no longer active**.

However, **the entire pipeline was successfully implemented and tested**.  
You can find screenshots from the actual project execution in the **`Images` folder**.

---

## 🤝 **Contributions & Feedback**

Have suggestions or want to collaborate? **Open to feedback and improvements.**  
Feel free to raise an issue or [connect with me on LinkedIn](https://www.linkedin.com/in/adityathakur9617/)!

---

## 📌 **Disclaimer**

All data used in this project is **fictional** and intended solely for **educational and demonstration purposes**. Not for commercial deployment.

---
