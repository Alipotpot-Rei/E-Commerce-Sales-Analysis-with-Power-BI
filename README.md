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
1. Import CSV file into Power BI
2. Create calculated columns:
   - Order Processing Time = DATEDIFF([Order Date], [Ship Date], DAY)
4. Establish relationships between tables (if additional tables are added later)
5. Create measures for KPIs and aggregations

## Technical Requirements
- Power BI Desktop (latest version)
- Basic understanding of DAX for calculated measures
- Power BI service for sharing (optional)

## Implementation Timeline
1. Data Preparation: 1 day
2. Dashboard Design: 2 days
3. Visualization Refinement: 1 day
4. Testing and Validation: 1 day
5. Deployment: 0.5 day

## Expected Outcomes
- Identification of top-performing products and regions
- Insights into optimal discount strategies
- Understanding of customer segment profitability
- Data-driven recommendations for inventory and marketing strategies

Would you like me to elaborate on any specific aspect of this Power BI project plan or provide sample DAX measures for any of the visualizations?
