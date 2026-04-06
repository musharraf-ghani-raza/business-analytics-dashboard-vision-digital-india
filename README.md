# 📊 Business Analytics Dashboard Project

<div align="center">

![Project Banner](https://img.shields.io/badge/Project-Business_Analytics_Dashboard-1A1A2E?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Tools](https://img.shields.io/badge/Tools-Excel_%7C_SQL_%7C_Power_BI-F2C811?style=for-the-badge)

</div>

---

## 📋 Project Overview

| Field | Details |
|---|---|
| **Organization** | Vision Digital India |
| **Role** | Business Analyst Intern |
| **Period** | January 2025 – March 2025 |
| **Location** | Bengaluru, India |
| **Tools Used** | Microsoft Excel (Advanced), SQL, Power BI |

---

## 🎯 Project Objective

Built end-to-end business analytics dashboards and MIS reports to monitor Service Level Agreement (SLA) performance, track Key Performance Indicators (KPIs), and enable data-driven decision-making for internal stakeholders. The project covered data collection, cleaning, analysis, dashboard development, and report generation across 6 service categories.

---

## 📁 Repository Structure

```
project-1-business-analytics-dashboard/
│
├── 📊 data/
│   ├── raw_data.csv                    ← Raw business performance dataset (72 rows)
│   └── data_dictionary.md              ← Column definitions and data guide
│
├── 📈 VisionDigitalIndia_MIS_Dashboard_2025.xlsx   ← Main Excel Dashboard File
│
├── 🖼️ screenshots/
│   ├── excel_mis_report.png            ← MIS Monthly Report screenshot
│   ├── excel_sla_dashboard.png         ← SLA Performance Dashboard screenshot
│   ├── excel_pivot_summary.png         ← Pivot Summary with charts screenshot
│   ├── powerbi_kpi_overview.png        ← Power BI KPI cards screenshot
│   ├── powerbi_sla_trend.png           ← Power BI SLA trend line chart
│   └── powerbi_service_breakdown.png   ← Power BI service breakdown charts
│
├── 📄 reports/
│   └── MIS_Project_Summary_Report.md   ← Detailed project methodology report
│
└── README.md                           ← This file
```

---

## 📊 Excel Dashboard — Sheets Overview

### Sheet 1: Raw Data
- **72 rows** of monthly business performance data
- Covers **6 service categories** × **12 months**
- Fields: Month, Service, Tickets Raised, Tickets Resolved, SLA Breaches, Avg Resolution (hrs), CSAT Score (%), Revenue (INR)

### Sheet 2: MIS Monthly Report
- **6 KPI summary cards** — Total Tickets, Resolution Rate, SLA Compliance %, CSAT, Revenue, Reports Issued
- **Monthly performance table** with SLA status (ON TRACK / REVIEW) using conditional color coding
- **Service-wise breakdown** with performance badges (HIGH / MEDIUM)
- All values driven by **Excel formulas** (AVERAGE, SUM, cell references)

### Sheet 3: SLA Dashboard
- **Week-by-week SLA compliance tracker** (12 weeks: Jan–Mar 2025)
- **Service-level SLA table** comparing Target % vs Jan/Feb/Mar Actuals
- **Trend indicators** (Improving / Stable / Excellent)
- **Line chart** — Weekly SLA Compliance % Trend

### Sheet 4: Client Query Log
- **22 client query records** with Query ID, Date, Client Name, Type, Priority, Resolution Time, Status
- **Color-coded priority badges** (HIGH = Red, MEDIUM = Amber, LOW = Green)
- All queries marked as **RESOLVED** with resolution time logged

### Sheet 5: Pivot Summary
- **Revenue pivot table** — Service vs Month (Jan/Feb/Mar 2025)
- **Grand Total row** for all services
- **Clustered bar chart** — Revenue by Service across 3 months

---

## 📈 Power BI Dashboard — Visuals Overview

The Power BI dashboard provides an interactive view of the same dataset with:

| Visual | Type | Insight |
|---|---|---|
| KPI Cards (6) | Card | Tickets, Resolution Rate, SLA %, CSAT, Revenue, Reports |
| Weekly SLA Trend | Line Chart | 12-week SLA compliance and CSAT trend |
| Ticket Status Split | Donut Chart | Resolved / In Progress / Escalated / Pending |
| Revenue by Service | Clustered Bar | Jan–Mar revenue across 6 services |
| CSAT by Service | Horizontal Bar | Service-level satisfaction scores |
| Monthly Volume | Stacked Bar | Resolved, Breaches, Pending per month |
| SLA Performance Table | Table Visual | Detailed service × month SLA compliance |

---

## 📉 Key Results & Outcomes

| Metric | Result |
|---|---|
| MIS Reports Generated | 15+ (Weekly and Monthly) |
| Client Queries Resolved | 20+ financial discrepancy queries |
| Reporting Effort Reduction | ~30% via dashboard automation |
| SLA Compliance (Mar 2025) | 93.5% average across services |
| Average CSAT Score | 87.6% |
| Total Revenue Tracked | ₹57.7 Lakhs (Jan–Mar 2025) |
| Data Inconsistencies Identified | 5+ anomalies flagged and resolved |

---

## 🛠️ Skills Demonstrated

- ✅ Advanced Excel — Pivot Tables, VLOOKUP, HLOOKUP, Conditional Formatting, Charts
- ✅ MIS Report Generation — Weekly and Monthly structured reporting
- ✅ SLA Monitoring and KPI Tracking
- ✅ Power BI — Interactive dashboards, slicers, multiple visual types
- ✅ SQL — Data querying and aggregation
- ✅ Data Cleaning and Anomaly Detection
- ✅ Stakeholder Communication — Report delivery and query resolution

---

## 🚀 How to Use This Project

### Excel Dashboard
1. Download `VisionDigitalIndia_MIS_Dashboard_2025.xlsx`
2. Open in **Microsoft Excel 2016 or later**
3. Navigate between sheets using the sheet tabs at the bottom
4. All KPI values auto-calculate from the Raw Data sheet

### Power BI Dashboard
1. Open `screenshots/` folder to view all Power BI visuals
2. The full interactive dashboard HTML is available at [Power BI Dashboard](../project-1-business-analytics-dashboard/VisionDigitalIndia_PowerBI_Dashboard.html)

---

## 👤 Author

**Musharraf Ghani Raza**
- 📧 musharrafghani@gmail.com
- 💼 [LinkedIn](https://www.linkedin.com/in/musharraf-ghani-raza-b862a3250)
- 📍 Bengaluru, India

---

*This project was completed as part of my Business Analyst Internship at Vision Digital India (January–March 2025).*
