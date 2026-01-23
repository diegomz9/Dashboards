# Procurement Performance Dashboard Power BI

## Overview
This Power BI dashboard analyzes procurement data across five key suppliers from January 2022 to December 2023, covering total spend of $34.06M, savings achievement, supplier performance, quality & compliance, and monthly trends.

The dashboard provides an executive-level view of cost control, negotiation effectiveness, supplier reliability, defect patterns, and operational trends.

## Business Questions
- How effectively is procurement capturing savings, and where are the biggest opportunities by category and supplier?
- Which suppliers deliver the best combination of cost savings and quality (lowest defects)?
- Where are quality and compliance risks concentrated (by supplier, category, and specific POs)?
- How have spend, savings, order volume, and defect rates evolved over time, and what seasonal patterns exist?
- What is the impact of order status (Delivered vs Pending/Partial/Cancelled) on total spend and operations?

## Tools & Skills Used
- **Power BI**
  - DAX measures
  - Power Query (data cleaning and transformation)
  - Interactive slicers/drill-throughs/conditional formatting
- Data Analysis & Visualization
- Procurement Metrics
- Data Storytelling

## Dashboard Pages

### Page 1 — Procurement Executive Summary
Focus areas:
- High-level key metrics (total spend, savings, defect rate, delivery performance)
- Spend vs potential spend by item category
- Spend distribution by order status
- Top suppliers by spend

Key insight: Strong overall savings (7.87%) with balanced supplier concentration, but delivery performance (only 70.82% fully delivered) and quality (7.02% defect rate) present clear improvement opportunities.

<img width="1236" height="717" alt="image" src="https://github.com/user-attachments/assets/bedca3e2-2d6c-4f73-944e-cf932a1a28fc" />


### Page 2 — Supplier Performance Analysis
Focus areas:
- Spend breakdown and share by supplier
- Detailed supplier scorecard
- Good vs defective units per supplier
- Savings vs defect rate scatter plot for supplier segmentation

Key insight: Alpha_Inc and Epsilon_Group stand out as "star" suppliers (strong savings + low defects), while Delta_Logistics lags significantly on quality and requires immediate attention.

<img width="1219" height="698" alt="image" src="https://github.com/user-attachments/assets/c4cc69ea-34b1-4bcc-b518-f85e95707b6e" />


### Page 3 — Quality & Compliance
Focus areas:
- Quality metrics (total defective units, compliance rate)
- Defects by item category and supplier
- Top 10 high-risk purchase orders (highest defect rates)

Key insight: Delta_Logistics accounts for ~40% of all defective units despite only ~18% of spend. Office Supplies and Raw Materials categories contribute the most absolute defects.

<img width="1239" height="704" alt="image" src="https://github.com/user-attachments/assets/5c618da7-0f69-4caf-9cb6-81c04b0a28c4" />


### Page 4 — Trends Over Time
Focus areas:
- Monthly spend and savings evolution
- Defect rate trends
- Ordered quantity vs defective units over time

Key insight: Spend and savings were front-loaded (strong Q1 performance), followed by a mid-year slowdown. Quantity and defects remained relatively stable month-to-month, showing consistent operational volume and quality control despite seasonal spend fluctuations.

<img width="1238" height="686" alt="image" src="https://github.com/user-attachments/assets/c0fd3bb7-3c36-4a70-9f37-0b5448f04f5a" />


A full detailed written analysis with recommendations is available in [Insights.md](./Insights.md).

Done by Diego Martinez Zubillaga
