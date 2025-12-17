# Enterprise Sales & Customer Intelligence Dashboard 📊

## Project Overview 📌

The **Enterprise Sales & Customer Intelligence Dashboard** is an end-to-end data analytics project designed to help a multi-channel retail organization analyze **sales performance, customer behavior, and regional growth** using **SQL and Power BI**.

This project transforms raw transactional data into a **structured analytics data warehouse**, performs **business-driven SQL analysis**, and delivers **interactive executive dashboards** to support data-driven decision-making. The overall design closely mirrors real-world enterprise analytics workflows used by data analysts in large organizations.

---

## Business Problem 🏢

Retail businesses operate across multiple channels such as websites, mobile applications, and physical stores, generating large volumes of transactional data. However, this data is often siloed and lacks a unified analytical structure.

As a result, business leaders struggle to gain clear visibility into:
- Revenue trends and growth patterns  
- Product and category performance  
- Customer retention and lifetime value  
- Regional and channel-wise performance  

This project addresses these challenges by creating a **single source of truth** for sales analytics and converting raw data into actionable business insights.

---

## Project Objectives 🎯

The key objectives of this project are to centralize multi-channel sales data into a unified analytics database, design an optimized **star-schema data model**, perform in-depth SQL-based business analysis, and build executive-ready dashboards using Power BI. The project also focuses on delivering insights that support strategic business decisions.

---

## Data Model Architecture 🧱

The analytics system is designed using a **Star Schema**, a standard approach used in enterprise data warehouses for efficient analytical querying.

### Fact Table
- `fact_sales` – Stores transactional sales data including revenue, quantity, channel, and order date

### Dimension Tables
- `dim_customer` – Customer demographic and signup information  
- `dim_product` – Product and category attributes  
- `dim_location` – City and regional details  
- `dim_time` – Date, month, quarter, and year attributes  

This structure improves query performance and supports scalable business analysis.

---

## Business Analysis & Key Insights 🔍

The project answers key business questions across multiple domains. Revenue analysis focuses on monthly and quarterly trends, channel-wise performance, and growth metrics such as MoM and YoY. Product analysis evaluates top and bottom performers, category-level contribution, and price versus volume dynamics. Customer analysis covers new versus returning customers, repeat purchase behavior, and customer lifetime value. Regional analysis highlights city and region-level performance to identify high-growth and underperforming markets.

---

## Dashboards & Visualization 📊

The insights generated from SQL analysis are visualized using interactive Power BI dashboards designed for different stakeholders.

- **Executive KPI Dashboard** presenting revenue, growth, average order value, and top products  
- **Sales & Product Analysis Dashboard** showing trends, category performance, and channel comparison  
- **Customer & Regional Insights Dashboard** highlighting retention, CLV, and geographic performance  

These dashboards enable business users to explore data through filters, drill-downs, and interactive visuals.

---

## Tools & Technologies 🛠️

- **SQL (MySQL / PostgreSQL)** – Data modeling and business analysis  
- **Power BI** – Interactive dashboards and data visualization  
- **Microsoft Excel** – Data validation and preprocessing  
- **Python (Optional)** – Synthetic data generation  

---

## Project Structure 📁

Enterprise-Sales-Customer-Intelligence/
│
├── data/ # Raw and processed datasets
├── sql/ # SQL scripts for analysis
│ └── business_analysis.sql
├── dashboards/ # Power BI dashboards
│ └── sales_dashboard.pbix
├── insights/ # Business insights and reports
│ └── business_report.pdf
└── README.md
---

## Key Outcomes 📈

This project demonstrates the development of an enterprise-grade sales analytics solution built on a large transactional dataset. It showcases strong data modeling practices, advanced SQL-based analysis, and executive-level dashboarding to deliver actionable business insights.

---

## Business Impact 🚀

The solution enables organizations to monitor sales performance in near real time, identify high-value products and customers, optimize regional and channel strategies, and make confident data-driven decisions using reliable analytics.

---

## Future Enhancements 🔮

Future improvements may include automated data ingestion pipelines, advanced customer segmentation, sales forecasting, and role-based dashboard access for different stakeholders.

---

## Author 👤

**Priyansh Singh**  
Aspiring Data Analyst  
SQL | Power BI | Business Analytics
