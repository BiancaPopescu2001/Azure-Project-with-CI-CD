<h1 align="center">Olympics Paris 2024 Data Engineering Project with CI/CD</h1>

![Text](https://github.com/BiancaPopescu2001/Azure-Project-with-CI-CD/blob/main/Arhitecture%20Olympics.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Architecture](#architecture)
- [Data Dictionary](#data-dictionary)
- [Skills Demonstrated](#skills-demonstrated)


## Introduction
This project focuses on building a data engineering pipeline for Olympics Paris 2024 data using the Azure ecosystem.

## Architecture

The project follows the Medallion Architecture, which organizes data into three distinct layers to maintain quality, scalability, and accessibility:

1. **Bronze (Raw) Layer:**

    - **Purpose:** Store raw data as-is from the source without any transformations.
    - **Source:** GitHub APIs, Azure Datalake Gen 2.
    - **Tools:** Azure Data Factory.

2. **Silver (Transformed) Layer:**

    - **Purpose:** Clean, transform, and enrich the raw data for analysis.
    - **Tools:** Azure Databricks.

3. **Gold (Serving) Layer:**

    - **Purpose:** Serve refined data to stakeholders through a data warehouse.
    - **Tools:** Azure Databricks, PowerBI

![Text](https://github.com/BiancaPopescu2001/Azure-Project-with-CI-CD/blob/main/Arhitecture%20Olympics.jpg)

## Data Dictionary

- Azure Cloud Architecture

- Data Ingestion

- ETL Orchestration

- Delta Lake Architecture

- Delta Live Tables (DLT)

- Azure Data Lake Storage Gen2 (ADLS)

- Azure Data Factory (ADF)

- PySpark / Apache Spark

- Databricks Notebooks

- Python Programming

- SQL / SparkSQL

- CI/CD with Azure DevOps

-GitHub Version Control

Data Modeling (Bronze, Silver, Gold Layers)

Data Transformation & Cleaning
