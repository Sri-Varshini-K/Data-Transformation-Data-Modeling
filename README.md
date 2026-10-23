# E-Commerce Sales Analysis – Power BI

## Project Overview
This project focuses on data transformation and data modeling using Microsoft Power BI. The objective is to prepare e-commerce sales data, establish relationships between tables, and organize data for effective sales analysis.

## Tools Used
- Microsoft Power BI
- Power Query Editor

## Datasets
- **List of Orders.csv** – Order and customer information
- **Order Details.csv** – Sales, profit, category, and sub-category details
- **Sales Target.csv** – Monthly sales targets by category

## Key Activities

### 1. Data Transformation
- Restricted the List of Orders table to the first 500 rows.
- Corrected data types and formatted customer names using proper case.
- Created a Location column by combining City and State.
- Calculated Profit Margin and created a Profit Status column.

### 2. Data Merging
- Merged List of Orders and Order Details using Order ID.
- Created a consolidated table named **Orders Data**.

### 3. Data Cleaning
- Identified missing values and duplicate records.
- Applied appropriate data-cleaning techniques.
- Sorted orders by date and filtered data for regional analysis.

### 4. Grouping and Aggregation
- Calculated order counts, average profit by category, and total amount by sub-category.
- Aggregated sales targets by month.

### 5. Data Modeling
- Established relationships between List of Orders and Order Details using Order ID.
- Created a relationship between Order Details and Sales Target using Category.
- Verified that the relationships were active.

## Skills Demonstrated
Data Transformation, Data Cleaning, Power Query, Data Modeling, Table Merging, Data Aggregation, Custom Columns, and Relationship Management.

## Learning Outcomes
Gained practical experience in transforming raw e-commerce data, combining multiple tables, handling data quality issues, and building relationships to prepare data for business analysis.
