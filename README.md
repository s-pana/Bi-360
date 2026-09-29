# AtliQ Hardware: Business Insights 360 (Power BI)

A business intelligence dashboard suite built in Power BI to monitor, analyze, and optimize operations across all business units for AtliQ Hardware.

📄 **[View Full Project PDF Report](chapter-11-bi360-10-compressed.pdf)**

---

## 📌 Executive Summary

Rapid global expansion led to data silos and blind spots across AtliQ Hardware's regional markets. This project unifies transactional enterprise data into actionable, role-based dashboards to support data-driven decision-making across executive, financial, and operational teams.

---

## 📊 Dashboard Modules

* **Finance View:** P&L statements, Net Sales trends over time, Gross Margin breakdown, and top products/customers by revenue contribution.
* **Sales View:** Customer performance matrices, net sales vs. target variances, and unit economics across sales channels.
* **Marketing View:** Divisional performance analysis, market share trends, and region-level Gross Margin % tracking.
* **Supply Chain View:** Forecast accuracy, net error, absolute error, and key indicators to prevent stockouts and inventory bloat.
* **Executive View:** High-level dashboard aggregating enterprise-level KPIs, market share metrics, and consolidated revenue trajectories for C-suite leadership.

---

## 🛠️ Technical Implementation

1. **Data Ingestion:** Extracted raw transactional data from MySQL database using optimized SQL queries.
2. **Data Modeling:** Built an optimized Star/Snowflake schema establishing clear relationships between fact and dimension tables.
3. **DAX Calculations:** Engineered dynamic measures for time-intelligence, target variance tracking, and complex P&L metrics.
4. **Interactive UI/UX:** Integrated dynamic slicers, KPI status indicators, bookmarks, tooltips, and conditional formatting.
5. **Data Validation:** Verified calculation results directly against SQL database records to ensure zero reporting drift.
6. **Deployment:** Published to Power BI Service with automated scheduled refreshes and role-based access.

---

## 📁 Repository Structure

```text
├── chapter-11-bi360-10-compressed.pdf   # Complete project documentation and slide deck
├── README.md                            # Project overview and documentation
└── reports/                             # Power BI report files (.pbix)
