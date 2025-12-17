# 📊 Enterprise Sales & Customer Intelligence Dashboard

## 📌 Project Overview

This project is an end-to-end **enterprise-grade data analytics solution** designed to help a multi-channel retail business analyze its **sales performance, customer behavior, and regional growth** using **SQL and Power BI**.

The system transforms raw transactional sales data into a **structured analytics data warehouse**, performs **business-driven SQL analysis**, and delivers **interactive executive dashboards** to support data-driven decision-making.

---

## 🏢 Business Problem

Modern businesses generate large volumes of sales data across multiple platforms such as:
- Website
- Mobile application
- Offline retail stores

However, leadership teams often lack clear visibility into:
- Revenue trends and growth patterns
- Product and category performance
- Customer retention and lifetime value
- Regional and channel-wise performance

This project addresses these challenges by creating a **single source of truth** for sales analytics and transforming raw data into actionable insights.

---

## 🎯 Project Objectives

- Centralize multi-channel sales data into a unified analytics database
- Design an optimized **star-schema data model** for fast analytical queries
- Perform in-depth business analysis using SQL
- Build executive-ready dashboards using Power BI
- Deliver meaningful insights and strategic recommendations

---

## 🧱 Data Model Architecture

The project follows a **Star Schema** data modeling approach commonly used in enterprise data warehouses.

### ⭐ Fact Table
- `fact_sales` – Stores transactional sales data (revenue, quantity, channel, date)

### 🌐 Dimension Tables
- `dim_customer` – Customer demographics and signup details  
- `dim_product` – Product and category information  
- `dim_location` – City and region data  
- `dim_time` – Date, month, quarter, and year attributes  

This structure improves query performance and enables scalable analytics.

---

## 🔍 Key Business Questions Answered

### Revenue & Growth
- Monthly and quarterly revenue trends
- Month-over-Month (MoM) and Year-over-Year (YoY) growth
- Sales performance by channel

### Product Analytics
- Top and bottom-performing products
- Product and category revenue contribution
- Price vs volume analysis

### Customer Analytics
- New vs returning customers
- Repeat purchase behavior
- Customer Lifetime Value (CLV)

### Regional Insights
- City and region-wise revenue performance
- Identification of high-growth and underperforming regions

---

## 📊 Dashboards

The project includes **interactive Power BI dashboards** designed for different stakeholders:

### 📈 Executive KPI Dashboard
- Total Revenue
- Growth Percentage
- Average Order Value (AOV)
- Top Products

### 📊 Sales & Product Analysis Dashboard
- Product and category performance
- Revenue trends
- Channel-wise comparison

### 📍 Customer & Regional Insights Dashboard
- Repeat customer rate
- Customer Lifetime Value (CLV)
- Geographic performance analysis

---

## 🛠️ Tools & Technologies

- **SQL (MySQL / PostgreSQL)** – Data modeling and business analysis  
- **Power BI** – Data visualization and dashboarding  
- **Microsoft Excel** – Data validation and preprocessing  
- **Python (Optional)** – Synthetic data generation  

---

## 📁 Project Structure

Enterprise-Sales-Customer-Intelligence/
│
├── data/ # Raw and processed datasets
├── sql/ # Business analysis SQL queries
│ └── business_analysis.sql
├── dashboards/ # Power BI dashboards
│ └── sales_dashboard.pbix
├── insights/ # Business insights and recommendations
│ └── business_report.pdf
└── README.md

---

## 📈 Key Outcomes

- Built an enterprise-grade sales analytics system on 200k+ transaction records
- Designed a scalable star-schema data warehouse
- Delivered executive-level dashboards for KPI tracking
- Generated actionable insights to support revenue growth and customer retention

---

## 🚀 Business Impact

This analytics solution enables business leaders to:
- Monitor revenue and growth trends in real time
- Identify top-performing products and customers
- Improve customer retention strategies
- Optimize regional and channel performance
- Make confident, data-driven decisions

---

## 📌 Future Enhancements

- Automated data ingestion pipelines
- Advanced customer segmentation
- Forecasting and trend analysis
- Role-based dashboard access

---

## 👤 Author

**Priyansh Singh**  
Aspiring Data Analyst | SQL | Power BI | Business Analytics
