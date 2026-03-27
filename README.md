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

## 🔍 Key Insights & Findings
* **Financial Health:** The business maintains a healthy 60.3% overall profit margin, generating $21M in profit from $34M in revenue.
*  **Product Superstars:** Manuka Honey Choco and Orange Choco are top performers with profit margins exceeding 78%.
*  **The "Efficiency Gap":** While total sales are high, the current month saw a 10.8% MoM decline, signaling a need for immediate marketing intervention.
*  **Shipping Bottlenecks:** Shipment analysis shows a heavy concentration of small-batch shipments (0–500 units), which may be driving up the $14M total cost.

## 🧭 Strategic Recommendations (Solutions)
* **High-Margin Focus:**
- Action: Allocate 20% more marketing budget to Choco Coated Almonds and Manuka Honey Choco.
- Reason: These products have the highest "LBS %" and profit margins (76.4%+), offering the best ROI.

* **Cost Optimization:**
- Action: Review the logistics strategy for Baker's Choco Chips.
- Reason: This product has the lowest profit margin at 17.4%, likely due to high production or shipping costs relative to its price point.

# ##Regional Strategy:**
- Action: Launch a "Recovery Campaign" in underperforming regions filtered by the interactive slicers to reverse the -10.8% MoM trend.

## 📊 Data Architecture
The report is built on a robust relational data model (Star Schema):
* **Shipment Data (Fact Table):** Contains transaction-level details (Sales, Boxes, Dates).
* **Product Dimension:** Detailed info on product categories and cost per box.
* **Geo Dimension:** Mapping countries to their respective global regions.
* **People Dimension:** Sales team hierarchy and personnel details.
* **Calendar Table:** A custom Date table used for Time Intelligence calculations (YoY, MTD, etc.).

## 🛠️ Tools & Tech Stack.
- **Power BI Desktop:** For ETL, Data Modeling, and Visualization.
- **Power Query:** Used for data cleaning and standardizing regional names.
- **DAX (Data Analysis Expressions):** Created custom measures for:
    - `Total Sales`
    - `Total Boxes`
    - `Profit Margin %`
    - `Average Sales per Shipment`
- **Interactive Features:** Bookmarks for switching between Sales, Boxes, Shipment, Cost, and Profit views.

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

