# Supermarket Sales Dashboard

An interactive, single-page Power BI dashboard designed to analyze retail performance, product weight distributions, and revenue generation across various supermarket outlets. This project turns retail data into key operational insights regarding item demand, pricing strategies, and outlet characteristics.

---

## 📊 Dashboard Preview

![Supermarket Sales Dashboard Preview](./dashboard_preview.png)

---

## 🚀 Key Features & Insights

This dashboard gives store managers and retail analysts an executive lens into sales trends and product traits:

### 📊 Executive Summary KPIs
*   **Total Item Outlet Sales:** `10.56M` gross sales generated across all properties.
*   **Total Item MRP:** `658.98K` cumulative maximum retail price data footprint.
*   **Outlet Timeline Slicer:** Tracks store metrics established between **1987 and 2009**.

### 📉 Multi-Dimensional Slicers & Filters
*   **Item Fat Content:** Dynamic toggle panels classifying product performance into `LF`, `reg`, `Low Fat`, and `Regular`.
*   **Outlet Profiles:** Segments data instantly by **Outlet Size** (`High`, `Medium`, `Small`) and **Outlet Type** (`Supermarket Type1`, `Supermarket Type2`).
*   **Item Type Inventory:** High-impact multi-select menu grouping items from `Baking Goods` and `Meat` down to `Snack Foods` and `Household`.

### 📈 Core Visualizations
*   **Pricing Insights (Item_MRP by Item_Type):** Column chart indicating maximum retail price ceilings across product groups, led strongly by **Fruits and Vegetables** and **Snack Foods**.
*   **Revenue Generation (Item_Outlet_Sales by Item_Type):** Vertical bar chart tracking top-earning inventory types, highlighting **Snack Foods** ($1.57M) and **Fruits and Vegetables** ($1.55M) as primary cash cows.
*   **Sales Run Rate (Item_Outlet_Sales by Item_Type):** Horizontal comparison bar tracking core baseline earnings.
*   **Vintage Performance (Item_Outlet_Sales by Outlet_Establishment_Year):** Comprehensive pie chart breaking down revenue streams by store age cohorts, showing consistent splits led by locations launched in **2004** (21.47%) and **1999** (20.67%).
*   **Logistics Weight Analysis (Item_Weight by Item_Type):** Area chart tracking total product distribution weights to help optimize logistics pipelines.

---

## 🛠️ Tech Stack & Tools

*   **BI Tool:** Power BI Desktop
*   **Data Layout:** Vibrant, color-blocked workspace using high-contrast segment containers to provide clear cognitive boundaries between filters, revenue plots, and product metrics.

---

## 📂 Folder Structure

This project lives in its own dedicated workspace within your portfolio directory:
```text
PowerBI-Data-Analytics-Portfolio/
├── Amazon-Prime-Video-Analytics/
├── College-Analysis-Dashboard/
├── Corporate-Sales-Performance-Dashboard/
├── Employee Attrition Dashboard/
├── HR-Analytics-Dashboard/
├── Job Market Analysis Dashboard/
├── Student Depression Analysis Dashboard/
└── Supermarket-Sales-Dashboard/       
    ├── README.md                      
    ├── SUPER MARKET SALES.pbix        
    └── dashboard_preview.png          
