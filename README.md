# E-commerce Data Analysis

## Overview
This project focuses on analyzing Target's operations in Brazil using a dataset that includes 100,000 orders placed between 2016 and 2018. The analysis provides insights into order processing, pricing strategies, payment and shipping efficiency, customer demographics, product characteristics, and customer satisfaction.

## Dataset
The dataset consists of the following CSV files:
- `customers.csv`: Information about customers.
- `sellers.csv`: Details about sellers.
- `order_items.csv`: Specifics of items in each order.
- `geolocation.csv`: Customer location data.
- `payments.csv`: Payment methods and statuses.
- `orders.csv`: Overall order details.
- `products.csv`: Information about products.

  ## Folder and File Structure

### 1. `Queries.txt`
   - Contains a list of SQL queries used for analyzing the dataset. Queries range from basic to advanced, helping extract insights from the data.

### 2. `README.md`
   - The main documentation file that provides an overview of the project, usage instructions, and explanations for each folder/file in the repository.

### 3. `csv_to_sql_uploader.ipynb`
   - A Jupyter Notebook that contains Python code to convert the CSV dataset into a MySQL database for analysis.

### 4. `dataset_link.txt`
   - A file containing a link to the dataset used in this project. The dataset can be downloaded from the specified link due to its large size.

### 5. `ecommerce_data_analysis_with_pyton_sql.ipynb`
   - The main folder containing Python and SQL scripts that handle data processing, querying, and analysis. It includes all the scripts required to reproduce the analysis.

## Features
- **Basic Queries**: Insights on unique cities, order counts, total sales, payment methods, and customer demographics.
- **Intermediate Queries**: Analysis on monthly orders, product averages, revenue contributions, and seller performance.
- **Advanced Queries**: In-depth analysis including moving averages, cumulative sales, customer retention rates, and top customers by spending.
