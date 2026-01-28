# Powerbi-financial-dashboard

## Overview
Built an interactive Power BI dashboard using Microsoft’s **Financials** sample data to analyze sales and profitability.  
This project demonstrates **data modeling (star schema)**, **Power Query transformations**, and **DAX measures**.

---

## What I Built
-  Interactive dashboard with KPIs and trends
-  Star schema model:
  - **FactFinancials** (fact table)
  - **DimProduct** (dimension table)
  - Relationship: **DimProduct (1) → FactFinancials (*)** on `Product ID`
-  Core DAX measures for business reporting

---

## Key DAX Measures
- **Total Sales**
- **Total Profit**
- **Profit Margin %**

---

## Screenshots

### Dashboard
![Dashboard](screenshots/01-dashboard.png)
![Dashboard](screenshots/02-Filter on this page-dashboard.png)

### Star Schema (Model View)
![Star Schema](screenshots/03-model-star-schema.png)

### DAX Measures
![DAX Measures](screenshots/04-DAX-measures.png)

### Power Query Steps (ETL)
![Power Query](screenshots/05-power-query-FactFinancials.png)
### Power Query Steps (ETL)
![Power Query](screenshots/06-power-query-DimProduct.png)
---

## Skills Demonstrated
- Power BI Desktop (new UI)
- Power Query (merge, reference, expand, clean modeling workflow)
- Data Modeling (Star Schema, 1:* relationships)
- DAX (measures for KPIs)
- Dashboard building (charts, slicers, formatting)

---

## How to Use
1. Download `PowerBI_Financial_Dashboard.pbix`
2. Open in **Power BI Desktop**
3. Explore filters/slicers to interact with the report

---

## Notes
This project uses Microsoft’s built-in **Financials sample dataset** for learning and demonstration.
