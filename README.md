# 🚚 Olist E-Commerce Data Analysis & Business Dashboard

An end-to-end business intelligence and data analytics project analyzing the **Olist Brazilian E-Commerce Dataset**. This project transforms raw transaction, logistics, and customer data into interactive, actionable dashboards to drive strategic decisions in retail operations, customer retention, and supply chain efficiency.

---

## 📌 Executive Summary

Olist is a major Brazilian marketplace platform connecting small businesses to larger retail channels. This project focuses on analyzing **over 100,000 orders** from 2016 to 2018 to uncover insights across three critical business dimensions:

1. **Financial Performance:** Revenue trends, average order value (AOV), and payment method distribution.
2. **Customer Analytics & Churn:** Customer lifetime value, repeat purchase behavior, and geographic distribution.
3. **Supply Chain & Logistics:** Delivery performance, freight costs, seller delivery delays, and carrier lead times.

---

## 📸 Dashboard Screenshots

| Financial Performance | Customer Analytics & Churn |
| :---: | :---: |
| ![Financial Dashboard](https://github.com/naima-hussein4/Olist-Analysis/blob/main/Images/screenshot%201.png) | ![Customer Analysis Dashboard](https://github.com/naima-hussein4/Olist-Analysis/blob/main/Images/screenshot%202.png) |



## 📊 Key Dashboards & Features

### 💵 1. Financial Performance Dashboard
* **Revenue & Order Growth:** Historical sales volume and revenue tracking month-over-month.
* **Payment Insights:** Breakdown of transactions by payment type (Credit Card, Boleto, Voucher, Debit Card) and installment patterns.
* **Category Analysis:** Top-performing product categories by total sales and profit margins.

### 👥 2. Customer Analytics & Churn Dashboard
* **Customer Segmentation:** Analysis of unique vs. recurring buyers across Brazilian states.
* **Churn & Retention Rates:** Tracking customer drop-off points and re-order intervals.
* **Geographic Heatmap:** Spatial distribution of customers and average order values by region.

### 📦 3. Supply Chain & Operational Efficiency Dashboard
* **Delivery Performance:** On-time delivery rate vs. estimated delivery date comparisons.
* **Logistics Bottlenecks:** Analysis of carrier shipping lead times, freight costs, and order processing times.
* **Seller Scorecards:** Monitoring seller fulfillment metrics and customer review scores relative to delivery delays.

---

## 🛠️ Tech Stack & Tools

* **Data Storage & Querying:** SQL Server / SSMS (Data extraction, transformation, aggregation)
* **Data Preparation & Cleaning:** Microsoft Excel / Power Query
* **Data Visualization & Analytics:** Power BI (DAX metrics, interactive dashboards, dynamic slicers)
* **Design & Layout:** Custom UI layout with responsive visual grid

---

## 📁 Repository Structure

```text
├── data/
│   ├── raw/               # Original Olist CSV datasets
│   └── processed/         # Cleaned and transformed data tables
├── sql/
│   ├── schema.sql         # Database schema and table definitions
│   └── queries.sql        # SQL queries for KPIs, aggregations, and data checks
├── powerbi/
│   └── Olist_Dashboard.pbix  # Interactive Power BI Report
├── assets/                # Dashboard screenshots and diagrams
└── README.md              # Project documentation
