# My-Trainlyze-tasks
# 📊 Superstore Sales Performance Dashboard

An interactive business intelligence dashboard built in **Microsoft Excel** to analyze sales performance, profitability, regional distribution, product category trends, and top customer contributions across the Superstore retail dataset.

![Superstore Sales Dashboard](images/dashboard.png)

---

## 🎯 Project Overview
The goal of this project is to transform raw retail transaction data into a clean, dynamic executive dashboard that helps stakeholders monitor overall business health and quickly spot top-performing segments and loss-making sub-categories.

### Key Metrics Tracked (KPIs)
* **Total Revenue:** Overall sales generated across selected periods and segments
* **Total Profit:** Net profit performance across orders
* **Profit Margin (%):** Overall profitability ratio (`Total Profit / Total Revenue`)
* **Total Orders:** Count of unique customer orders
* **Average Order Value (AOV):** Average revenue generated per order

---

## 📈 Dashboard Visuals & Features
* **Monthly Revenue Trend by Year:** Multi-year line chart tracking seasonal revenue fluctuations and year-over-year growth.
* **Revenue and Profit by Sub-Category:** Clustered comparison highlighting high-revenue vs. low-margin or loss-making sub-categories.
* **Sales by States:** Filled geographic map visualizing state-level sales concentration across the United States.
* **Sales by Product Category:** Donut chart breaking down revenue share across *Technology*, *Furniture*, and *Office Supplies*.
* **Top 10 Customers by Revenue:** Horizontal bar chart ranking highest-value customers.
* **Profit by Sub-Category:** Column chart isolating profitable sub-categories from negative-margin items.
* **Interactive Filters & Time Period:** Dynamic slicers for **Region**, **Category**, and **Segment**, paired with an interactive **Date Timeline** filter connected to all visuals.

---

## 🛠️ Tools & Excel Techniques Used
* **Data Cleaning & Preparation:** Standardized date formats, removed duplicates, and structured tabular data for analysis.
* **PivotTables & PivotCharts:** Built dynamic aggregations powering every KPI card and chart.
* **Interactive Controls:** Configured Slicers and Timeline filters with multi-report connections for real-time cross-filtering.
* **Dashboard Design & UI:** Applied a consistent color palette, KPI card layout, clean axis formatting, and structured visual hierarchy.

---

## 💡 Key Business Insights
* **Top Revenue Drivers:** *Technology* and *Office Supplies* generate the largest share of overall revenue, while certain *Furniture* sub-categories (such as Tables and Bookcases) negatively impact overall profit margins.
* **Seasonality:** Monthly sales consistently peak in the final quarter of the year (Q4), reflecting strong year-end demand.
* **Geographic Concentration:** Coastal and major commercial states drive a disproportionate share of total revenue.

---

## 📂 Repository Structure
```text
├── Superstore_Sales_Dashboard.xlsx   # Main Excel workbook with Dashboard, KPIs, and Dataset
├── images/
│   └── dashboard.png                 # High-resolution screenshot of the dashboard
└── README.md                         # Project documentation
