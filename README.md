# 📊 Financial Sales Analysis Report — Power BI
> Power BI | DAX | Financial Analytics | Multi-Country

> **An end-to-end interactive financial dashboard built with Power BI, powered by DAX measures and multi-dimensional sales data.**

---

## 🚀 Project Overview

This Power BI report delivers a comprehensive financial and sales performance analysis across multiple countries, product lines, and market segments. It features three fully interactive report pages designed to help stakeholders make data-driven decisions at a glance.

| Report Page | Purpose |
|---|---|
| 📈 **Financial Dashboard** | High-level KPI overview with trend analysis |
| 🗺️ **Sales Report** | Geographic and product-level sales breakdown |
| 💰 **Profit & Units Report** | Profitability and quantity sold deep-dive |

---

## 🎯 Key Features

- ✅ **DAX Measures** — Custom calculated metrics including Total Sales, Total Profit, Total Gross Sales, and Total Quantity Sold
- ✅ **Dynamic Slicers** — Filter by Year, Product, Segment, and Country for real-time cross-filtering
- ✅ **Multi-page Navigation** — Three dedicated report pages for layered storytelling
- ✅ **Geo Mapping** — Interactive maps visualizing profit and sales by country
- ✅ **Combo & Waterfall Charts** — Advanced chart types for segment-level profitability analysis

---

## 📐 Report Pages Breakdown

### 1️⃣ Financial Dashboard
The executive summary page — built around 4 KPI cards and trend visuals.

- **KPI Cards:** Total Sales · Total Gross Sales · Total Profit · Total Quantity Sold
- **Line Chart:** Sales and profit trends over time (Year/Month hierarchy)
- **Clustered Column Chart:** Total Profit by Country
- **Clustered Bar Chart:** Total Quantity Sold by Product
- **Pie Chart:** Total Sales breakdown by Market Segment
- **Slicers:** Year · Product · Segment

### 2️⃣ Sales Report
A geographic and product-focused view for regional performance analysis.

- **Map Visual (x2):** Total Profit by Country · Total Sales by Country
- **Clustered Column Chart:** Total Sales by Country and Product
- **100% Stacked Bar Chart:** Segment distribution by Country
- **Slicers:** Country · Product · Segment

### 3️⃣ Profit & Units Report
A deep-dive into profitability and unit economics across products and segments.

- **Line & Stacked Column Combo Chart:** Profit trends by Segment over time
- **Waterfall Chart:** Quantity Sold breakdown by Product and Segment
- **Donut Chart:** Total Profit share by Country
- **Pie Chart:** Total Profit by Product
- **Clustered Bar & Column Charts:** Quantity Sold by Country and Product

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-Measures-0078D4?style=for-the-badge)
![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Financial%20Data-green?style=for-the-badge)

- **Platform:** Microsoft Power BI Desktop
- **Query Language:** DAX (Data Analysis Expressions)
- **Dataset:** `financials` — containing fields: Country, Product, Segment, Date, Sales, Gross Sales, Profit, Quantity Sold
- **File Format:** `.pbix`

---

## 📊 DAX Measures Used

```dax
Total Sales = SUM(financials[Sales])
Total Gross Sales = SUM(financials[Gross Sales])
Total Profit = SUM(financials[Profit])
Total Quantity Sold = SUM(financials[Units Sold])
```

---

## 💡 Skills Demonstrated

- Business Intelligence (BI) Dashboard Design
- DAX formula writing and measure creation
- Data storytelling across multiple report pages
- Cross-filtering and interactive slicer implementation
- Geographic data visualization using Power BI Maps
- Advanced chart selection (Waterfall, Combo, 100% Stacked Bar)
- Financial domain understanding (Gross Sales, Net Profit, Segmentation)

---

## 📁 File Structure

```
Financial_Sales_Analysis_Report_Power_BI.pbix
├── Financial Dashboard        ← Page 1: Executive KPI Overview
├── Sales Report               ← Page 2: Geographic & Product Sales
└── Profit & Units Report      ← Page 3: Profitability Deep-Dive
```
## Key Insights
- France is the top profit market at $3.8M; Mexico at $2.9M — gap visible and filterable
- Government segment drives 44.22% of Total Sales — largest revenue source
- Paseo is the highest-volume product — supply chain prioritisation signal
- Time-series analysis reveals Q4 sales acceleration — supports quarterly forecasting

## Tech Stack
- Power BI Desktop (2-page report, slicers, geo maps, cross-filter)
- DAX (Total Sales, Total Profit, Average Sales, Max Sales, YoY trends)
- Data: Financial Sales dataset ($118.73M sales, 5 countries, 5 segments, 6 products)

## Buisness Problem It Solves
- Leadership couldn’t see which countries were driving profit vs. dragging it — now it’s one click.
-  Segment data was siloed — now Government (44%), Small Business (36%), and Enterprise (17%) are visible side-by-side
-  very business question required a manual data pull — now it’s fully self-service

---

## Dasboard Images
<img width="601" height="336" alt="Screenshot 2026-05-20 021543" src="https://github.com/user-attachments/assets/4131fa47-f2e8-4c3c-9911-c25cf316a14e" /> <img width="601" height="338" alt="image" src="https://github.com/user-attachments/assets/ea133048-1095-43d4-a6d7-07abebf798a2" />

> 📬 *Feel free to connect or reach out if you'd like to discuss this project or explore collaboration opportunities!
- Prateek Gupta
- Email : prateekgupta545@gmail.com
- Phone : +91-8074780272
