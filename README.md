# 🏎️ Strategic Financial Dashboard: Ferrari Case Study (2016-2024)

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)


## 📖 Executive Summary
This project involves the development of an end-to-end Business Intelligence solution analyzing Ferrari's financial performance from 2016 to 2024. 

Designed for **C-Suite strategic planning**, this dashboard consolidates complex financial statements into actionable KPIs, allowing stakeholders to monitor operational efficiency, profitability, and growth trends at a glance.

## 💼 Business Scenario & Objectives
**The Challenge:**
[cite_start]Financial data was fragmented across multiple static reports, making it difficult for executives to visualize long-term trends in **EBITDA margins** and **Inventory Turnover**[cite: 8].

**The Solution:**
I acted as a Data Analyst to build a centralized dashboard that serves as a "single source of truth." The goal was to enable data-driven decision-making regarding cost structures and revenue streams.

**Key Objectives:**
* [cite_start]**Consolidate Data:** Integrate 8 years of financial data (2016-2024) into a unified data model[cite: 8].
* [cite_start]**Visualize Efficiency:** Track Inventory Turnover and operational metrics to identify supply chain bottlenecks[cite: 8].
* [cite_start]**Profitability Analysis:** Deconstruct profit margins using P&L Waterfall charts[cite: 8].

## 📊 Dashboard Previews

<img width="1546" height="876" alt="image" src="https://github.com/user-attachments/assets/0f5321ff-d169-47df-a520-1766366a57d1" />
<img width="1583" height="874" alt="image" src="https://github.com/user-attachments/assets/bfd64550-541a-4d0e-9d5d-3fe52dae5d43" />
<img width="1584" height="881" alt="image" src="https://github.com/user-attachments/assets/c2a09266-e22b-42d6-924e-1de524b92555" />
### Additional KPI:
<img width="1959" height="1302" alt="image" src="https://github.com/user-attachments/assets/43d65cc4-9257-424c-ac06-43f1a8b2fd18" />


### Key Views:
1.  **Executive Overview:** High-level KPIs (Revenue, Net Debt, EBITDA) with Year-over-Year (YoY) variance.
2.  **P&L Waterfall:** A bridge analysis showing exactly how Revenue flows down to Net Income, highlighting major expense drivers.
3.  **Operational Efficiency:** Analysis of working capital, specifically focusing on Inventory Turnover ratios.

## 🛠️ Technical Implementation
This project demonstrates proficiency in the full BI lifecycle:

* **ETL (Extract, Transform, Load):** Used **Power Query** to clean raw financial datasets, handle missing values, and unpivot columns for analysis.
* **Data Modeling:** Built a robust **Star Schema** to ensure efficient query performance and accurate filtering.
* **DAX (Data Analysis Expressions):** * Created complex measures for *Time Intelligence* (YoY Growth, YTD calculations).
    * Implemented dynamic titles and conditional formatting to enhance User Experience (UX).

## 💡 Key Insights
* *Example Insight:* Identified a X% increase in EBITDA margins in 2022 despite rising operational costs.
* *Example Insight:* Inventory turnover stabilized in 2023, suggesting improved supply chain management.

## 📂 Repository Structure
```text
├── data/               # Raw data files (anonymized/public)
├── Ferrari_Report.pbix # The Power BI source file
└── README.md           # Project documentation
