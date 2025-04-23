# 📊 Retail Orders Data Analysis Project
This project focuses on end-to-end data processing and analysis of a retail orders dataset to extract meaningful business insights. The dataset was sourced from Kaggle and includes detailed information about products, pricing, discounts, regions, shipping modes, and order timelines.

# 🔧 Key Steps & Workflow:
## Data Acquisition
  - Fetched dataset using the Kaggle API (ankitbansal06/retail-orders).
  - Downloaded and loaded the data into a pandas DataFrame.
  - Data Cleaning & Preprocessing
  - Handled null and inconsistent values ('unknown', 'Not Available').
  - Renamed and standardized column names.
  - Converted date fields to proper datetime format.
  - Engineered new features: discount, sale_price, and profit.
  - Dropped irrelevant columns to simplify the dataset.
  - Data Storage
  - Saved the cleaned dataset to a CSV file.
  - Loaded the final DataFrame into a MySQL database table using SQLAlchemy.

## SQL-Based Data Analysis

  - Identified top 10 revenue-generating products.
  - Analyzed top 5 best-selling products by region.
  - Compared monthly sales growth between 2022 and 2023.
  - Found the highest sales month for each product category.
  - Determined the sub-category with the highest YoY growth in profit.

## 📈 Data Visualization (Matplotlib)

  - Visualized the Top 10 Sub-Categories by Profit Growth comparing 2023 vs 2022.
  - The bar chart highlights the top-performing sub-categories in terms of profit expansion.

# 🚀 Tools & Technologies Used
  - Python (Pandas, Matplotlib)
  - MySQL (via mysql-connector-python and SQLAlchemy)
  - Kaggle API for dataset access
  - SQL for in-depth business query analysis

# 📌 Outcome
 - This project demonstrates the ability to work across the entire data pipeline — from ingestion and transformation to storage and insight generation — and builds a strong foundation for a Database Analyst or Data Engineer role.
