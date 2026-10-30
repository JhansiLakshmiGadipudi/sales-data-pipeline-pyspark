# Sales Data Pipeline Using PySpark and Databricks

## Project Overview
This project demonstrates a simple sales data pipeline using PySpark and Databricks. It processes sales data through Bronze, Silver, and Gold layers.

## Technologies Used
- Python
- PySpark
- Databricks
- Delta Lake
- SQL

## Pipeline Layers
- **Bronze:** Stores raw sales data.
- **Silver:** Cleans the data and calculates total sales.
- **Gold:** Creates a product-wise sales summary.

## Data Quality Checks
- Checks for duplicate order IDs.
- Checks for null values.
- Checks for invalid quantities and prices.

## Final Output
The Gold layer summarizes total quantity, total revenue, and number of orders for each product.

## Learning Outcome
Learned the basics of building a data pipeline using PySpark and Databricks.
