# Data Warehouse & ETL Implementation

## Overview

This project implements a Data Warehouse using a dimensional star schema model and ETL processes developed with Pentaho Data Integration.

The objective is to transform raw CSV data into a structured analytical model optimized for querying and reporting.

This project demonstrates core Data Engineering concepts including data modeling, ETL pipeline design, and structured data storage.

---

## Architecture

**Source Layer**
- Raw CSV files

**ETL Layer**
- Pentaho Data Integration (.ktr transformations)
- Data cleaning and transformation
- Surrogate key generation
- Referential integrity management

**Storage Layer**
- MySQL database
- Star schema (Fact table + Dimension tables)

---

## Technologies Used

- Pentaho Data Integration
- MySQL
- SQL
- Dimensional modeling (Star Schema)
- ETL processes

---

## Data Model

The Data Warehouse follows a star schema design:

- Fact table containing measurable business metrics
- Dimension tables containing descriptive attributes
- Surrogate keys for dimensional consistency

---

## ETL Process

1. Extract data from source CSV files.
2. Transform and cleanse data.
3. Load dimension tables.
4. Load fact table.
5. Validate referential integrity.

---

## Key Concepts Demonstrated

- Dimensional data modeling
- ETL pipeline implementation
- Data cleansing and transformation
- Surrogate key handling
- Data warehouse design principles

---

## Repository Structure

