# E-Commerce-Sales-Analysis-with-Power-BI

## Project Description
The Power BI report analyzes e-commerce sales data to provide insights into sales performance, product categories, and the impact of discounts on profitability. The report consists of four pages that allow stakeholders to explore sales trends and make data-driven decisions.

## Report Structure

### 1. Overview Page
**Purpose**: Provide a high-level summary of key sales metrics

**Visualizations**:
- Total Sales (KPI card)
- Total Profit (KPI card)
- Profit Margin (KPI card)
- Month-on-Month Sales (KPI card)
- Profit Margin, MoM and YoY Sales (matrix chart)  
- Monthly Sales Trend (line chart)

### 2. Store Performance Page
**Purpose**: Analyze sales performance by geographic location

**Visualizations**:
- Sales by State and Store Department (shape map)
- Top 10 Store Locations by Sales (matrix chart)

### 3. Product Performance Page
**Purpose**: Evaluate product category and subcategory performance

**Visualizations**:
- Sales and Product Margin by store department, category and sub-category (treemap with bookmarks)

### 4. Effect of Discount on Sales Page
**Purpose**: Examine how discounts impact sales volume and profitability

**Visualizations**:
- Discount vs. Profit Margin Correlation with sales bubble size (scatter plot)

## Data Preparation Steps
1. Import CSV file of fact table into Power BI
2. Using Power Query in Power BI, a calendar table is created from the fact table. 
3. Using Power Query in Power BI, create the following calculated columns (order processing time, discount, and sale price) from the other columns in the fact table
4. Using DAX in Power BI, create the following measures for KPIs and aggregations: (total sales, total profit, % sales, MoM sales change, and YoY sales change). 

