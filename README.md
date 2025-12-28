# Zepto E-commerce SQL Data Analysis Project

## Overview

This project demonstrates a real-world SQL data analysis workflow using an e-commerce inventory dataset inspired by India’s quick-commerce ecosystem.
The focus is on database design, data exploration, data cleaning, and business-driven analysis using SQL.

The project is built to reflect how a Data Analyst would work with raw inventory data in a retail or e-commerce environment.

## Objectives
- Design a structured relational table for product inventory data
- Perform exploratory data analysis (EDA) using SQL
- Clean and standardize raw pricing data
- Answer business-oriented questions related to pricing, discounts,stock,and   revenue
- Build a portfolio-ready SQL project suitable for interviews and GitHub

## Dataset Description
The dataset represents product listings commonly found in a grocery or quick-commerce platform.
Each row corresponds to a unique product SKU, where the same product name may appear multiple times due to variations in size, price, or packaging.

## Key Columns
- Sku_id – Auto-incremented primary key
- Category – Product category
- Name – Product name
- MRP – Maximum Retail Price
- DiscountPercent – Discount applied on MRP
- DiscountedSellingPrice – Final selling price
- AvailableQuantity – Units available in inventory
- WeightInGms – Product weight in grams
- OutOfStock – Stock availability indicator
- Quantity – Units per package

## Project Workflow
1. ## Database & Table Design

- Created a MySQL database and table with appropriate data types.
- Used an auto-increment primary key for SKU identification.

2. ## Data Import

- Imported CSV data into MySQL using MySQL Workbench.
- Ensured correct column mapping and UTF-8 encoding.
- Excluded auto-generated primary key during import.

3. ## Data Exploration

- Verified record counts
- Reviewed sample records
- Checked for null or missing values
- Analyzed category distribution
- Compared in-stock vs out-of-stock products
- Identified duplicate product names across SKUs

4. ## Data Cleaning

- Removed invalid pricing records
- Standardized pricing values
- Ensured consistency across numeric fields

5. ## Business Analysis

- Identified best-value products based on discount percentage
- Analyzed high-priced products that are out of stock
- Estimated category-wise revenue
- Evaluated products with high MRP and low discounts
- Ranked categories by average discount
- Calculated price per gram for value comparison
- Segmented products by weight
- Measured total inventory weight by category

## Tools & Technologies

- MySQL
- MySQL Workbench
- SQL
- CSV dataset
- GitHub

## Repository Structure
- ├── Zepto_SQL_data_analysis.sql
- ├── dataset/
- │   └── zepto.csv
- └── README.md

## How to Run

1. Clone the repository
2. Create a database in MySQL
3. Execute the SQL script to create tables
4. Import the CSV dataset into MySQL
5. Run the analysis queries sequentially

## Use Case

This project is suitable for:

- SQL beginners building a first portfolio project
- Data analyst aspirants preparing for interviews
- Practicing SQL with realistic e-commerce data


## Author
### Muhammed Swalih, 
Aspiring Data Analyst | SQL & Data Analytics Enthusiast
