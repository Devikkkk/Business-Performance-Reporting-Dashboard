# 📊 Business Performance Reporting Dashboard | Power BI

![Dashboard Preview](preview.jpg)

---

## 📌 Project Overview

This project presents an end-to-end **Business Performance Reporting Dashboard** built using **Power BI Desktop**, based on the Superstore Sales dataset. The dashboard enables stakeholders to monitor business performance across product categories, customer segments, regions, and time periods — supporting data-driven decision-making aligned to PMO reporting standards.

---

## 🎯 Business Objective

- Track overall business performance across **Sales, Profit, Quantity, and Discount** KPIs
- Analyse performance trends across **monthly, quarterly, and yearly** time dimensions
- Identify top-performing and underperforming **product categories and segments**
- Enable **regional and channel-level** performance monitoring via interactive filters
- Support **stakeholder reporting** through clear, intuitive visual storytelling

---

## 🗂️ Dataset

| Detail | Info |
|---|---|
| **File** | `sample_-_superstore_xls_-_Orders.csv` |
| **Source** | Superstore Sales Dataset |
| **Records** | 9,994 rows |
| **Time Period** | 2014 – 2017 |

### Key Columns

| Column | Description |
|---|---|
| Order Date | Date of order placement |
| Category / Sub-Category | Product classification |
| Segment | Customer segment (Consumer, Corporate, Home Office) |
| Region | Geographic region (Central, East, South, West) |
| Ship Mode | Shipping method used |
| Sales | Revenue generated |
| Profit | Profit earned |
| Quantity | Units sold |
| Discount | Discount applied |

---

## 🛠️ Tools & Skills Used

| Tool / Skill | Application |
|---|---|
| **Power BI Desktop** | End-to-end dashboard development |
| **Power Query** | Data cleaning, transformation, and date formatting |
| **Data Modelling** | Structured relationships for cross-dimensional analysis |
| **DAX Measures** | KPI calculations — Profit, Sales, Quantity, Discount aggregations |
| **Data Visualisation** | 12+ chart types for multi-dimensional reporting |
| **Interactive Slicers** | Year (2014–2017) and Region filters for dynamic reporting |

---

## 📊 Dashboard Components

### KPI Summary Cards
- **Total Sales** — 2.3M (all years)
- **Total Profit** — 286.3K
- **Total Quantity** — 37.9K
- **Total Discount** — 1.6K
- **Total Orders** — 9,994

### Visualisations

| Chart | Purpose |
|---|---|
| Bar Chart — Sales by Category | Compare Technology, Furniture, Office Supplies performance |
| Line Chart — Sales by Month | Identify monthly seasonality and sales trends |
| Combo Chart — Monthly Sales & Quantity Totals | Dual-axis view of volume vs revenue |
| Treemap — Category Sales Summation | Proportional category contribution |
| Pie Chart — Category Profits Summation | Profit share by category |
| Donut Chart — Sales by Ship Mode | Distribution across Standard, First, Second Class |
| Donut Chart — Sales by Segment | Consumer, Corporate, Home Office split |
| Donut Chart — Sales by Quarter | Seasonal quarterly performance |
| Scatter Chart — Sales and Profit | Correlation analysis between sales and profitability |
| Map — Geographic Distribution | Regional performance across North America |
| Table — Products Top 10 | Top performing products by sales value |

### Interactive Filters / Slicers
- **Year Slicer** — 2014, 2015, 2016, 2017
- **Region Slicer** — Central, East, South, West

---

## 📁 Repository Structure

```
Business-Performance-Reporting-Dashboard/
│
├── Sales_Analysis.pbix          # Power BI Desktop file
├── sample_superstore_orders.csv # Raw dataset
├── preview.jpg                  # Dashboard screenshot (all years)
├── sales_2014.jpg               # Dashboard — 2014 filtered view
├── reg_east_2016.jpg            # Dashboard — East Region 2016
├── reg_west_2017.jpg            # Dashboard — West Region 2017
└── README.md                    # Project documentation
```

---

## 🔍 Key Insights

- **Technology** is the highest revenue-generating category at **$0.84M**, followed by Furniture ($0.74M) and Office Supplies ($0.72M)
- **Q4 (Oct–Dec)** consistently drives the highest sales across all years — accounting for **38%** of annual revenue — indicating strong year-end demand
- **Standard Class** is the dominant shipping mode at **59%** of all shipments, suggesting an opportunity to optimise logistics costs
- **Consumer segment** drives the majority of sales at **50.56%**, followed by Corporate (30.74%) and Home Office (18.7%)
- Sales show a clear **upward trend from 2014 to 2017**, growing from $484.2K to $2.3M cumulatively

---

## 📸 Dashboard Screenshots

### All Years — Overview
![All Years](preview.jpg)

### 2014 — Annual View
![2014](sales_2014.jpg)

### East Region — 2016
![East 2016](reg_east_2016.jpg)

### West Region — 2017
![West 2017](reg_west_2017.jpg)

---

## 🚀 How to Use

1. Clone or download this repository
2. Open `Sales_Analysis.pbix` in **Power BI Desktop**
3. Use the **Year** buttons (2014–2017) to filter by year
4. Use the **Region** slicer (Central, East, South, West) to filter by geography
5. Hover over any visual for detailed tooltips and data breakdowns

---

## 👤 Author

**Devik Satyavenkat**  
CMI Level 7 | Power BI | Data Analytics | PMO Reporting  
🔗 [LinkedIn](https://www.linkedin.com/in/deviksatyavenkat)

---

## 📜 Skills Demonstrated

`Power BI` `Power Query` `Data Modelling` `DAX` `Data Visualisation` `KPI Reporting` `Trend Analysis` `Stakeholder Reporting` `Business Intelligence` `Interactive Dashboards`
