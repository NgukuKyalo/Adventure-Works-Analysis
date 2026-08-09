# Adventure Works Sales Analysis (2015–2017)

A Power BI dashboard analyzing AdventureWorks sales data across product categories, customer occupations, and time, built to surface revenue, profitability, and growth trends between 2015 and 2017.

## 📊 Overview

This report is split into two pages:

- **Executive Summary** — high-level KPIs and category-level performance
- **Detailed Insights** — time-series trends, product color breakdown, seasonality, and occupation-level performance

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Revenue | $24.91M |
| Total Profit | $10.46M |
| Profit Margin % | 41.97% |
| Revenue YoY Growth % | 58.40% |

## 📈 Executive Summary

- **Total Revenue by Year** — revenue climbs sharply from 2015 to 2016, then levels off into 2017.
- **Total Revenue / Total Cost by CategoryName** — Bikes dominate both revenue and cost by a wide margin over Accessories and Clothing.
- **Profit Margin % by CategoryName** — Accessories and Clothing are the most profitable categories by margin, while Bikes (despite highest revenue) has the lowest margin.
- Filters: Year (2015/2016/2017), CategoryName (Select all, Accessories, Bikes, Clothing, Components)

## 🔍 Detailed Insights

- **Total Orders and Total Quantity Sold by Month-Year** — flat and low through mid-2016, then a sharp, sustained jump from ~Jul 2016 onward.
- **Total Quantity Sold by ProductColor** — ~60.68% of units sold have no color attribute (NA); Black is the top actual color at 12.58%.
- **Total Revenue and Revenue Previous Year by Month Name** — revenue is seasonal, peaking in spring (April–June) and dipping in late summer/early fall (July–September).
- **Occupation Breakdown (Total Orders, Total Revenue, Profit Margin %)** — Professional leads in orders and revenue; Management has the highest profit margin; Manual has the lowest of both. Conditional formatting (color scale) is applied to the Profit Margin % column.

## 💡 Key Recommendations
1. **Investigate the mid-2016 growth jump** — identify the driver (launch, channel, campaign, pricing) to determine if it's repeatable or a one-off.
2. **Plan around seasonality** — build inventory/staffing ahead of the spring peak; run promotions in the July–September trough.
3. **Confirm 2016→2017 growth trend** — reconcile the flat 2016–2017 revenue chart against the 58.4% YoY growth headline to understand where growth is concentrated.

## 🛠️ Built With

- Power BI Desktop
- AdventureWorks sales dataset

## 📂 Repository Structure

```
├── AdventureWorksSalesAnalysis.pbix   # Power BI report file
├── data/                              # Source data (if included)
└── README.md
```

## 🚀 Getting Started

1. Clone this repository
2. Open `AdventureWorksSalesAnalysis.pbix` in [Power BI Desktop](https://powerbi.microsoft.com/desktop/)
3. Refresh data connections if needed
4. Explore the Executive Summary and Detailed Insights pages

## 📄 License

Add your license here (e.g., MIT).
