# E-commerce Data Project - 1
Objective : The objective of this project is to analyze e-commerce sales data to identify trends in sales performance, regional performance, product category profitability, and top-selling products. The analysis aims to generate insights that can support business decision-making and strategic planning.

## Source
https://www.kaggle.com/datasets/sidramazam/e-commerce-sales-performance-analysis/data

## Dataset Description
- This dataset was synthetically generated and may not reflect real-world data.
  
## Tools Used
- Pyhton
- Pandas
- Jupyter Notebook
- Github
  
## Project Date 
03-04-2026

## Dataset: E-Commerce Sales Data
The dataset contains historical e-commerce transaction records including:
- Order Date
- Product Name
- Category
- Region
- Quantity
- Sales
- Profit

## Data Cleaning
- No missing values were found in the dataset.
- Converted "Order Date" to datetime format for time-based analysis.
- Checked for negative profit values; none were found.

## Feature Engineering
- Extracted Year and Month from Order Date for yearly and monthly sales analysis.
  
## Assumptions & Limitations
- The dataset does not contain loss-making transactions.
- All recorded sales show positive profit.
- Product pricing and cost structure are not available, so deeper margin analysis cannot be performed.

## Exploratory Data Analysis
- Overall Profit Margin
- Sales and Profit by Region
- Sales and Profit by Year
- Sales and Profit by Category
- Top10 Best Selling Products

## KPI Summary
- The overall profit margin is 17.29% indicating a healthy profit.
- The West region generated the highest sales and profit making it the strongest performing region.
- 2023 recorded the highest total sales and profit suggesting high business performance during that year.
- Among product categories, Electronics generated highest revenue and profit followed by Accessories and Office product.
- The top performing products by quantity were Monitor, Smart watch and Camera, indicating strong demand for electronic related items.

