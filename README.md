
# Decathlon Retail Performance Dashboard

## Project Overview

This project focuses on analyzing Decathlon's retail sales and profitability performance using Power BI. The dashboard provides an interactive view of sales trends, gross profit, product performance, regional contribution, and brand performance.

The objective is to help retail management monitor business performance, compare Year-to-Date (YTD) results with the Previous Year-to-Date (PYTD) period, identify growth opportunities, and make data-driven business decisions.

## Business Problem

Retail management needs a consolidated view of sales and profitability to understand how the business is performing across different products, sports, brands, and regions.

The key business challenges addressed in this project are:

- Monitoring sales and gross profit growth compared with the previous year.
- Identifying changes in gross profit margins.
- Understanding monthly sales trends and seasonal patterns.
- Identifying top-performing and underperforming sports and brands.
- Evaluating product types based on sales and profitability.
- Understanding regional sales contribution.
- Analyzing sales performance across payment methods and promotion segments.

## Tech Stack

- **Power BI:** Dashboard development and data visualization.
- **Power Query:** Data cleaning, transformation, and preparation.
- **DAX:** Calculated measures, KPIs, and Year-over-Year comparisons.
- **Data Modeling:** Relationships between sales, product, store, and date tables.
- **Microsoft Excel:** Data inspection and preliminary analysis.

## Data Source

- **Platform:** Kaggle
- **Dataset:** Decathlon Retail Sales Dataset
- **Format:** Structured retail sales data.

The dataset contains sales transactions and related product and store information.

### Data Tables Used

| Table | Description |
|---|---|
| Sales | Transaction-level sales, revenue, cost, profit, quantity, payment method, and promotion |
| Products | Product type, sport, brand, and colour |
| Store | State and regional information |
| Date | Calendar information for time-based analysis |

*Dataset Source: Kaggle. Add the original Kaggle dataset URL here.*

## Dashboard Features

### 1. Key Performance Indicators (KPIs)

The dashboard tracks six major performance indicators:

- Net Sales YTD
- Gross Profit YTD
- Gross Margin YTD %
- Net Units Sold YTD
- Net Orders YTD
- Average Order Value (AOV)

Each KPI includes a comparison with the corresponding previous-year period and its Year-over-Year (YoY) change.

### 2. Sales Trend Analysis

- Monthly comparison of current-year and previous-year sales.
- Identification of high-performing and low-performing months.
- Year-over-year sales movement.
- Comparison of equivalent reporting periods.

### 3. Product and Sport Analysis

- Net Sales YTD by Sport.
- Product Type Performance based on sales and gross margin.
- Comparison of product types using order volume.
- Identification of high-sales and high-margin product types.

### 4. Regional Performance Analysis

- Net Sales YTD by Region.
- Regional contribution to total sales.
- Comparison of sales performance across geographical regions.

### 5. Brand Performance Analysis

- Sales comparison across different brands.
- Identification of leading brands.
- Year-over-Year brand sales growth.
- Comparison against the internal average growth benchmark.

### 6. Interactive Filters

The dashboard includes interactive slicers for:

- State
- Sport
- Colour
- Promotion
- Payment Method

A reset filters button allows users to restore the default dashboard view.

## Key Business Insights

Based on the dashboard results (YTD through 15 September 2026):

### 1. Overall Sales Performance

- Net sales reached ₹55.26M compared with ₹44.4M in the previous year.
- Sales increased by 24.3% YoY.
- Gross profit increased by 25.3%, reaching ₹21.72M.

### 2. Profitability Analysis

- Gross margin improved from 39.0% to 39.3%.
- The improvement represents an increase of 0.3 percentage points.
- Gross profit growth slightly exceeded revenue growth.

### 3. Sport Performance

- Hiking emerged as the highest revenue-generating sport, with approximately ₹12.1M in sales.
- Badminton followed with approximately ₹6.2M.
- Fitness and Cricket generated approximately ₹6.0M each.

### 4. Brand Performance

- Quechua recorded the highest displayed brand sales at approximately ₹12.1M.
- Perfly followed with approximately ₹6.2M.
- The leading brands represent significant contributors to the displayed sales mix.

### 5. Regional Performance

- South contributed approximately 31.69% of total sales.
- West contributed approximately 27.03%.
- Together, these two regions accounted for approximately 58.7% of total sales.

### 6. Order and Customer Spending Trends

- Net orders increased by 23.0% YoY.
- Net units sold increased by 23.1%.
- Average Order Value increased by 24.3%, reaching ₹2.82K.

These results indicate growth in both order volume and average spending per order.

### 7. Monthly Sales Trends

- August recorded the highest monthly sales in the displayed current-year trend.
- Current-year sales remained above the corresponding previous-year monthly sales through August.
- September represents a partial-month comparison covering only the first 15 days.

## Business Recommendations

Based on the analysis, the following actions could support better business performance:

1. **Improve Product Profitability:** Review high-sales, low-margin product types to identify opportunities for better pricing and cost management.

2. **Focus on High-Performing Sports:** Analyze the products driving Hiking sales and explore opportunities to strengthen other sports categories.

3. **Strengthen Regional Performance:** Study the sales patterns of South and West and identify opportunities to improve performance in other regions.

4. **Increase Average Order Value:** Explore product bundling, cross-selling, and complementary product recommendations.

5. **Optimize Brand Portfolio:** Evaluate brand-level sales growth and profitability to support merchandising decisions.

6. **Improve Sales Planning:** Use monthly sales trends to identify seasonal patterns and plan future sales activities.

## Business Impact

The dashboard provides a consolidated view of retail performance and supports management in:

- **Performance Monitoring:** Track sales, profitability, and order growth through key business indicators.
- **Better Decision-Making:** Identify products, sports, brands, and regions contributing to business performance.
- **Profitability Management:** Highlight product types that may require margin improvement.
- **Regional Planning:** Understand geographical sales contribution and identify potential growth opportunities.
- **Business Strategy:** Support data-driven merchandising, sales planning, and commercial decisions.

## Skills Demonstrated

- Data Cleaning and Transformation
- Data Modeling
- DAX Measures and Calculations
- KPI Development
- Time Intelligence and YoY Analysis
- Business Intelligence
- Data Visualization
- Retail Sales Analysis
- Financial and Profitability Analysis
- Business Insights and Recommendations

## Dashboard Preview

