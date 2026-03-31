# 📊 Sales Performance Dashboard: Superstore

This project features a comprehensive Business Intelligence solution developed in **Power BI**, focusing on profitability, logistics, and temporal performance using the global Superstore dataset. 

The project follows a full data pipeline: from raw data extraction and **Excel pre-processing** to advanced data modeling (Star Schema) and interactive UI/UX design.

---

## 🛠️ Data Pipeline & Technical Competencies

### 1. Data Pre-processing (Microsoft Excel)
Before importing into Power BI, a rigorous data cleaning and preparation stage was conducted in Excel:
* **Data Cleaning:** Identification and removal of duplicates and inconsistent records.
* **Standardization:** Formatting of dates, currencies, and geographical fields to ensure source integrity.
* **Data Enrichment:** Creation of helper columns to facilitate complex joins during the ETL phase.

### 2. ETL & Modeling (Power Query & Power BI)
* **Power Query:** Built a robust Star Schema consisting of a Fact table (`fSales`) and Dimensions (`dCustomers`, `dProducts`, `dGeography`).
* **Data Modeling:** Implementation of a **Star Schema** and a custom **dCalendar** table for advanced time intelligence.
* **Advanced DAX:** Developed complex measures using `CALCULATE`, `SAMEPERIODLASTYEAR`, `ALL`, and `DIVIDE` to calculate Margin %, Average Ticket, and YoY Growth.

### 3. UI/UX Design 
* **Smart Interactivity:** Conditional formatting (color-coded by profit), Top 10 rankings, and a dedicated **Reset Button** for seamless navigation.

---

## 🚀 Key Business Insights
* **Temporal Performance (YoY):** Comparison between Current Year vs. Last Year revenue to identify growth trends.
* **Regional Profitability:** Mapping high-volume states with low or negative profit margins.
* **Logistics Efficiency:** Analyzing the impact of shipping modes on delivery times and operational costs.

---

## 📈 Dashboard Preview
![Dashboard Screenshot](https://github.com/sheldoon/Sales-Performance-Dashboard-Superstore/blob/main/image/main_dashboard_page-0001.jpg)

---
