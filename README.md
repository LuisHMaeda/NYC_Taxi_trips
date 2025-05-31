# 🗽 NYC Taxi Trips – Analytics Engineering Project

This project leverages **dbt (Data Build Tool)** and **Databricks** to model and document New York City taxi trip data made available by the [NYC Taxi and Limousine Commission (TLC)](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page).



## Tech Stack

- **dbt**: Data transformation, testing, and documentation
- **Databricks**: Cloud data platform for data storage and processing
- **Power BI**: Data visualization

## Project Objectives

In this project, I designed and implemented an end-to-end analytics pipeline using public data from the NYC Taxi & Limousine Commission (TLC). The pipeline consists of the following steps:

1. Extracted raw Parquet files from the NYC Trip Record Data website and loaded them into Databricks for further processing.
2. Transformed and modeled the data using dbt, applying tests and documentation through dbt’s built-in features.
3. Developed interactive dashboards in Power BI, visualizing key metrics such as average trip duration, tip amounts, payment types, and trip distribution by zone.

The sections below will explain details on the technologies and files utilized.

## Data set

[NYC Taxi website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) 

This official website maintained by the **New York City Taxi and Limousine Commission (TLC)** provides public access to trip-level taxi data.

It includes:

- Raw Parquet files for trip records, available monthly.
- Data dictionaries describing each field in detail.
- Taxi Zone Maps and lookup tables to relate pickup and dropoff location IDs to NYC neighborhoods and boroughs.

