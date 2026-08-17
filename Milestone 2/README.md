<div align="center">

# 📦 Supply Chain Analytics – Milestone 2

### Inventory Analytics & Delivery Performance Dashboard using Power BI

Building an interactive analytics dashboard to monitor **Inventory Performance**, **Inventory Turnover**, **Stock Movement**, and **Delivery Performance** using **Power BI**, **Power Query**, **DAX**, and **PostgreSQL**.

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-005A9C?style=for-the-badge)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge)

</div>

---

# 📖 Project Overview

This repository contains **Milestone 2** of the **Supply Chain Analytics Project**.

The objective of this milestone is to analyze inventory efficiency and delivery performance to help businesses:

- Optimize inventory investment
- Reduce slow-moving and dead stock
- Improve inventory turnover
- Enhance delivery performance
- Support data-driven supply chain decisions

The dashboard is built entirely in **Power BI** using data imported from **PostgreSQL**.

---

# 🎯 Business Objectives

- Monitor inventory health
- Measure inventory turnover
- Identify fast-moving and slow-moving products
- Track delivery delays
- Evaluate shipping performance
- Support inventory optimization

---

# 🛠 Tech Stack

- **Power BI**
- **Power Query**
- **DAX**
- **PostgreSQL**

---

# 📊 Dashboard Overview

## 1️⃣ Inventory Analytics Dashboard

This dashboard focuses on inventory efficiency using KPIs and trend analysis.

### KPIs

- Total Inventory Value
- Inventory Turnover
- Stock Quantity
- Slow Moving Inventory
- Fast Moving Inventory
- Dead Stock
- Average Days Since Last Sale

### Visuals

- Inventory Value by Category
- Inventory Turnover Trend
- Stock Status Distribution
- Inventory by Warehouse
- Top Products by Inventory Value
- Product Performance Analysis

---

## 2️⃣ Delivery Performance Dashboard

This dashboard evaluates shipping efficiency and delivery operations.

### KPIs

- Total Orders
- On-Time Deliveries
- Late Deliveries
- Average Delivery Time
- On-Time Delivery %
- Late Delivery %

### Visuals

- Delivery Status Breakdown
- Delivery Trend
- Shipping Mode Performance
- Region-wise Delivery Analysis
- Average Delivery Time by Category

---

# 📈 Inventory Turnover Calculation Approach

### Formula

```
Inventory Turnover =
Cost of Goods Sold (COGS)
--------------------------------
Average Inventory Value
```

Since detailed COGS was not available in the dataset, inventory turnover was estimated using inventory movement metrics available in the transactional data.

### Interpretation

- Higher turnover indicates products are selling quickly.
- Lower turnover suggests excess inventory or slow sales.
- Very low turnover may indicate dead stock.

---

# 🚀 Slow-Moving & Fast-Moving Inventory Identification Logic

| Inventory Type | Logic |
|---------------|-------|
| Fast Moving | Days Since Last Sale ≤ 30 |
| Normal Stock | 31 – 90 Days |
| Slow Moving | > 90 Days |
| Dead Stock | No sales for extended period while stock is available |

### Benefits

- Detect excess inventory
- Reduce holding costs
- Improve replenishment planning
- Increase warehouse efficiency

---

# 🚚 Delivery Performance Analysis Methodology

Delivery performance was evaluated by comparing:

- Order Date
- Shipping Date
- Delivery Duration

### Key Metrics

- Average Delivery Time
- On-Time Delivery %
- Late Delivery %
- Orders Delivered
- Delivery Delay Trends

### Business Analysis

The dashboard enables businesses to:

- Monitor shipping efficiency
- Identify delivery bottlenecks
- Compare regional performance
- Improve customer satisfaction

---

# 📊 Key Insights

### Inventory

- Fast-moving products contribute significantly to inventory turnover.
- Slow-moving inventory occupies warehouse space and increases carrying costs.
- Dead stock should be reviewed for clearance or discontinuation.
- Certain categories require better inventory replenishment planning.

### Delivery

- Most deliveries are completed within the expected timeframe.
- Delayed shipments can be monitored by region and shipping mode.
- Delivery trends help identify operational bottlenecks.
- Improving late delivery rates enhances customer experience.

---

# 💡 Business Recommendations

### Inventory Management

- Replenish fast-moving products more frequently.
- Reduce purchase quantities for slow-moving products.
- Clear dead stock through promotions or liquidation.
- Review reorder points using historical demand.

### Delivery Operations

- Improve logistics in regions with frequent delays.
- Optimize shipping routes to reduce delivery time.
- Monitor carrier performance regularly.
- Increase visibility into order fulfilment processes.

---

# 📌 Skills Demonstrated

- Data Modeling
- Data Cleaning
- Power Query Transformation
- DAX Measures
- KPI Design
- Inventory Analytics
- Supply Chain Analytics
- Delivery Performance Analysis
- Interactive Dashboard Design
- Business Intelligence

---

# 📷 Dashboard Preview

## Inventory Analytics

> *(Add screenshot here)*

screenshots/Inventory_Analytics.png

---

## Delivery Performance

> *(Add screenshot here)*

screenshots/Delivery_Performance.png

---

# 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Building business-focused Power BI dashboards
- Designing inventory analytics solutions
- Creating DAX measures for KPIs
- Performing delivery performance analysis
- Translating business requirements into actionable insights

---

# 👨‍💻 Author

**Prudhvi Surla**

Aspiring Data Analyst

Skills:
- Power BI
- PostgreSQL
- SQL
- DAX
- Power Query
- Data Visualization
- Business Intelligence

---

## ⭐ If you found this project helpful, consider giving it a Star!
