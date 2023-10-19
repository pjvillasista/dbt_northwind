# Analytics Engineering Bootcamp - dbt Project

This repository contains the dbt models for the Analytics Engineering Bootcamp.

## Project Overview

This project is structured to transform and model the Northwind dataset in BigQuery. The primary goal is to create a dimensional data warehouse that can be used for analytical reporting and business intelligence.

### Directory Structure

- `models/`: Contains all the dbt models.
  - `staging/`: Contains the staging layer models which are the first transformation of the source data.
  - `warehouse/`: Contains the dimensional and fact tables for the data warehouse layer.

- `tests/`: Contains custom data tests.

- `macros/`: Contains custom macros used across the project.

## Data Sources

- **Northwind**: A sample database representing a company's sales operations.

## Setup & Running

1. Ensure you have dbt installed.
2. Clone this repository.
3. Navigate to the project directory.
4. Run `dbt debug` to ensure your connection is set up correctly.
5. Run `dbt run` to execute the models.

## Models

### Staging Layer

- `stg_customer`: Staging table for customer data.
- `stg_employees`: Staging table for employee data.
- ... 

### Data Warehouse Layer (Dimensional Modeling Layer)

- `dim_customer`: Dimension table for customer data.
- `dim_employee`: Dimension table for employee data.
- ... 

