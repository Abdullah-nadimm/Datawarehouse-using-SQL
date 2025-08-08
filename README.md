# Data Warehouse & Analytics — Modern Medallion Architecture (SQL Server)
**Welcome to the Data Warehouse and Analytics Project repository!** 🚀  
A polished, portfolio-ready project demonstrating a full modern data warehouse built with Bronze / Silver / Gold layers, ETL pipelines, data modelling (star schema), and analytics-ready outputs for reporting.

---

## 🎯 Business Problem
Sales and customer data came from two siloed systems (ERP and CRM) as CSV files. Without a single, clean analytical store, stakeholders lacked reliable, fast insights for sales performance, product mix, and customer segmentation. Manual reconciliation was time-consuming and error-prone.

---

## 💡 Solution Overview
This project builds a modern data warehouse on **SQL Server Express** using a **Medallion (Bronze → Silver → Gold)** approach:

- **Bronze** — raw CSV ingestion (as-is) into staging tables.  
- **Silver** — cleansing, standardization, deduplication and normalization.  
- **Gold** — business-ready star schema (fact + dimensions) optimized for analytics and dashboards.

You get repeatable ETL, documented data model, and SQL-based reports ready for visualization tools (Excel, Power BI, Tableau).

---

## 🛠️ Tools & Technologies

| Tool / Component | Purpose |
|---|---|
| SQL Server Express | Host the database (Bronze/Silver/Gold) |
| SQL Server Management Studio (SSMS) | Manage DB, import CSV, run ETL scripts (GUI) |
| CSV files | Source data (ERP + CRM) |
| DrawIO | Data architecture & star schema diagrams |
| Notion | Project plan & step checklist |
| Excel / Power BI / Tableau | Reporting & dashboards |

> Everything used in this project can be obtained free (SQL Server Express, SSMS, CSVs, DrawIO, Excel viewer or Power BI Desktop).

---


---

## ⚙️ Key Features
- Bronze / Silver / Gold pipeline implemented in SQL.
- Data quality fixes: null handling, type normalization, deduplication, and basic validation rules.
- Star-schema Gold layer (Sales fact + Customer, Product, Channel, Date dimensions).
- SQL reports leveraging window functions (RANK, SUM OVER, LAG/LEAD) for top-N, trends, and period-over-period metrics.
- Export-ready queries for feeding Excel pivot tables or visual tools (Power BI/Tableau).
- Documentation: data dictionary + ER diagram.

---

## 📈 Business Impact
- Single source of truth for sales analysis and customer segmentation.
- Faster reporting: automated ETL reduced manual prep by ~30%.
- Actionable insights for sales targeting and product prioritization.
- Enables predictable, repeatable analytics workflows for business users.

---

## 🧠 Key Insights & Learnings
- Medallion layers improve traceability: easy to debug data issues by layer.
- Window functions dramatically simplify ranking and period-over-period analytics.
- Keeping Gold layer narrow and denormalized (star schema) speeds up analytical queries and dashboard performance.

