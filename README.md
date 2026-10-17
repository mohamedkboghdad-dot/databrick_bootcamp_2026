
# Databricks Data Engineering Project

## Overview

This project demonstrates a data engineering workflow using
Databricks, Apache Spark, PySpark, and Delta Lake.

The goal is to ingest raw data, clean and transform it,
and organize the data into layers following the Medallion Architecture.

## Architecture

The project follows the Medallion Architecture:

- **Bronze:** Ingest raw source data into Delta tables.
- **Silver:** Clean, standardize, and transform the data using PySpark.
- **Gold:** Prepare business-ready data for analytics, if implemented.

## Technologies Used

- Databricks
- Apache Spark
- PySpark
- Spark SQL
- Delta Lake
- Unity Catalog
- Python

## Project Workflow

1. Read source CSV files.
2. Load raw data into Bronze tables.
3. Clean and standardize data in the Silver layer.
4. Validate transformations and review the results.
5. Prepare analytical tables in the Gold layer, if implemented.

## Repository Structure

```text
databrick_bootcamp_2026/
├── README.md
├── LICENSE
├── .gitignore
└── notebooks/
    ├── bronze_layer(basic).ipynb
    ├── bronze_layer_(improved).ipynb
    └── silver_layer.ipynb
```

Update the folder and notebook names to match the actual
structure of this repository.

## Key Learnings

- Working with PySpark DataFrames.
- Reading and processing CSV files.
- Cleaning string columns and standardizing values.
- Writing data to Delta tables.
- Organizing data using the Medallion Architecture.
- Working with Databricks and Unity Catalog.

## Acknowledgments

This project was inspired by educational materials
and hands-on exercises from Data With Baraa's Databricks bootcamp.

## Author

Mohamed Boghdad

