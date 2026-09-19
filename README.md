# NYC Taxi Analytics & Spark Performance Optimization

An end-to-end **Apache Spark analytics project built on Databricks** using the NYC Yellow Taxi Trip dataset.

The project focuses on practical Spark DataFrame operations, data quality and cleaning, data enrichment through joins, business-oriented analytics, and Spark performance optimization.

The objective was not only to analyze the taxi data, but also to understand how Spark executes analytical workloads and evaluate whether manual optimization techniques actually improve performance.

---

## Project Overview

This project analyzes **NYC Yellow Taxi trip data for January 2024** using **PySpark on Databricks**.

The workflow covers:

- Data loading and schema inspection
- Exploratory data analysis
- Data quality validation and cleaning
- Handling NULL and anomalous values
- Data enrichment using dimension joins
- Business-oriented analytical questions
- Spark SQL and DataFrame aggregations
- Spark performance optimization experiments
- Physical plan analysis using `explain()`
- Evaluation of Broadcast Join, Shuffle/Repartition, Caching, AQE and Photon

The project demonstrates how Apache Spark can be used for both **large-scale data analysis and performance-aware data processing**.

---

## Tech Stack

### Data Processing & Analytics

- **Apache Spark**
- **PySpark**
- **Spark DataFrames**
- **Spark SQL**
- **Databricks**

### Databricks & Spark Optimization

- **Databricks Serverless Compute**
- **Photon Engine**
- **Adaptive Query Execution (AQE)**
- Broadcast Join
- Shuffle Analysis
- Repartitioning
- Physical Plan Analysis using `explain("formatted")`

### Programming & Data

- **Python**
- **SQL**
- **Parquet**
- **CSV**

### Version Control

- **Git**
- **GitHub**

---

## Project Workflow

```text
Raw Data
   │
   ▼
Data Loading
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Data Quality Validation & Cleaning
   │
   ▼
Data Enrichment
   │
   ▼
Business Analysis
   │
   ▼
Spark Performance Optimization
   │
   ▼
Final Insights
