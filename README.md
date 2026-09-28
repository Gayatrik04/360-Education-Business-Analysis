# 360° Education Business Analysis Dashboard

## Project Overview
The 360° Education Business Analysis project is an end-to-end analytics solution designed to evaluate and optimize the operational, financial, and placement performance of a multi-branch professional training institute.

Spanning a 17-month period, this project consolidates key performance indicators (KPIs) across five geographic branches (Karve Nagar, Nagpur, Hadapsar, Pimpri, and Chinchwad) and five core technology domains (Data Science, Data Analytics, Java Full Stack, Python Full Stack, and Software Testing).

---

## Problem Statement
Despite robust top-line revenue ($66\text{M}$) and consistent student acquisition ($2\text{K}$ admissions):
* **Revenue Leakage:** 21.21% ($14\text{M}$) of total revenue remains uncollected, with 73.25% of the active student base carrying outstanding fee balances. 
* **Low Placement Conversion:**The institutional placement rate sits at 34.85%, despite over 6,000 placement calls being generated across partner networks.
* **Marketing Inefficiencies:**Lead conversion sits at 31.90% ($638$ converted out of $2\text{K}$ total leads), requiring ad budget re-allocation toward high-performing channels like LinkedIn, YouTube, and direct Walk-Ins.
* **Data Anomaly:**A sharp, unnatural metric drop-off occurs in May 2025 across admissions and revenues, indicating potential tracking cutoffs or seasonal exam disruptions.

---

## Project Objectives
* **Financial Optimization:** Improve collection efficiency from 79.45% toward >90% by establishing milestone-gated payment rules to recover $14\text{M}$ in pending receivables. 
* **Placement Acceleration:** Boost overall placement rates from 34.85% toward 50%+ by targeting the 414 candidates receiving $5+$ calls without converting through pre-screening and mock interview bootcamps.
* **Marketing ROI Maximization:** Raise lead conversion rates from 31.90% to 40% by dynamically prioritizing top-converting sources like LinkedIn ($123$ conversions) and YouTube ($105$ conversions).
* **Data Governance:**Streamline DAX measures and visualization funnels to ensure real-time reporting accuracy across executive views.
---

## Dashboard Architecture & Key Findings
The solution is divided into four distinct interactive Power BI pages:

### 1. Executive Overview
* **Focus:**High-level executive health tracking across overall revenue, total enrollments, and conversion performance.
* **Key Finding:**Data Analytics ($16\text{M}$ / $24.52\%$) and Data Science ($16\text{M}$ / $23.92\%$) drive nearly half ($48.44\%$) of total institutional revenue.
**[Executive Overview](Dashboard_screenshot/Executive_Overview.png)**

### 2. Sales & Admission Analysis
* **Focus:**Lead generation funnels, marketing acquisition channels, and branch-level lead conversion ratios. 
* **Key Finding:**LinkedIn is the single highest digital lead converter ($123$ conversions), followed closely by organic sources: Walk-Ins ($105$), YouTube ($105$), and Student Referrals ($104$). 
**[Sales & Admission Analysis](Dashboard_screenshot/sales_and_admission_analysis.png)**


### 3. Placement Analysis
* **Focus:**Student employment funnels, course-wise hiring performance, and recruitment company distributions. 
* **Key Finding:**Software Testing holds the highest course placement rate at 37.21% ($144$ placed). Top hiring partners include Wipro ($296$), Capgemini ($293$), Accenture ($292$), Tech Mahindra ($274$), Infosys ($268$), and Cognizant ($260$). 
**[Placement Analysis](Dashboard_screenshot/Placement_Analysis.png)**


### 4. Financial Analysis
* **Focus:**Monthly fee collection trends, cash flow breakdown by payment modes, and outstanding debt monitoring.
* **Key Finding:**73.25% of students have pending fee installments. Payment channels remain evenly distributed: Cash ($26.86\%$), Cards ($24.97\%$), Net Banking ($24.29\%$), and UPI ($23.89\%$).
**[Financial Analysis](Dashboard_screenshot/Financial_Analsis.png)**

---

## Future Improvements

* **Automated Fee Guardrails:** Integrate CRM/LMS to automatically pause course or placement cell access if fee milestones are missed.
* **AI-Powered Placement Prep:** Deploy automated resume-scanners and AI mock-interview tools to screen students before corporate scheduling.
* **Predictive Lead Scoring:** Implement a machine learning model to score leads, prioritizing high-intent inquiries from top channels.
* **Real-Time Data Pipelines:** Build automated, real-time ETL pipelines to eliminate tracking lag and artificial data drops.
* **Risk-Mitigated Payments:** Partner with external NBFCs to offer formal EMI options or Income Share Agreements (ISAs).

---

## Tech Stack & Tools Used
* **Data Visualization & Business Intelligence:** Power BI (Desktop & Service)
* **Data Modeling & Analytics:**DAX (Data Analysis Expressions), Star Schema Modeling, Power Query (ETL)
* **Documentation & Framework:**Markdown, GitHub

---

## Repository Structure
```text
├── Dashboards/             # High-resolution dashboard screenshots and export assets
├── Data/                   # Raw & transformed dataset schema
├── Report/                 # Power BI model file (.pbix) and analytical documentation
└── README.md               # Executive project documentation
```

---

<div align="center">

[![GitHub Repository](https://img.shields.io/badge/GitHub-Repository-black?style=flat-square&logo=github)](https://github.com/Gayatrik04/360-Education-Business-Analysis)
[![LinkedIn Profile](https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/gayatri-kasbekar-674a883a3/)

</div>
