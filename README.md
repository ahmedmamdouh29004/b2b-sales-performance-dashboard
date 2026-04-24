# 📊 B2B Sales & Distribution Performance Analytics Dashboard

### Power BI · DAX · Star Schema · Data Modeling  

> DEPI Graduation Project | Data Analytics Track (Microsoft Power BI Specialist)  
> Supervised by Eng. Amr Suliman

---

## 🔍 Project Overview

Alex Agency Analytics is an end-to-end **business intelligence solution** built in Power BI that transforms raw B2B transactional data into a centralized, interactive analytics platform. The project covers the full data lifecycle — from ingestion and cleaning through star schema modeling and DAX measure development — culminating in **7 production-ready dashboard pages** that serve executive, operational, and analytical audiences.

**Dataset:** ~1,000 order transactions across 89 customers, 230 products, 9 employees, and 21 countries.

---

## 🚀 Live Power BI Dashboard

👉 **Explore the interactive dashboard (fully dynamic & filterable):**  
🔗 [Launch Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiYTE3NzZkNWYtMmY5MC00M2U3LTlhZmMtZjZmYjAyMDQwOGY0IiwidCI6ImVhZjYyNGM4LWEwYzQtNDE5NS04N2QyLTQ0M2U1ZDc1MTZjZCIsImMiOjh9&pageName=330d161c4eca3e82ae89)

---

## 📸 Dashboard Preview

👉 **View Dashboard Preview (PDF):**  
[b2b-sales-dashboard-preview](docs/b2b-sales-dashboard-walkthrough.pdf)

| Landing Page | Sales Trends & Seasonality | Shipping & Delivery |
|--------------|----------------------------|----------------------|
| ![Landing](dashboard_screenshots/00_landing_page.jpeg) | ![Sales Trends](dashboard_screenshots/01_sales_trends_seasonality.jpeg) | ![Shipping](dashboard_screenshots/04_shipping_delivery_insights.jpeg) |

> These snapshots represent key analytical views from the Power BI dashboard, showcasing executive overview, sales performance trends, and logistics efficiency.

---

## 🚀 Top Business Insights

| # | Insight | Impact |
|---|---------|--------|
| 1 | **60.31% YoY sales growth** with $475K total revenue | Strong overall business momentum |
| 2 | **Q1 dominates** at ~$200K — nearly 2× any other quarter | Clear need for Q2–Q4 retention strategy |
| 3 | **81.68% international sales** across 21 countries | High global exposure; currency/logistics risk |
| 4 | **USA ($87K) & Germany ($78K)** drive 35%+ of revenue | EU + NA = core expansion focus zone |
| 5 | **Clothes category ($186K)** = 39% of all sales; Shirts alone: $108K | Strong category concentration |
| 6 | **91.86% customer retention rate** with avg 5.39 orders/customer | Loyal base — acquisition is the gap |
| 7 | **Top employee (Margaret Peacock) = 19.35% of total revenue** | Star performer dependency risk |
| 8 | **93% on-time delivery rate** across 10 shipping partners | Logistics performing well overall |
| 9 | **Cunewalde city: $42K** — outperforms every other city by 45% | Micro-market loyalty hotspot |
| 10 | **Africa & Asia-Pacific = 0 orders** despite global reach | Largest untapped growth opportunity |

---

## 📁 Repository Structure

```
alex-agency-analytics/
│
├── 📊 Alex_Agency_Analytics.pbix       # Main Power BI dashboard file
│
├── 📂 data/
│   └── Data.xlsx                       # Source dataset (fact + dimensions)
│
├── 📂 docs/
│   ├── b2b-sales-performance-analysis-report.pdf   # Full technical & business documentation
│   └── b2b-sales-dashboard-walkthrough.pdf     # Dashboard screenshots & visual walkthrough
│
screenshots/
├── 00_landing_overview.jpeg
├── 01_sales_trends_seasonality.jpeg
├── 02_customer_insights_segmentation.jpeg
├── 03_product_performance_analysis.jpeg
├── 04_shipping_delivery_insights.jpeg
├── 05_geographic_sales_distribution.jpeg
├── 06_employee_sales_team_performance.jpeg
├── 07_deep_dive_decomposition_tree.jpeg
└── 08_deep_dive_transaction_table.jpeg
│
└── README.md
```

---

## 🏗️ Technical Architecture

```
Raw Data (Excel)
     │
     ▼
Power Query (ETL)
  ├── Null handling & deduplication
  ├── Data type standardization
  └── Calculated columns (Profit, Full Name, Date Parts)
     │
     ▼
Star Schema Model
  ├── FACT: FactOrder (transactions)
  └── DIMS: DimCustomers · DimProducts · DimEmployees
            DimShippers · DimTerritory · DimDate
     │
     ▼
DAX Measures (9 Categories)
  └── Time · Sales · Customers · Products
      Performance · Geo · Employees · Shipping · KPIs
     │
     ▼
7 Interactive Dashboard Pages
```

---

## 📈 Dashboard Pages

| Page | Key KPIs |
|------|----------|
| **Sales Trends & Seasonality** | Total Sales · YoY Growth · Monthly Seasonality Index |
| **Customer Insights** | Retention Rate · CLV Scatter · Top 5 Companies |
| **Product Performance** | Category Sales · Top 10 Products · Quantity Trend |
| **Shipping & Delivery** | On-Time Rate · Avg Delivery Days · Freight by Carrier |
| **Geographical Analysis** | Sales by Country · AOV by City · Market Map |
| **Employee Performance** | Rankings · Target KPI · Orders by Employee |
| **Deep Dive Analysis** | Drill-through decomposition tree · Full order table |

---

## 💼 Business Impact

- **Faster decisions:** Replaced manual reporting with real-time interactive dashboards  
- **Revenue clarity:** Pinpointed that 2 countries (USA + Germany) drive 35% of revenue  
- **Operational efficiency:** Identified top/bottom shipping carriers by speed and cost  
- **Growth roadmap:** Quantified untapped markets (Asia-Pacific, Africa) with zero current penetration  
- **Talent visibility:** Exposed performance gaps between top and bottom employees

---

## 👥 Team & Role

This project was developed as part of the **DEPI (Digital Egypt Pioneers Initiative) – Data Analytics Track (Microsoft Power BI Specialist)**.


As **Team Leader**, I was responsible for end-to-end project leadership and cross-functional oversight across the analytics lifecycle:

- Defined project scope, structure, and execution plan to ensure alignment between business requirements and analytical outputs  
- Supervised the data modeling process (Star Schema), contributing to issue resolution and ensuring model integrity and scalability  
- Developed and validated key DAX measures to ensure accuracy, consistency, and business relevance of KPIs  
- Designed and optimized dashboard page structure and visual storytelling flow to enhance usability and decision-making clarity  
- Conducted end-to-end review of all deliverables to ensure data accuracy, consistency, and alignment with business objectives  
- Ensured final production readiness of the dashboard, including quality assurance and performance validation before deliveryy

### Team Members

| Name |
|------|
| Saeed Mohamed Saeed |
| Jasser Ashraf |
| Ahmed Mamdouh Khaled (Team Lead) |
| Omar Mohamed Abdel-Hafez |
| Mohamed Salah El-Din |
| Youssef Mohamed Marzouk |

**Supervisor:** Eng. Amr Suliman

---

## 🛠️ Tools & Technologies

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=flat&logo=microsoft&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-742774?style=flat&logo=microsoft&logoColor=white)

---

*For full technical documentation, DAX measures, and detailed business analysis — see [`docs/b2b-sales-performance-analysis-report.pdf`](docs/b2b-sales-performance-analysis-report.pdf)*
