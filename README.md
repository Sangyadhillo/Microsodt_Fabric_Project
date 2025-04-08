# Project Title :- E-commerce Data Lakehouse using Microsoft Fabric with Medallion Architecture (Bronze-Silver-Gold)

# Tools & Technologies
Microsoft Fabric

Lakehouse Architecture

Data Pipelines

Dataflow Gen2

Spark Notebooks

Power BI (for final reporting)

OLAP Warehouses

# Project Overview
This project demonstrates how to build a robust, scalable data architecture for an e-commerce domain using the Medallion Architecture pattern on Microsoft Fabric. 
It organizes the data into Bronze (Raw), Silver (Cleaned), and Gold (Aggregated) layers, enabling efficient data transformation, storage, and consumption for business intelligence use cases.

# Workflow Summary
## 🥉 Bronze Layer
Created a Lakehouse to store raw CSV files.

Uploaded and verified e-commerce data files.

Organized raw ingestion as the foundation of the pipeline.

## 🥈 Silver Layer
Created a separate workspace for the Silver Lakehouse.

Designed Data Pipelines to convert raw CSVs into structured tables.

Used Get Metadata and ForEach to dynamically handle multiple files.

Performed data transformations using Spark Notebooks or Dataflow Gen2.

## 🥇 Gold Layer
Connected to a Warehouse for efficient analytical querying.

Loaded cleaned data from the Silver layer using Dataflow Gen2.

Designed for non-technical users to easily access and use the data.

## 📊 Reporting
Connected BI tools like Power BI to the warehouse.

Created dashboards and visualizations for end users.

Configured data refresh schedules for pipelines, flows, and notebooks.

# Key Takeaways

Got practical experience working with data from start to finish using Microsoft Fabric.

Set up smart systems to handle files and automatically clean and transform the data.

Used best practices to organize data using the Medallion Architecture (Bronze, Silver, Gold layers).

Made it easy for others to explore and use the data by creating user-friendly, ready-to-use reports.
