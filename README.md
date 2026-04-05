# SQL Sales Analytics & Reporting System

## Overview
I built this project to demonstrate how raw transactional data can be transformed into analytics-ready reporting tables using SQL. The workflow covers schema design, sample data loading, data cleaning, validation checks, and KPI reporting.

The objective is to simulate a practical reporting environment where business users need trusted monthly revenue, customer, product, and growth insights from operational data.

## Business Use Case
Business teams often need clean reporting tables instead of querying raw transaction data directly. This project shows how SQL can be used to prepare structured, reliable datasets for dashboards, business reviews, and recurring performance analysis.

## Project Objectives
- Design raw and reporting tables
- Load sample transactional data
- Clean and standardize source records
- Build reporting-ready dimension and fact tables
- Perform data quality checks
- Generate KPI and business reporting queries

## Tech Stack
- PostgreSQL
- SQL

## Project Files
- `schema.sql` → creates raw, dimension, and fact tables
- `insert_sample_data.sql` → loads sample transactional data
- `data_cleaning.sql` → transforms and loads clean reporting tables
- `data_quality_checks.sql` → checks duplicates, missing values, and data integrity
- `reporting_queries.sql` → KPI queries for business reporting

## Data Model
Raw source tables:
- `raw_customers`
- `raw_products`
- `raw_orders`

Reporting tables:
- `dim_customers`
- `dim_products`
- `fact_orders`

## Key Business Questions Answered
- What is the total revenue?
- How does revenue change month by month?
- Which categories generate the highest revenue?
- Who are the top customers?
- Which products perform best?
- What is the average order value?
- What is the month-over-month growth rate?
- Which cities contribute the most revenue?

## Skills Demonstrated
- Advanced SQL
- Data cleaning and transformation
- Data validation
- Data modeling
- KPI reporting
- Window functions
- Aggregations and joins

## How to Run
1. Run `schema.sql`
2. Run `insert_sample_data.sql`
3. Run `data_cleaning.sql`
4. Run `data_quality_checks.sql`
5. Run `reporting_queries.sql`

## Author
Md. Mizanur Rahman
