#DATA PIPELINE ARCHITECTURE

This project implements an end-to-end data pipeline on Google Cloud.


## Pipeline Flow

Data Source  > Ingestion > Processing > Data Lake > BigQuery > Analytics

## Components

### DATA SOURCE
External data such as CSV files or APIs

### INGESTION
Python scripts that extract data from the source

### PROCESSING
Data Cleaning and transformation logic

### DATA LAKE
Cloud Storage bucket with three layers :
 - RAW
 - PROCESSED
 - CURATED

### Data Warehouse
BigQuery stores structured data for analytics

### ORCHESTRATION
Airflow manages pipeline scheduling

### INFRASTRUCTURE
Terraform provisions cloud resources
