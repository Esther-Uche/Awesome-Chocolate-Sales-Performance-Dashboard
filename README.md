# 🍫 Awesome Chocolate Sales Analysis

![Awesome-Chocolate-Sales-Performance-Dashboard](./Awesome-in-store.jpeg)
## 📋 Project Overview
This project is a comprehensive **Power BI Sales Dashboard** designed for "Awesome Chocolate," a global chocolate distributor. The analysis provides deep insights into sales performance, product trends, and team efficiency across multiple international markets including India, USA, UK, Canada, Australia, and New Zealand.

## 🎯 Key Objectives
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

