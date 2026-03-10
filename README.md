# E-commerce Data Project - 1
## Objective
The objective of this project is to analyze e-commerce sales data to identify trends in sales performance, regional performance, product category profitability, and top-selling products. The analysis aims to generate insights that can support business decision-making and strategic planning.

## Final Summary 
The analysis shows that the dataset maintains a consistent profit margin (~17.5%) across all product categories, indicating balanced pricing and cost structures. A strong positive correlation between sales and profit (0.83) suggests that increasing sales directly improves profitability. Moderate correlations between sales, profit, and quantity indicate that larger order sizes contribute to higher revenue and profit. Most transactions are small to moderate in value, while a few high-value transactions generate significantly higher profits. Overall, the results suggest that business performance is primarily driven by higher sales volume and larger transactions while maintaining stable profit margins. Below are the detailed proceedings of the project.

## Source
https://www.kaggle.com/datasets/sidramazam/e-commerce-sales-performance-analysis/data

## Dataset Description
- This dataset was synthetically generated and may not reflect real-world data.
  
## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
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

## Data Visualizations
- Sales by Region(Bar chart) : The West region shows the strongest market demand compared to other regions.
- Sales by Category(Bar Chart) : Electronics generated highest sales reaching upto $5.5M while Office supplies generated the lowest salesa at approximately million.
- Sales by Month (Line chart with marker) : Overall, May was the best performing month and february being the worst performing month. 
- Top 10 products by sales (Bar Chart) : Camera peaked with 1.2 M aales followed by Monitors at 1.1 M sale. The least was headphones with less than a million.
- Sales Heatmap (Month vs Year) : The Heat map reveals seasonal fluctuations in sales acroos three years. May consistently shows strong sales performance. August 2023 recorded highest sales whiile February appears to be the weakest month.

## Adv EDA Data Vizualizations
- Profit Margin by category(Bar chart) : The Overall Profit margin(17.5%) and the category-wise Profit margin values range between 17.1% to 17.8%. This indicates that profitability is fairly consistent across all product categories, suggesting a balanced pricing and cost structure for the items sold.
- Correlation Matrix(heatmap) : Sales and Profit showed strong positive correlation with 0.83. This indiactes, higher sales lead to higher profits. Moderate correlation of 0.66 was identified between Sales and Quantity and a 0.56 correlation between profit and quantity.
- Scatter Plot Analysis : 
    1. There are almost no points where high sales have very low profit compared to the rest of the dataset.Hence is called a positive correlation.
    2. All points appear above the horizontal axis where Profit = 0. Hence, There are no loss-making transactions in this dataset.
    3. The vertical spread of points(**Heteroscedasticity**__) shows the range of profit for the same sales value.Higher value transactions show greater profit variability.
    4. Since many points cluster in one region of the chart, it indicates:The majority of transactions fall within a moderate sales range.
- Regression Line:
    1. The straight line suggests the relationship between sales and profit is approximately proportional.
- Distirbution analysis of Sales(Histogran) : Most transactions are small or moderate in value.
- Outlier Detection (Box Plot): The profit distribution showed a strong right skew, with the majority of transactions generating moderate profit between approximately $200 and $700. The median profit is around $400, indicating a typical profit level for most transactions. However, several high-profit outliers exist, reaching up to nearly $3000, suggesting that certain transactions generate significantly higher profits than the majority.
- Pairplot: The pairplot revealed important relationships between sales, profit, and quantity. Both sales and profit distributions are right-skewed, indicating that most transactions involve lower values while a few large transactions contribute significantly to total revenue. The scatter plots show a strong positive relationship between sales and profit, suggesting that higher revenue transactions tend to generate higher profits. Additionally, quantity demonstrates a positive relationship with both sales and profit, indicating that larger order sizes lead to higher transaction values and profitability.


