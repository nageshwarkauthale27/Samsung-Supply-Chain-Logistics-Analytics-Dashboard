# 📊 Samsung Supply Chain & Logistics Analytics Dashboard

> **Power BI | DAX | Power Query | Data Modeling | Star Schema | Business Intelligence**

An end-to-end interactive Supply Chain and Logistics Analytics Dashboard built in Power BI for Samsung, covering Supplier Performance, Inventory Management, Shipment Tracking, Customer Revenue Analysis, and Executive-level KPI reporting.

---

## 🖼️ Dashboard Preview

> *Add screenshots of your dashboard pages here*
> To add: Go to Power BI → Take screenshot of each page → Upload to this repo → Replace the lines below

| Executive Overview | Supplier Analytics |
|---|---|
| ![Executive Overview](screenshots/executive_overview.png) | ![Supplier Analytics](screenshots/supplier_analytics.png) |

| Inventory Analytics | Shipment Analytics |
|---|---|
| ![Inventory](screenshots/inventory_analytics.png) | ![Shipment](screenshots/shipment_analytics.png) |

---

## 📌 Project Overview

This project was developed to provide Samsung's business stakeholders with a centralized, real-time view of their entire supply chain operations — from procurement and inventory to logistics and customer revenue — through a multi-page interactive Power BI dashboard.

---

## 🗂️ Dashboard Pages

| Page | Description |
|---|---|
| 🏠 Executive Overview | High-level KPIs: Revenue, Profit, Order Rate, Lead Time |
| 🏭 Supplier Analytics | Supplier quality scores, lead times, unit cost tracking |
| 📦 Inventory Analytics | Inventory value, safety stock, reorder points, defects |
| 🚚 Shipment Analytics | Delivery success, carrier performance, delay reasons |
| 👥 Customer Analytics | Revenue by customer, channel, category, and trend |

---

## 📐 Data Model — Star Schema

```
                    ┌─────────────┐
                    │  DimDate    │
                    └──────┬──────┘
                           │
┌──────────────┐    ┌──────┴──────┐    ┌──────────────┐
│ DimSupplier  ├────┤  FactSales  ├────┤ DimCustomer  │
└──────────────┘    └──────┬──────┘    └──────────────┘
                           │
              ┌────────────┼────────────┐
              │            │            │
     ┌────────┴───┐  ┌─────┴──────┐  ┌─┴──────────────┐
     │DimInventory│  │DimShipment │  │DimProcurement  │
     └────────────┘  └────────────┘  └────────────────┘
```

**Fact Tables:** Sales, Shipment, Procurement, Production
**Dimension Tables:** Supplier, Customer, Inventory, Date, Product

---

## 📊 Key KPIs and Metrics

### 💰 Revenue and Profit
| KPI | Value |
|---|---|
| Gross Revenue | 186.86M |
| Total Revenue | 176.95M |
| Total Profit | 48.56M |
| Profit Margin | 27.44% |

### 🏭 Supply Chain
| KPI | Description |
|---|---|
| Perfect Order Rate | 75.29% — Orders delivered on time, complete, damage-free |
| Average Lead Time | Tracks average days from order to delivery per supplier |
| Supplier Quality Score | Measures defect rate and rejection percentage per supplier |
| Unit Cost | Monitors procurement cost per unit across suppliers |

### 📦 Inventory
| KPI | Description |
|---|---|
| Inventory Value | Total value of current stock |
| Safety Stock Level | Minimum stock threshold to prevent stockouts |
| Reorder Point | Trigger level for new procurement orders |
| Inventory Turnover Rate | How many times inventory is sold/used in a period |
| Days of Inventory | Average days stock lasts before replenishment |
| Defective Units | Count of rejected or damaged inventory items |

### 🚚 Shipment
| KPI | Description |
|---|---|
| Delivered Shipment % | Percentage of shipments successfully delivered |
| Total Shipment Quantity | Total units shipped across all carriers |
| Shipment Cost | Total and average cost per shipment |
| Carrier Performance | On-time delivery rate per carrier |
| Delay Reason Analysis | Categorized reasons for delivery delays |

### 👥 Customer
| KPI | Description |
|---|---|
| Revenue by Customer | Top customers ranked by revenue contribution |
| Revenue by Channel | Online vs Offline vs Partner channel breakdown |
| Profit by Channel | Profitability analysis across sales channels |
| Category Revenue | Performance by product category |
| Revenue Growth Trend | Month-over-month and year-over-year growth |

---

## ⚙️ Advanced Power BI Features Used

- ✅ **Star Schema Data Modeling** — optimized relationships for fast queries
- ✅ **20+ DAX Measures** — calculated KPIs using DIVIDE, CALCULATE, SUMX, FILTER
- ✅ **Drill-through Navigation** — click through from summary to detail pages
- ✅ **Interactive Slicers** — filter by date, supplier, product, region
- ✅ **Bookmark Navigation** — seamless page switching with buttons
- ✅ **KPI Cards** — at-a-glance performance indicators
- ✅ **Trend Analysis** — line charts with moving averages
- ✅ **Cross Filtering** — visuals filter each other dynamically
- ✅ **Custom Tooltips** — hover for additional context on charts

---

## 💡 Business Impact

- 📌 Centralized 5+ operational domains into one unified dashboard
- 📌 Enabled supplier performance benchmarking and quality tracking
- 📌 Identified inventory bottlenecks and optimized reorder thresholds
- 📌 Pinpointed shipment delay causes by carrier and route
- 📌 Provided revenue and profitability insights across channels and customers

---

## 🛠️ Tools and Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

---

## 📂 Repository Structure

```
Samsung-Supply-Chain-Dashboard/
│
├── Samsung.pbix                  # Main Power BI Dashboard file
├── README.md                     # Project documentation
└── screenshots/                  # Dashboard page screenshots
    ├── executive_overview.png
    ├── supplier_analytics.png
    ├── inventory_analytics.png
    ├── shipment_analytics.png
    └── customer_analytics.png
```

---

## 🚀 How to Open This Project

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)
2. Clone or download this repository
3. Open `Samsung Supply Chain & Logistics Analytics Dashboard.pbix` in Power BI Desktop
4. Explore the dashboard pages using the navigation tabs at the bottom

---

## 👤 Author

**Nageshwar Eknath Kauthale**
📧 nageshwarkauthale27@gmail.com
🔗 [LinkedIn](https://linkedin.com/in/nageshwar-kauthale-aaa781249)
🐙 [GitHub](https://github.com/nageshwarkauthale27)

---

⭐ *If you found this project helpful, please give it a star!*
