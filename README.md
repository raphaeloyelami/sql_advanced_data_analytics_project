# SQL Advanced Data Analytics Project
A comprehensive collection of SQL scripts for data exploration, analytics, and reporting. These scripts cover various analyses such as database exploration, measures and metrics, time-based trends, cumulative analytics, segmentation, and more.

## Project Overview
This repository contains an advanced SQL data analytics project that involves the exploration, analysis, and reporting of a sales database. The project utilizes multiple SQL techniques to analyze and derive insights from a retail sales dataset, consisting of customer, product, and sales data across various tables. The objective is to leverage SQL queries to generate meaningful business insights, customer behavior analysis, product performance, and sales metrics.

### Objective
The goal of this project is to explore a real-world sales database to answer key business questions through advanced SQL queries. The analysis includes customer segmentation, product performance reports, sales trend analysis, and more. By applying various SQL techniques such as aggregation, joins, ranking, and time-series analysis, the project demonstrates the power of SQL in deriving actionable insights.

## 📂 Repository Structure
```
sql_data_analytics/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # ERD
│
├── scripts/                            # SQL scripts for analysis
│
└── README.md                           # Project overview and instructions
```


## Tables Involved
1. **`dim_customers`** - Contains customer information.
    - Key attributes: `customer_key`, `customer_id`, `customer_number`, `first_name`, `last_name`, `country`, `marital_status`, `gender`, `birthdate`.

2. **`fact_sales`** - Contains sales transactions data.
    - Key attributes: `order_number`, `product_key`, `customer_key`, `order_date`, `shipping_date`, `due_date`, `sales_amount`, `quantity`, `price`.

3. **`dim_products`** - Contains product information.
    - Key attributes: `product_key`, `product_id`, `product_number`, `product_name`, `category_id`, `category`, `subcategory`, `maintenance`, `cost`, `product_line`, `start_date`.

## Key Insights and Analyses
- **Customer Segmentation**: Identify customer groups based on various attributes such as demographics, sales activity, etc.
- **Part-to-Whole Analysis**: Perform a breakdown of key metrics, e.g., sales per product category or region.
- **Customer & Product Reports**: Generate detailed reports on customer behavior and product performance.
- **Magnitude and Ranking Analysis**: Identify top-selling products, highest-spending customers, etc.
- **Time-based Analysis**: Analyze trends, sales performance over time, and seasonal changes.
- **Change Over Time Analysis**: Examine how certain metrics change over specific periods (e.g., monthly or quarterly).
- **Cumulative Analysis**: Calculate cumulative sales, customer growth, etc.
- **Performance Analysis**: Evaluate overall sales performance and individual product performance.

## SQL Queries & Scripts
The SQL scripts provided are organized into the following categories:

1. **Database Creation**: Scripts to create the database structure and necessary tables.
2. **Exploratory Data Analysis**: Initial queries to explore the data and gain an understanding of the dataset.
3. **Segmentation & Report Generation**: Queries to generate customer segmentation, reports, and product performance.
4. **Advanced Analytics**: Queries that perform in-depth analytics like ranking, cumulative metrics, and time-based analyses.

## ERD (Entity-Relationship Diagram)
An Entity-Relationship Diagram (ERD) of the database schema is available in the `docs/` folder. The diagram visualizes the relationships between the tables in the database and provides insights into how the data is structured.

![ERD](https://github.com/raphaeloyelami/sql_advanced_data_analytics_project/blob/3d06c805132f99d9ff5017ca036c1ea0f31b2e45/docs/data_model.png)

## Prerequisites
Before running the SQL scripts, ensure you have:
- **[Datasets](datasets/):** Access to the project dataset (csv files).
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads):** Lightweight server for hosting your SQL database.
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16):** GUI for managing and interacting with databases.

## Acknowledgments
- This project was developed as part of an advanced SQL data analytics course.
- Thanks to the [creator](https://www.youtube.com/@DataWithBaraa) of the dataset used in this project.

## Contact
For any questions or suggestions, feel free to open an issue or contact me [here](raphaeloyelami1@gmail.com).
