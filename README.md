
# Netflix Azure Data Engineering Project





## Project Overview

This project implements an end-to-end data engineering pipeline for processing Netflix datasets using Microsoft Azure services and Azure Databricks.

The project demonstrates data ingestion, data transformation, validation, and workflow orchestration using cloud-based data engineering tools.

## Technologies Used

* Microsoft Azure
* Azure Data Factory (ADF)
* Azure Data Lake Storage Gen2
* Azure Databricks
* Apache Spark / PySpark
* Delta Lake
* Python
* GitHub

## Dataset

The project uses Netflix-related CSV datasets, including:

* Netflix Titles
* Netflix Cast
* Netflix Categories
* Netflix Countries
* Netflix Directors

## Project Workflow

1. **Data Ingestion:** Ingest raw Netflix CSV files into Azure Data Lake Storage using Azure Data Factory.
2. **Bronze Layer:** Process incoming files using Azure Databricks and Auto Loader.
3. **Silver Layer:** Clean, transform, and validate data using PySpark notebooks.
4. **Data Validation:** Apply validation logic to identify and handle data quality issues.
5. **Job Orchestration:** Execute Databricks notebooks through configured Databricks Jobs.
6. **Storage:** Organize processed data into appropriate data lake layers.

## Project Structure

```text
├── ADF_Pipeline
├── Databricks_Jobs
├── Databricks_Notebooks
├── Raw
└── README.md
```

## Azure Databricks Jobs

The project includes Databricks Jobs for coordinating notebook execution and data transformation workflows.

Screenshots of the configured jobs are included in the `Databricks_Jobs` folder.

## Learning Outcomes

* Working with Azure Data Factory pipelines
* Using Azure Data Lake Storage Gen2
* Implementing Auto Loader in Azure Databricks
* Performing data transformation using PySpark
* Understanding Bronze and Silver data layers
* Configuring and executing Databricks Jobs
* Managing project files using Git and GitHub

## Author

Abhishek Nandan

