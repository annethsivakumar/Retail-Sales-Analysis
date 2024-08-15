# Retail-Sales-Analysis

This project is the culmination of the _Python for Data Engineering_ Linkedin course, focusing on implementing an end-to-end ETL (Extract, Transform, Load) pipeline for retail sales analysis. The objective is to create a Python script that processes and analyzes retail sales data stored in a CSV file with four columns: date, product, quantity, and sales.

The project follows these key data engineering steps:

1. **Data Extraction:** The CSV file is read into a pandas DataFrame, forming the basis for the ETL process.
2. **Data Transformation:** The data undergoes cleaning to remove rows with missing or incomplete values. Subsequently, the script performs data manipulation to calculate total sales per product, identify the bestselling product, and determine average daily sales.
3. **Data Loading and Visualization:** The transformed data is used to generate visualizations, including sales trends over time and a bar chart showing sales per product, facilitating clear insights into the data.

The analysis is structured within a Python class named RetailSalesAnalyzer, encapsulating methods for each stage of the ETL process. The final script creates an instance of this class, executing its methods to perform the complete data analysis and visualization, demonstrating practical data engineering skills.
