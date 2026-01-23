# Procurement Dashboard Insights

**Dataset Overview**  
- Time Period: January 1, 2022 – December 16, 2023 (full 2022–2023 data)  
- Filters Applied: None (all categories, suppliers, order statuses, and compliance levels included)  
- Suppliers: 5 total  
- Total Spend: $34.06M  
- Total Quantity Ordered: ~626K units  

---

## Page 1: Procurement Executive Summary

<img width="1116" height="628" alt="image" src="https://github.com/user-attachments/assets/29b20a3f-ec8a-4b4e-ae98-79ae2b6d24bb" />

### Key Metrics
| Metric                  | Value          |
|-------------------------|----------------|
| Total Spend             | $34.06M       |
| Total Savings           | $2.91M        |
| Overall Savings %       | 7.87%         |
| Average Defect Rate     | 7.02%         |
| % Orders Delivered      | 70.82%        |
| Total Quantity Ordered  | 626K units    |
| Purchase Orders         | 562           |

### Key Insights
- Strong cost control with $2.91M in negotiated savings (7.87% overall savings rate).
- Quality is acceptable but improvable (7.02% defect rate ≈ 1 in 14 units defective).
- Delivery performance offers opportunity: only 70.82% of orders fully delivered (~29% partial, pending, or cancelled).
- Moderate PO volume (562 POs over ~2 years ≈ 23 POs/month) with average PO value ≈ $60K, indicating large-order procurement.

### Negotiated vs Potential Spend by Category
- Categories ranked by spend: MRO > Office Supplies > Electronics > Packaging > Raw Materials.
- Potential Spend exceeds Actual Spend in every category, highlighting captured savings.
- Savings % by category: Packaging (8.40%) > Electronics (8.07%) > MRO (7.76%) > Raw Materials (7.75%) > Office Supplies (7.45%).
- Opportunity exists for category-specific strategies to push overall savings above 10%.

### Spend Distribution by Order Status
- Delivered: ~70%  
- Pending: ~13%  
- Partially Delivered: ~9%  
- Cancelled: ~7%

### Top Suppliers by Spend
| Supplier        | Spend    | Share |
|-----------------|----------|-------|
| Epsilon_Group   | $7.84M  | ~23% |
| Beta_Supplies   | $7.64M  | ~22% |
| Gamma_Co        | $7.23M  | ~21% |
| Delta_Logistics | $6.28M  | ~18% |
| Alpha_Inc       | $5.07M  | ~14% |

- Balanced distribution provides leverage while reducing single-supplier risk.  
- Recommendation: Maintain strategic relationships and explore qualified alternatives over time.

---

## Page 2: Supplier Performance Analysis

<img width="1116" height="618" alt="image" src="https://github.com/user-attachments/assets/31c8350a-8f1c-44d4-951f-6645c3ece9ad" />


### Total Spend by Supplier
| Supplier        | Spend    | Share |
|-----------------|----------|-------|
| Epsilon_Group   | $7.84M  | ~23% |
| Beta_Supplies   | $7.64M  | ~22% |
| Gamma_Co        | $7.23M  | ~21% |
| Delta_Logistics | $6.28M  | ~18% |
| Alpha_Inc       | $5.07M  | ~14% |

- Even distribution (14–23% range); top three suppliers represent ~66.5% of spend.

### Supplier Key Metrics
| Supplier        | Total Spend   | Total Savings | Savings % | Defect Rate % | Delivery Days |
|-----------------|---------------|---------------|-----------|---------------|---------------|
| Beta_Supplies   | $7,640,191   | $712,175     | 8.53%    | 9.80%        | 11.19        |
| Alpha_Inc       | $5,068,376   | $432,379     | 7.86%    | 2.09%        | 10.45        |
| Epsilon_Group   | $7,841,009   | $651,736     | 7.67%    | 3.08%        | 10.70        |
| Gamma_Co        | $7,228,318   | $598,287     | 7.64%    | 5.01%        | 10.25        |
| Delta_Logistics | $6,283,847   | $515,419     | 7.58%    | 14.70%       | 11.03        |
| **Total**       | $34,061,740  | $2,909,996   | 7.87%    | 7.02%        | 10.74        |

### Insights
- **Savings leaders**: Beta_Supplies (highest rate and absolute savings), followed by Alpha_Inc.
- **Quality leaders**: Alpha_Inc and Epsilon_Group (lowest defect rates, well below average).
- **Quality concerns**: Delta_Logistics (14.70%) and Beta_Supplies (9.80%) drive most defects.
- **Delivery**: Consistent across suppliers (10–11 days).

### Good vs Defective Units
- Predominantly good units across all suppliers.
- Largest defective proportions visible for Delta_Logistics and Beta_Supplies.

### Savings vs Defect Rate (Scatter)
- **Star performers**: Alpha_Inc and Epsilon_Group (strong savings + low defects).
- **Trade-off**: Beta_Supplies (highest savings but higher defects).
- **Improvement target**: Delta_Logistics (lowest savings + highest defects).

---

## Page 3: Quality & Compliance

<img width="1103" height="619" alt="image" src="https://github.com/user-attachments/assets/262993fe-3ad1-458f-8352-c887eac3c687" />


### Key Metrics
| Metric                   | Value    |
|--------------------------|----------|
| Total Defective Units    | 42,758  |
| Average Defect Rate      | 7.02%   |
| Average Delivery Days    | 10.74   |
| Compliance Rate          | 83.45%  |

### Insights
- 42,758 defective units represent tangible downstream costs.
- Quality is a moderate risk area with clear improvement potential.

### Defects by Item Category
- Highest average defect rates: Office Supplies (~7.97%) > Raw Materials > Electronics > MRO > Packaging.
- Highest absolute defects: Office Supplies and Raw Materials.

### Defective Units by Supplier
| Supplier        | Defective Units | Share |
|-----------------|-----------------|-------|
| Delta_Logistics | ~17K           | ~40% |
| Beta_Supplies   | ~13K           | ~30% |
| Gamma_Co        | ~6K            | ~15% |
| Epsilon_Group   | ~4K            | ~9%  |
| Alpha_Inc       | ~3K            | ~6%  |

- Delta_Logistics is the primary quality risk (disproportionate defect share relative to volume).

### Top 10 High-Risk Purchase Orders
- Defect rates: 16.5–18.7% (well above overall 7.02%).
- 9 of 10 POs from Delta_Logistics across multiple categories.
- Recommendation: Immediate supplier review and corrective actions with Delta_Logistics.

---

## Page 4: Trends Over Time

<img width="1111" height="615" alt="image" src="https://github.com/user-attachments/assets/e924225a-be9b-46c9-b978-819af9b876ac" />


### Spend & Savings Trends
- Overall spend shows a downward trend over the period.
- Seasonal pattern: Strong Q1 activity, mid-year slowdown, moderate recovery.
- Savings were front-loaded (highest in early high-spend months).
- Opportunity: Apply early-year negotiation tactics consistently to maintain higher savings rates.

### Quantity & Defects Trends
- Ordered quantity relatively stable month-to-month (~40–60K units), with peak toward end of Q1.
- Defective units track proportionally with quantity (2K–4.5K monthly range).
- Positive outcome: Quality processes remain consistent regardless of volume fluctuations.

### Overall Trend Summary
- Procurement maintains stable operational volume and quality through seasonal cycles.
- Spend and savings variations present targeted optimization opportunities.


Done by Diego Martinez Zubillaga
