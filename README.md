# Sales Performance Analysis Dashboard | Power BI

An interactive sales analytics project built with Microsoft Power BI and DAX to explore revenue, sales volume, product performance, and regional performance.

## Project Overview

This project analyzes a sample sales dataset to demonstrate how business data can be transformed into useful insights. The report contains two pages:

- **Sales Overview:** KPI cards, product revenue comparisons, sales volume by product, regional revenue comparisons, and interactive slicers.
- **Business Insights:** Findings, business implications, and recommendations based on the analysis.

## Business Questions

1. Which product generates the highest revenue?
2. Which product has the highest sales volume?
3. Which region contributes the most revenue?
4. How can the findings support inventory planning and business decisions?

## Dashboard Preview

### 1. Sales Overview

(![Sales Overview Dashboard](Sales%20Overview.png))

This page presents key performance indicators and charts comparing revenue by product, quantity sold by product, and revenue by region. Product and region slicers allow users to explore the data interactively.

### 2. Business Insights and Recommendations

![Business Insights Dashboard](Business%20Insight.png)

This page summarizes the key findings and translates them into practical recommendations for inventory planning, product performance monitoring, and regional sales improvement.

## Key Performance Indicators

| Metric | Result |
|---|---:|
| Total Revenue | Approximately ₦49,200 |
| Total Quantity Sold | 36 units |
| Average Selling Price | Approximately ₦1,366.67 per unit |

*Figures are based on the current report and are rounded for presentation.*

## Key Findings

### Product Revenue

Rice generated the highest revenue at approximately ₦20,000, followed by Beans at ₦18,000 and Garri at ₦11,200.

**Business implication:** Maintain appropriate stock levels for strong revenue contributors while investigating opportunities to improve revenue from other products.

### Sales Volume

Garri recorded the highest sales volume, followed by Beans and Rice.

**Business implication:** High sales volume does not automatically mean the highest revenue. Comparing both measures helps the business evaluate product performance more effectively.

### Regional Performance

The East region generated the highest revenue, followed by the West and North regions.

**Business implication:** Investigate the factors associated with stronger sales in the East and explore ways to improve performance in other regions.

## Tools and Skills Demonstrated

- Microsoft Power BI
- DAX measures
- KPI development
- Data visualization
- Interactive slicers and filtering
- Product and regional performance analysis
- Business insight development and recommendations

## DAX Measures

### Total Revenue

```DAX
Total Revenue =
SUM('Day 5 Project'[Total Sales])
```

### Total Quantity Sold

```DAX
Total Quantity Sold =
SUM('Day 5 Project'[Quantity])
```

### Average Selling Price

```DAX
Average Selling Price =
DIVIDE(
    [Total Revenue],
    [Total Quantity Sold],
    0
)
```

Average selling price is calculated as total revenue divided by total units sold. It is not the same as cost price.

## Business Recommendations

- Maintain appropriate inventory for products with strong revenue and sales volume.
- Investigate differences between product sales volume and revenue contribution.
- Study the factors behind the East region's stronger performance.
- Monitor key sales metrics regularly to support data-informed decisions.

## Project Files

- [Download the Power BI Dashboard (.pbix)](./Sales_Performance_Dashboard.pbix) — interactive Power BI report.
- Dashboard screenshots are displayed in the preview section above.

## Project Reflection

This project strengthened my practical understanding of DAX measures, KPI reporting, interactive dashboard design, and translating numerical results into business recommendations.

It is part of my ongoing journey in data analytics and my development of practical, portfolio-ready projects.

---

**Tools:** Microsoft Power BI | DAX

**Project type:** Sales performance analysis and business intelligence
