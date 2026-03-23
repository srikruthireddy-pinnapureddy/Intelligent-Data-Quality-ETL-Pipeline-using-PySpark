# Intelligent Data Quality & ETL Pipeline using PySpark

## Overview
This project implements an end-to-end PySpark ETL pipeline for transactional sales data. It performs data ingestion, cleaning, validation, anomaly detection, and aggregation, then stores processed outputs in Parquet format.

## Tech Stack
Python, PySpark, Apache Spark, SQL, Parquet

## Features
- Data ingestion from CSV
- Column standardization
- Data cleaning and normalization
- Rule-based validation
- Duplicate removal
- Anomaly detection for high-value transactions
- Daily and product-level aggregations
- Output in Parquet format

## Project Structure
```text
intelligent-data-quality-etl-pyspark/
├── data/
│   └── raw/
│       └── sales_data.csv
├── output/
├── src/
│   └── main.py
├── requirements.txt
└── README.md
