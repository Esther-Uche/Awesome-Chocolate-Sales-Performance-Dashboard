# 🍫 Awesome Chocolate Sales Analysis

![Awesome-Chocolate-Sales-Performance-Dashboard](./Awesome-Choco.png)
## 📋 Project Overview
 This Power BI project provides a 360-degree view of Awesome Chocolates' global operations analyzing $34M in total sales and 6K shipments inorder to identify profitability drivers, sales performance, product trends, cost inefficiencies, and market expansion opportunities across multiple regions including the USA, UK, India, Canada, and Australia.

## 🎯 Business Problem and Objective
The organization faced challenges in tracking real-time profit margins across diverse product lines (Bars, Bites, etc.) and understanding the correlation between shipment volumes and operational costs.

* **Objectives:**
* **Analyze Profitability:** Monitor the 60.3% global profit margin and identify underperforming products.
* **Operational Efficiency:** Evaluate shipment distributions and cost-to-sales ratios.
* **Market Intelligence:** Compare performance across different global territories and product categories.
* **Revenue Analysis:** Track total sales and shipment volumes (boxes) over time.
* **Geographical Insights:** Identify high-performing regions (APAC, Americas, Europe).
* **Product Performance:** Analyze sales by category (Bars, Bites, Others) and specific products.
* **Sales Team Evaluation:** Monitor individual salesperson performance and team rankings (Team Yummies, Delish, Jucies).

## 📊 Data Architecture
The report is built on a robust relational data model (Star Schema):
* **Shipment Data (Fact Table):** Contains transaction-level details (Sales, Boxes, Dates).
* **Product Dimension:** Detailed info on product categories and cost per box.
* **Geo Dimension:** Mapping countries to their respective global regions.
* **People Dimension:** Sales team hierarchy and personnel details.
* **Calendar Table:** A custom Date table used for Time Intelligence calculations (YoY, MTD, etc.).

## 🛠️ Tools & Tech Stack
- **Power BI Desktop:** For ETL, Data Modeling, and Visualization.
- **Power Query:** Used for data cleaning and standardizing regional names.
- **DAX (Data Analysis Expressions):** Created custom measures for:
    - `Total Sales`
    - `Total Boxes`
    - `Profit Margin %`
    - `Average Sales per Shipment`

## 💡 Business Insights
- **Top Region:** The **APAC** region (specifically India and New Zealand) shows the highest frequency of high-volume shipments.
- **Top Product:** Premium items like **85% Dark Bars** and **Raspberry Choco** are major revenue drivers.
- **Team Efficiency:** **Team Yummies** consistently leads in total sales volume across most quarters.

## 📂 How to Use
1.  **Download** the `Awesome Chocolate.pbix` file.
2.  Open it using [Power BI Desktop](https://powerbi.microsoft.com/desktop/).
3.  Interact with the **Slicers** on the left to filter by Region, Product, or Salesperson.

---

## 👤 Author
**[Uchechi Esther]**
*Data Analyst | Power BI Enthusiast*



---
*Note: This project uses sample data for demonstration purposes.*

