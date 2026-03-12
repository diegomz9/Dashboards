# Sales Performance Dashboard Power BI

## Overview

This Power BI dashboard analyzes superstore sales data from January 2015 to December 2018, covering **$2.26 million** in total sales across 4,922 orders, 9,800 units sold, and 1,849 unique products.

The dashboard delivers an executive-level view of:

- Overall sales performance and regional distribution
- Delivery efficiency (avg. 3.96 days)
- Customer segment contributions and top spenders
- Product/category/subcategory performance and yearly trends
- Seasonal patterns and concentration risks

It helps answer core business questions around revenue drivers, geographic & customer concentration, product portfolio, and growth opportunities.

## Business Questions

- Which regions, categories, and products drive the majority of revenue and where is growth potential highest?
- How do customer segments (Consumer, Corporate, Home Office) contribute to sales, and who are our highest-value customers?
- What seasonal patterns exist in monthly sales, and how can we smooth demand fluctuations?
- Which subcategories and individual products have the strongest market share?
- Is there unhealthy concentration risk in regions, customers, or products?

## Tools & Skills Used

- **Power BI**
  - DAX measures & calculated columns
  - Power Query (data cleaning, date formatting, relationships)
  - Interactive slicers (date, region, category, city), bookmarks, conditional formatting
  - Donut charts, bar charts, line trends, tables, KPI cards
- Data Analysis & Visualization
- Sales & Customer Metrics
- Business Storytelling & Insights

## Dashboard Pages

### Page 1 — Sales Performance Overview

**Focus areas:**

- High-level KPIs: Total Sales, Units Sold, Number of Receipts, Avg. Sales per Receipt, Avg. Delivery Time, Total Products
- Sales trend by month (clear Q4 peaks, February lows)
- Regional sales breakdown (West 31.4%, East 29.6%, Central 21.8%, South 17.2%)
- Interactive filters: Category, Region, City, Date range

**Key insight:** Strong overall performance with fast delivery (~4 days) and healthy AOV ($459), but heavy reliance on West + East (61% combined) and pronounced seasonality (Q4 spikes).

### Page 2 — Customer Insights

**Focus areas:**

- Sales contribution by segment (Consumer ~51%, Corporate ~30%, Home Office ~19%)
- Monthly sales evolution by segment (Consumer drives peak volatility)
- Top spenders table (ranked by total sales, with segment & name)
- Interactive filters

**Key insight:** Consumer segment dominates volume and seasonal peaks. High-value customers are concentrated — top 20 represent a meaningful share of total revenue → retention & upselling programs recommended.

### Page 3 — Product Analysis

**Focus areas:**

- Sales share by sub-category
- Top 10 best-selling products by market share (Canon imageCLASS copier leads at 2.72%)
- Yearly sales by category (2015–2018) showing consistent growth, especially in Technology
- Interactive filters

**Key insight:** Technology is the fastest-growing and highest-revenue category. Product concentration (top 1 item drive outsized share) and explore bundling opportunities.

A full detailed written analysis with metrics, insights, and actionable recommendations is available in **[[insights.md](./Insights.md)](https://github.com/diegomz9/Dashboards/blob/main/SuperStoreSales/Insights.md)**.

Done by Diego Martinez Zubillaga
