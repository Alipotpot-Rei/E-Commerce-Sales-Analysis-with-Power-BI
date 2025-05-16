# E-Commerce-Sales-Analysis-with-Power-BI

## Project Description
The Power BI report analyzes e-commerce sales data to provide insights into sales performance, product categories, and the impact of discounts on profitability. The report consists of four pages that allow stakeholders to explore sales trends and make data-driven decisions.

## Data Source

- The dataset is taken from a Youtube video which shows the creation of a single-page Power BI report. I decided to create a multi-page Power BI report which i think is best for complex datasets, like e-commerce sales, making it easy to focus on specific metrics.

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
- Tooltip (bar chart of sales by customer segment which appears when hovering over the line chart)

### 2. Store Performance Page
**Purpose**: Analyze sales performance by geographic location

**Visualizations**:
- Sales by State and Customer Segment (shape map)
- Top 10 Store Locations by Sales (matrix chart)

### 3. Product Performance Page
**Purpose**: Evaluate product category and subcategory performance

**Visualizations**:
- Sales and Product Margin by customer segment, category and sub-category (treemap with bookmarks)

### 4. Effect of Discount on Sales Page
**Purpose**: Examine how discounts impact sales volume and profitability.

**Visualizations**:
- Discount vs. Profit Margin Correlation with sales bubble size (scatter plot)

## Data Preparation Steps
1. Import CSV file of fact table into Power BI.
2. Using Power Query in Power BI, a calendar table is created from the fact table. 
3. Using Power Query in Power BI, create the following calculated columns (order processing time, discount, and sale price) from the other columns in the fact table.
4. Using DAX in Power BI, create the following measures for KPIs and aggregations: (total sales, total profit, % sales, MoM sales change, and YoY sales change).

## Tools and Technologies

- Power BI Desktop is the primary IDE for report development, data modeling, and visualization.	
- Power Query (M)	is used for cleaning the sales_overview.csv and creating a calendar table.
- DAX (Data Analysis Expressions)	is used for calculating measures (total revenue, total profit, profit margin, MoM %, YoY %). 
- DeepSeek chatbot is used for creating the insights and recommendations

## Insights and Recommendations to optimize sales strategy, profitability, and operations

### **1. Sales Performance Insights**
#### **A. Revenue & Profitability**
- **Highest-Sale Item**: Furniture drives revenue but has lower margins  
- **Lowest Profit**: Bookcases and tables   
- **Best Margin**: Copiers and envelopes  

**Recommendations**:  
 **Limit discounts on low-margin items** or bundle them with high-margin products.  
 **Promote high-margin categories** through targeted campaigns.  

#### **B. Discount Impact**
- **High Discounts (>50%)** often lead to **losses**  
- **No-Discount Items** are consistently profitable  

**Recommendations**:  
 **Cap discounts at 30%** for low-margin items.  
 **Test dynamic pricing** (e.g., offer discounts only on overstocked items).  

### **2. Customer Segment Analysis**
| Segment      | Avg. Order Value | Discount Sensitivity | Key Products          |  
|--------------|------------------|----------------------|-----------------------|  
| **Consumer** | Low     | High                 | Paper, Art Supplies  |  
| **Home Office** | High | Moderate             | Furniture, Binders   |  
| **Corporate** | Medium  | Low (negotiated)     | Bulk Supplies        |  

**Recommendations**:  
 **Home Office**: Offer ergonomic bundles (e.g., chair + desk) to increase the average order value.  
 **Corporate**: Focus on volume contracts with minimal discounts.  
 **Consumer**: Use limited-time discounts to drive impulse buys.  

### **3. Geographic Trends**
- **High-profit regions**: East and West  
- **Low-profit regions**: Central and South  

**Recommendations**:  
 **Expand marketing in the Central and South regions ** (e.g., targeted ads).  
 **Analyze shipping costs** for East and West regions to optimize delivery pricing.  

### **4. Product-Level Opportunities**
- **Underperforming**: Bookcases and tables  
- **Star Products**:  
  - **Office Supplies**: Envelopes  
  - **Technology**: Copiers  

**Recommendations**:  
 **Discontinue or reposition** underperforming products (e.g., sell as part of kits).  
 **Highlight high-margin products** on the homepage/featured section.  

### **5. Operational Improvements**
- **Shipping**: First Class (1-day) has no discounts but higher profitability.  
- **Inventory**: High-value furniture (e.g., tables) may need stock optimization.  

**Recommendations**:  
 **Upsell faster shipping** for high-margin orders.  
 **Monitor inventory turnover** for furniture to avoid overstocking.  

### **Summary of Actions**  
1. **Adjust Discount Strategy**: Limit deep discounts on low-margin items.  
2. **Segment-Specific Campaigns**: Target Home Office with bundles, Corporate with contracts.  
3. **Regional Expansion**: Boost marketing in the Central and South regions.  
4. **Product Optimization**: Promote high-margin items, phase out unprofitable ones.  
5. **Shipping Efficiency**: Use faster shipping as a premium upsell.  
