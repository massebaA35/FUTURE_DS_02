# Sales Intelligence Dashboard — Retention & Churn

**Business Analytics | 2023 – 2025**

An interactive analytics dashboard built to track customer retention, churn, and sales performance across regions, categories, and segments. Designed for quick, filter-driven exploration of business KPIs.

![Dashboard Preview](Screenshot_2026-06-27_105956.png)

## 📊 Overview

This dashboard provides a 360° view of customer churn behavior and sales trends, enabling stakeholders to identify at-risk segments, regional performance gaps, and category-level revenue drivers.

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Customers | 8,680 |
| Churned Customers | 8,387 |
| Retained Customers | 293 |
| Churn Rate | 96.6% |
| Retention Rate | 3.4% |

## 📈 Dashboard Components

- **Customer Trend** — Monthly customer count trend across 2023–2026
- **Churn by Region** — Churned vs. retained customers split by Central, East, South, and West
- **Customer Churn Distribution** — Donut chart of overall churn vs. retention split
- **Customers by Segment** — Breakdown by Consumer, Corporate, and Home Office
- **Sales vs Profit by Quantity** — Bubble chart comparing sales, profit, and order volume by region
- **Sales by Region** — Total sales by region, broken down by customer segment
- **Sales by Category** — Total sales by product category (Technology, Furniture, Office Supplies), by year
- **Monthly Sales Trend** — Year-over-year monthly sales performance

## 🎛️ Filters

The dashboard supports dynamic slicing by:
- Year
- Quarter
- Region
- Category
- Segment

## 🛠️ Tech Stack

> _Update this section with the actual tools used (e.g., Power BI, Tableau, Looker Studio)._

- Visualization Tool: `Power BI / Tableau`
- Data Source: `Sales & Customer dataset (2023–2025)`
- Refresh Frequency: `Manual / Scheduled`

## 📁 Project Structure

```
sales-intelligence-dashboard/
├── data/                  # Raw and cleaned datasets
├── reports/               # Dashboard files (.pbix / .twbx)
├── images/                # Screenshots and exports
└── README.md
```

## 🚀 Getting Started

1. Clone this repository
   ```bash
   git clone https://github.com/massebaA35/sales-intelligence-dashboard.git
   ```
2. Open the report file in your BI tool of choice
3. Connect to the underlying data source (or use the sample dataset in `/data`)
4. Refresh the data and explore using the filter panel

## 📌 Insights at a Glance

- Churn is heavily concentrated, with a **96.6% churn rate** against only **3.4% retention**
- **Technology** leads total sales among product categories
- Sales performance is fairly consistent across **East, South, West, and Central** regions
- **Consumer** segment represents the largest customer base

## 🙋 Author

Built by **[massebaA35](https://github.com/massebaA35)** — feel free to connect or open an issue for suggestions.
