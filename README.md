# Sales Dashboard Project (Superstore Dataset)

## Project Overview

This project focuses on analyzing retail sales performance using the Superstore dataset. The goal was to build an interactive Excel dashboard that provides insights into business performance, customer behavior, and regional sales trends.
The dashboard highlights key performance indicators (KPIs) such as total sales, total profit, profit margin, and number of customers, enabling quick and data-driven decision-making.

### Data Source

The dataset used is the Superstore dataset, a popular retail dataset containing transactional data.

It includes:

- Order details (Order Date, Customer Name)
- Product categories (Furniture, Office Supplies, Technology)
- Sales and profit information
- Regional data (Central, East, South, West)

### Tools Used
- Microsoft Excel
  - Pivot Tables
  - Pivot Charts
  - Slicers (for interactivity)
    
### Data Cleaning and Preparation

To ensure data accuracy and consistency, the following steps were performed:

- Converted the Order Date using Text-to-Columns for proper date formatting
- Created new columns for Month and Year to enable time-based analysis
- Checked for inconsistencies and ensured data integrity
- Standardized data types (numbers, text, dates)
- Estimated Profit using an assumed average margin of 19%
- Calculated Profit Margin using:
- Profit ÷ Sales
- Created a Business Status column using an IF function to classify performance

### Exploratory Data Analysis (EDA)

Initial exploration was carried out to understand patterns and trends:

- Identified top-performing regions and categories
- Analyzed customer distribution and contribution to sales
- Examined monthly sales trends to detect seasonality
- Compared sales across different product categories

This step helped guide the dashboard design and key metrics selection.

### Data Analysis & Visualizations
#### Key KPIs
- Total Sales: $2,261,403.38
- Total Profit: $429,666.64
- Profit Margin: 19%
- Number of Customers: 793

### Charts & Why They Were Used

1. Sales by Region (Bar Chart)

- Used to compare sales performance across regions
- Easy to identify the highest and lowest performing regions
- Insight: The West region generates the highest sales

2. Top 10 Customers (Horizontal Bar Chart)

- Highlights key customers contributing most to revenue
- Helps in identifying high-value customers
- Insight: A small group of customers contributes a large portion of sales
  
3. Monthly Sales Trend (Line Chart) (if included)

- Shows how sales change over time
- Helps detect trends, seasonality, or growth patterns
- Insight: Useful for forecasting and planning

4. Profit by Category (if included)

- Compares profitability across product categories
- Helps identify which category drives profit

### Findings
- The West region is the top-performing region in terms of sales
- A few top customers contribute significantly to overall revenue
- The business maintains a healthy profit margin of 19%
- Sales vary across regions, indicating uneven performance
- Technology category perform better than others in profitability

### Recommendations
- Focus marketing and expansion strategies on high-performing regions (West & East)
- Develop loyalty programs for top customers to retain them
- Investigate underperforming regions (e.g., South) for improvement opportunities
- Optimize product offerings by focusing on high-profit categories
- Use monthly trends to plan promotions during peak periods

### Limitations
- Profit was estimated using a fixed 19% margin, which may not reflect actual profitability
- Dataset may not include all real-world factors (e.g., discounts, returns, operational costs)


