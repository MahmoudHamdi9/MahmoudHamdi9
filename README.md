<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=1F497D&height=200&section=header&text=Mahmoud%20Hamdi&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Data%20Analyst&descAlignY=58&descSize=22&descColor=BDD7EE&animation=fadeIn"/>

</div>

<br/>

## `$ whoami`

```yaml
name        : Mahmoud Hamdi El-Sayed
role        : Data Analyst
location    : Egypt 🇪🇬
focus       : End-to-end analytics — from raw data to executive decisions
currently   : Building analytics solutions with SQL Server, Power BI & Python
```

> *I don't just visualize data — I engineer the pipeline that makes it trustworthy.*

---

## ⚙️ Tech Stack

<div align="center">

**Core Tools**

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Data Modeling & Reporting**

![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Star Schema](https://img.shields.io/badge/Star%20Schema-8A2BE2?style=for-the-badge&logo=databricks&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-217346?style=for-the-badge&logo=microsoft&logoColor=white)
![T-SQL](https://img.shields.io/badge/T--SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

**Python Libraries**

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)

**Version Control & Exploration**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&logo=googlebigquery&logoColor=white)

</div>

---

## 🗂️ Featured Projects

<br/>

### 🏢 Commercial Mall (Agamy Star Mall) — End-to-End BI System
> `SQL Server 2022` · `Power BI` · `DAX` · `Galaxy Schema` · `T-SQL`

A full-cycle analytics project simulating a real commercial mall — built entirely from scratch, from database schema to executive dashboard.

**What was built:**
- 🗄️ **15-table relational schema** in SQL Server 2022 with full constraint engineering (PK, FK, CHECK, DEFAULT) ensuring referential integrity across tenancy, finance, and HR
- 🔷 **Galaxy Schema** in Power BI — 5 separate fact tables (Invoices, Collections, Expenses, Violations, Evaluations) connected through shared dimensions, preserving grain integrity across all analytical domains
- 🔍 **7 reusable SQL Views** forming a semantic analytics layer — each anchored to a specific business question, from financial reconciliation to overdue invoice seasonality
- 📊 **2-page executive dashboard** covering collection efficiency (74.73%), zone-level revenue leakage, tenant arrear rankings, HR attendance compliance (83.53%), and individual productivity scoring

**Key finding:** A **structural 25% collection gap** persisting across 4 full fiscal years (2022–2025), with the highest-traffic zone (Main Entrance, 95% footfall) carrying the largest shortfall — confirming the leak is a governance problem, not a demand problem.

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MahmoudHamdi9/Commercial-Mall-End-to-End-BI-System)

---

### 📱 Social Media Marketing Intelligence 
> `Python` · `Power BI` · `DAX` · `Star Schema` · `Apify` · `Regex NLP`

A marketing intelligence initiative built to support data-driven decision-making for a regional retail brand's social media team — analyzing owned performance across Facebook, Instagram, and TikTok, while using publicly available data from an international retail benchmark to better understand audience behavior and validate findings.

**What was built:**
- 🐍 **Python ETL pipeline** using Apify to collect and preprocess 4,768+ social media posts across Facebook, Instagram, and TikTok, including a custom bilingual (Arabic/English) regex-based text-cleaning layer for mixed-language content
- ⭐ **Star Schema** in Power BI — 3 platform-specific fact tables and 2 conformed dimensions (Dim_Calendar, Dim_Brand), powering **30+ DAX measures** across a multi-page marketing intelligence dashboard
- 🌍 **External industry benchmark** — used publicly available data from an international retail benchmark purely as a learning reference to validate audience-behavior patterns and strengthen insights drawn from the brand's own performance, not as a competitive scorecard
- 📅 **Content-pattern analysis** identifying seasonal and event-driven content (Ramadan, Eid, Back-to-School) as the most consistent driver of engagement, and flagging posting-time patterns that require further validation before adoption into the content calendar

**Key finding:** A **six-part executive analysis** delivering prioritized recommendations, KPIs, implementation timelines, and action owners — translating raw social data into a practical roadmap to improve content efficiency, platform allocation, and audience engagement quality.

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MahmoudHamdi9/Marketing-Intelligence-Dashboard)

---

### 🏙️ Real Estate Performance Analytics 
> `Power BI` · `Power Query` · `DAX` · `Star Schema` · `Time Intelligence`

Comprehensive Power BI analytics platform covering **$1.54B in revenue**, 2,000 units sold, and 5,000 client visits across three fiscal years (2023–2025).

**What was built:**
- ⭐ **Star Schema** with 2 fact tables and 3 dimension tables, plus a fully dynamic DAX-generated `Dim_Date` spanning the exact dataset range — no hardcoded boundaries
- 📐 **Complex DAX measures** — Conversion Rate (`DIVIDE`), Agent Average Performance (`AVERAGEX`), Avg Price per SQM — enabling agent-level and property-type benchmarking
- 🔎 **4-page interactive dashboard** covering executive overview, property portfolio, agent leaderboard, and client purchasing behavior with city-level revenue breakdowns

**Key findings:**
- 📉 Miami lead/referral rates dropped **17% YoY** — stagnation rooted in extended lead-to-sale cycles, not weak demand
- 📊 Bottom-tier agents recorded conversion efficiency as low as **17%** — top performers close premium-tier properties, not just more volume
- 💡 2024 buyer cohort identified as highest-ROI retargeting segment vs cold acquisition

[![View Repository](https://img.shields.io/badge/View%20Repository-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/MahmoudHamdi9/Real-Estate-Performance-Analytics-2026-)

---

## 🎓 Certifications

| Certificate | Issuer | Scope |
|:---|:---:|:---:|
| **Microsoft Power BI Data Analyst Professional** | Microsoft / Coursera | 8 Courses |
| **IBM Data Analyst Professional** | IBM / Coursera | 11 Courses |
| **Google Data Analytics Professional** | Google / Coursera | 9 Courses |
| **Data Analysis with SQL & Python** | DataCamp | 10+ Courses |

---
## 📊 GitHub Stats
<img src="https://github-readme-activity-graph.vercel.app/graph?username=MahmoudHamdi9&theme=github-compact&color=BDD7EE&line=1F497D&point=F2C811&hide_border=false"/>
---

## 🤝 Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/Mahmoud-Hamdi-Analyst)
[![Email](https://img.shields.io/badge/Email-mahmoudhamdiwm%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mahmoudhamdiwm@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/MahmoudHamdi9)

<br/>

*"The goal is to turn data into information, and information into insight."*

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=1F497D&height=120&section=footer&animation=fadeIn"/>
