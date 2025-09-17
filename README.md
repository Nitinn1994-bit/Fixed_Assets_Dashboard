# Fixed Assets – Power BI Dashboard

Executive-ready dashboards to track the fixed-asset lifecycle end-to-end: **beginning balances, acquisitions, depreciation, disposals, and net book value (NBV)** with drill-downs by **month, asset group, and location**.

---

## 🔎 Overview

- **KPIs:** Beginning Balance, **Acquisitions**, **Depreciation**, **Disposals**, **Net Book Value (NBV)**
- **Breakdowns:** Month, Asset Group/Category, Location (with fast filters)
- **Goal:** Clear visibility into how asset value changes over time to support informed asset management decisions

---

## 📊 Pages

### Fixed Assets Dashboard
The Fixed Assets Dashboard delivers key KPIs at a glance, helping you monitor beginning amounts, acquisitions, depreciation, disposals and net book value. It highlights changes over time, enabling quick identification of trends and shifts in asset value throughout the lifecycle.

Interactive visuals allow you to explore each KPI in detail, with breakdowns by month, asset group, and location. The dashboard provides a clear, flexible view to support informed asset management decisions.

---

## 🗂 Data Model (high level)

- **Fact tables:** Asset movements (additions/disposals), monthly depreciation
- **Dimensions:** Date, Asset, Category/Group, Location, Status  
Star schema optimized for time-series analysis and categorical slicing.

---

## 🛠️ Tech & Skills

- **Power BI** (DAX measures, Power Query)
- **Data modeling** (star schema, date intelligence)
- **Reporting design** (clean KPI cards, trend visuals, drillable tables)



---

## 📄 License
MIT License

## 👤 Contact
Nitin N — [nitinn9620@gmail.com](mailto:nitinn9620@gmail.com)
