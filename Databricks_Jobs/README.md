# Azure Databricks Jobs

This folder contains screenshots and documentation of the Azure Databricks Jobs configured for the Netflix data engineering project.

## Jobs Included

### 1. JobsforAutoUploader

This job automates the execution of data processing notebooks.

**Workflow:**

* Lookup notebook
* Silver notebook
* ForEach activity for processing multiple files

**Screenshot:** `JobsforAutoUploader.png`

### 2. Data Validation and Transformation Job

This job executes notebook tasks based on the workflow and validation conditions.

**Workflow:**

* Weekday lookup notebook
* Conditional execution using If/Else
* Silver transformation notebook
* Data validation notebook

**Screenshot:** `Validation_Job.png`

## Technologies Used

* Azure Databricks
* PySpark
* Databricks Workflows
* Databricks Notebooks
* Apache Spark

## Purpose

The Databricks Jobs are used to orchestrate notebook execution, automate data processing, and support the Netflix data engineering pipeline.
