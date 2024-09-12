# Olympic Games Data Engineering Pipeline (using Azure)

This repository contains the implementation of an ETL pipeline using **Azure Cloud** services to process **Olympic Games data** from Kaggle.

## Overview

The project extracts data from Kaggle, transforms it using **Apache Spark** in **Azure Databricks**, loads the cleaned data into **Azure Data Lake Storage**, and analyzes it using **Azure Synapse Analytics**.

![architecture](https://github.com/user-attachments/assets/a02c4e91-7a3b-46a2-b2fc-c1811c4ed1df)


### Objectives:
- **Extract** data from Kaggle.
- **Transform** using Spark.
- **Load** into Azure Data Lake Storage.
- **Analyze** using SQL and visualizations in Synapse.

## Solution

1. **Data Extraction**: 
   - Data is extracted from Kaggle via **Azure Data Factory** and stored in **Azure Data Lake Storage**.
2. **Data Transformation**: 
   - **Azure Databricks** and **Apache Spark** are used to clean and transform the data.
3. **Data Loading**: 
   - The transformed data is reloaded into **Azure Data Lake Storage**.
4. **Data Analysis**: 
   - **Azure Synapse Analytics** runs SQL queries and generates visualizations.

## Tech Stack

- **Azure Data Factory**: Data extraction and orchestration.
- **Azure Databricks**: Data transformation using Apache Spark.
- **Azure Data Lake Storage**: Scalable data storage.
- **Azure Synapse Analytics**: Data querying and visualization.

## Insights

The project allows analysis of Olympic data, such as:
- **Medal Distribution** by country and year.
- **Athlete Trends** in age and performance.
- **Event Performance** analysis across nations.

## Repository Structure

- `notebooks/`: Databricks notebooks for data transformation.
- `queries/`: SQL queries for analysis in Synapse.

## How to Run

1. Set up **Azure Data Factory**, **Databricks**, **Data Lake Storage**, and **Synapse Analytics**.
2. Extract data from Kaggle via **Data Factory**.
3. Transform the data in **Databricks**.
4. Load and query the data in **Synapse**.

## Preview
[Uploading Untitled video - Made with Clipchamp.mp4…](https://github.com/user-attachments/assets/e10dccba-78c3-4d9e-bb31-78b58cb25025)
