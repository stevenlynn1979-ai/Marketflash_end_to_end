# Marketflash: End-to-End Relational Database & Tableau Analytics

An end-to-end data analytics project showcasing relational database design, data pipeline orchestration, and executive-level business intelligence dashboards. This project translates raw operational data into interactive, actionable insights for stakeholders.

---

## 📌 Project Overview
Marketflash is designed to bridge the gap between raw data storage and strategic decision-making. By structuring disorganized data into a robust relational database and building intuitive visual interfaces, this project enables stakeholders to monitor key business performance indicators (KPIs) in real time.

---

## 🛠️ Tech Stack & Architecture
* **Database Design:** [e.g., PostgreSQL / SQLite / BigQuery] for relational database modeling, schema design, and analytical queries.
* **Data Prep & ETL:** [e.g., Python Pandas / SQL / Google Sheets] for data cleaning, handling null values, and parsing attributes.
* **Business Intelligence:** **Tableau** for creating interactive executive dashboards.
* **Version Control:** Git & GitHub.

---

## 📂 Repository Structure & Deliverables

This repository is fully populated with the core deliverables of the end-to-end pipeline:

* **`/database` or `/scripts`**: Contains the SQL DDL scripts used to create the tables, define primary/foreign keys, and model the relational schema.
* **`/data`**: Cleaned, structured datasets supporting the database and the Tableau visualizations.
* **`/dashboards`**: Packaged Tableau Workbook (`.twbx`) files showing the structural design behind the visualization.
* **`README.md`**: Project documentation and executive summary.

---

## 🗄️ Relational Database Design
To ensure data integrity and eliminate redundancy, the raw data was normalized into a relational schema. 

### Schema Highlights:
* **Primary Tables:** [e.g., Orders, Customers, Products, Branches]
* **Key Constraints:** Enforced strong referential integrity using primary and foreign key relationships to ensure robust data modeling.


---

## 📊 Tableau Dashboards
The final phase of the project delivers interactive, executive-level insights. 

👉 **[View the Interactive Tableau Public Dashboard](https://public.tableau.com/app/profile/steve.lynn6910/viz/MarketFlash_dashboard/Dashboard1)**

### Key Visualizations & Focus Areas:
1. **Executive Summary Dashboard:** High-level revenue, performance trends, and target tracking.
2. **Operational Efficiency:** Analysis of performance bottlenecks across different segments/locations.
3. **Customer Segmentation:** Breakdown of user cohorts to target high-value behaviors.

*To inspect the dashboard calculations and data sources locally, download the packaged workbook (`.twbx`) located in the `/dashboards` folder.*

---

## 🔑 Key Business Insights & Recommendations
* **Trend 1:** [E.g., High-performing product lines are consistently understocked in specific regions.]
* **Trend 2:** [E.g., Customer lifetime value (LTV) significantly increases when users cross a specific purchase threshold.]
* **Recommendation:** [E.g., Reallocate inventory to regional hubs based on predictive sales metrics.]


