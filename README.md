# 📊 Walmart Retail Sales Analysis & 2013 Forecasting Dashboard

An end-to-end interactive **Time Series & Sales Forecasting Dashboard** built in **Microsoft Excel**. This project analyzes over **420,000+ retail sales records** ($6.74B in total revenue) across **45 Walmart stores** and multiple departments from 2010 to 2012, applying statistical forecasting techniques to project 2013 seasonal revenue trends.

---

## 🎯 Project Objectives
- **Data Consolidation & Cleaning:** Merge and clean multi-source historical retail datasets (`train`, `features`, and `stores`) exceeding 420K rows.
- **Trend & Seasonality Analysis:** Identify multi-year revenue patterns, holiday spikes (Super Bowl, Labor Day, Thanksgiving, Christmas), and store-type performance (Type A, B, and C).
- **Demand Forecasting:** Project 2013 monthly sales trajectories using **3-Month Moving Averages** and **Exponential Smoothing (ETS)** to support inventory and resource planning.
- **Executive Reporting:** Deliver an interactive, user-friendly Excel dashboard with dynamic slicers for real-time filtering.

---

## 🛠️ Tools & Technical Stack
- **Microsoft Excel:** Core analytical environment and dashboard UI/UX design.
- **Power Query (ETL):** Data extraction, merging relational tables, handling missing values (CPI & Unemployment), and standardizing date formats.
- **Power Pivot & Data Modeling:** Built a Star Schema data model linking fact sales tables with store metadata and calendar dimensions.
- **DAX (Data Analysis Expressions):** Engineered dynamic KPI measures including Total Sales, YoY Growth %, 3-Month Moving Average, Holiday vs. Non-Holiday Sales, and Average Weekly Sales.
- **Forecasting Techniques:** Applied Excel's native **ETS (Exponential Triple Smoothing)** algorithm with confidence intervals alongside **Moving Averages** to smooth short-term fluctuations.

---

## 📈 Key Insights & Findings
- **Total Revenue:** Analyzed **$6.74 Billion** in cumulative sales across 45 stores (2010–2012).
- **Strong Seasonality:** Revenue consistently peaks in **Q4 (November & December)** driven by Thanksgiving and Christmas shopping surges, followed by a predictable post-holiday dip in January.
- **Store Type Performance:** **Type A** stores generate the highest overall revenue volume, significantly outperforming Type B and Type C locations.
- **2013 Forecast Outlook:** The ETS model projects steady baseline growth in 2013 while maintaining recurring Q4 seasonal spikes, providing clear upper and lower confidence bounds for inventory buffer planning.

---

## 🎛️ Dashboard Features
- **Executive KPI Cards:** High-level summary of Total Sales, YoY Growth, Average Weekly Sales, and Forecasted Revenue.
- **Interactive Slicers:** Filter dynamically by **Year**, **Store Type (A/B/C)**, and **Holiday Flag**.
- **Time Series & Forecast Visuals:** Line charts comparing Historical Sales, 3-Month Moving Averages, and 2013 ETS Forecast projections with confidence bounds.
- **Store & Regional Breakdown:** Comparative bar charts highlighting top-performing stores and seasonal patterns.

---
