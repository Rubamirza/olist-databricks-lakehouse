# olist-databricks-lakehouse

# Databricks Lakehouse – Brazilian E-Commerce (Olist)

## Overview
End-to-end Databricks lakehouse built using the medallion architecture
(Bronze → Silver → Gold) to support analytics for a marketplace business.

## Architecture
- Kaggle API → Databricks CLI → DBFS
- Delta Lake storage
- Spark-based transformations

## Data Ingestion
- Scripted download using Kaggle API
- CLI-based upload to Databricks
- Append-only Bronze Delta tables with metadata

## Data Modeling
- Silver layer enforces business rules and data quality
- Gold layer provides analytics-ready fact and dimension tables

## Tech Stack
- Databricks (Free Edition)
- Apache Spark
- Delta Lake
- Python
- SQL
