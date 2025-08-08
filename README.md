# 🌍 Global Super Store – Power BI Project

An interactive Power BI dashboard providing **end-to-end analytics** for Global Super Store, covering sales performance, customer behavior, and product trends. Designed to help management and analysts make **data-driven decisions** with actionable insights.

---

## 📊 Overview

This project transforms raw sales and returns data into an **interactive 6-page dashboard** for Global Super Store, enabling:

- 📈 Sales & profit trend analysis  
- 👥 Customer retention and segmentation tracking  
- 📦 Product performance and return monitoring  
- 🌍 Market and regional performance comparison  

---

## 📑 Dashboard Pages

1. **Home** – Intro page with clear navigation buttons to all dashboard sections.  
2. **Sales Report** – Sales, profit, orders, and returns, with visual trends and category breakdowns.  
3. **Sales Report 2** – Tabular profit analysis by time period, ship mode stats, and market-wise profit distribution.  
4. **Customer Analysis** – Cohort analysis for retention, profit/order trends by region, and segmentation.  
5. **Product Analysis** – KPIs for product counts, returns, discounts, delays, and profitability.  
6. **Product Analysis 2** – Profit breakdown by category/subcategory (waterfall chart) and country-wise orders (map view).

---

## 🧠 Data Modeling

The Power BI data model uses a **star schema** for optimal querying and dashboard performance.

### 🔹 Fact Table
- **FactOrders** – Sales, profit, quantity, discount, order date, ship date, customer key, product key, region key.  

### 🔸 Dimension Tables
- **DimCustomer** – Customer name, segment, and region.  
- **DimProduct** – Product name, category, subcategory.  
- **DimRegion** – Country, city, and market segmentation.  
- **DimPeople** – Sales representatives.  
- **DimReturns** – Returned order IDs and return status.  
- **DimDate** – Calendar table for time intelligence (Year, Quarter, Month).

> Relationships were defined using primary and foreign keys for accurate filtering and aggregations.

---

## 📈 Key Insights

- **U.S. market** contributes the highest revenue and orders.  
- **Accessories category** dominates in order count.  
- **Customer retention patterns** revealed through cohort analysis.  
- **Return rate** insights to address product and supply chain issues.  

---

## 🛠 Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX, dashboard design.  
- **Power Query Editor** – Data extraction, transformation, and loading (ETL).  
- **DAX (Data Analysis Expressions)** – KPIs and calculated measures.  
- **Excel Tables** – "Orders", "People", and "Returns" datasets.

---

## 🎯 Goal

Empower Global Super Store stakeholders with a single source of truth for sales, customer, and product data, driving operational improvements and strategic decisions.

---

## 📂 Files

- `Global-SuperStore.pbix` – Power BI dashboard file (not publicly shared).  
- PDF export of the dashboard – [Download here](https://drive.google.com/file/d/1448qag6ihSJIjOkLOFYd3UCcf2ImvOce/view?usp=sharing).

---
