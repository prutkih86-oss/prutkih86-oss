
# Hi, I'm Ihor Prudkyi! 👋

### Data Analyst | Business Intelligence | SQL • Python • Power BI • Databricks

I'm a Data Analyst with a strong technical background in mathematical modeling, statistical analysis, and analytical software development.

I bring over 15 years of experience in scientific and engineering environments, along with 8+ years of experience collaborating with international teams at Thermo Fisher Scientific.

My expertise combines **SQL, Python, business intelligence, statistical analysis, data engineering, and product analytics**. I build end-to-end analytical solutions — from data preparation and validation to automated pipelines, interactive dashboards, and actionable business insights.

I also have hands-on experience leading cross-functional development teams and contributing to AI-powered digital products.

📍 Kyiv, Ukraine | Open to remote, hybrid, and on-site opportunities

---

## 🛠️ Tech Stack

- **Data Analysis & Programming:** SQL (PostgreSQL, BigQuery), Python (Pandas, NumPy, SciPy), Statistical Analysis, Exploratory Data Analysis (EDA)
- **Business Intelligence:** Power BI, Tableau, Looker Studio, DAX, Power Query, Data Modeling, KPI Development
- **Data Engineering:** Databricks, Apache Spark, PySpark, Delta Lake, Medallion Architecture, ETL/ELT, Databricks Workflows
- **Product & Web Analytics:** GA4, Event Tracking, Funnel Analysis, User Behavior Analytics, Cohort Analysis, Customer Retention
- **Statistics & Experimentation:** A/B Testing, Hypothesis Testing, Two-Proportion Z-Test, Confidence Intervals
- **Application Development:** React, TypeScript, Vite, HTML, CSS, Python, NiceGUI, REST API, SQLite
- **Tools & Infrastructure:** Git, GitHub, Docker, Jupyter Notebook, Google Colab

---

## 🚀 Portfolio Projects

### 🚕 NYC Taxi Analytics — Databricks Medallion Pipeline

**Overview:** An end-to-end data engineering and analytics solution built in Databricks using the Medallion Architecture (Bronze → Silver → Gold).

The project covers incremental ingestion, data validation, quarantine handling, analytical transformations, workflow orchestration, and interactive BI dashboards.

**Tech Stack:** `Databricks`, `PySpark`, `Python`, `SQL`, `Delta Lake`, `Databricks Workflows`, `AI/BI Dashboards`

**Key Results:**

- Developed an end-to-end Medallion pipeline with incremental Delta Lake `MERGE` operations and SHA-256-based deduplication.
- Implemented automated data quality validation, quarantine handling, and six reconciliation checks across data layers.
- Orchestrated a four-task Databricks Workflow with successful execution in **1 min 30 sec**.
- Processed **21,932 historical taxi trips**, identifying **108 invalid records (0.49% rejection rate)**.
- Built an interactive AI/BI Dashboard covering daily demand, hourly activity, pickup locations, trip distance distribution, and data quality.
- Identified that **73.9% of valid trips were shorter than 3 miles** and observed an **81.3% drop in daily trips** on January 23, 2016, coinciding with Blizzard Jonas.

**Project:** [View Databricks Medallion Pipeline on GitHub](https://github.com/prutkih86-oss/nyc-taxi-medallion-pipeline)

---

### 📊 Beauty AI — Power BI Analytics

**Overview:** An analytical solution for the Beauty AI platform, integrating financial performance, customer behavior, and Google Analytics 4 data.

**Tech Stack:** `Power BI`, `SQL`, `Google BigQuery`, `GA4`, `DAX`, `Power Query`

**Key Results:**

- Developed three interactive Power BI dashboards: Revenue Overview, User Behavior, and Google Analytics.
- Analyzed **UAH 4.07M in total booking value** and **UAH 499.2K in platform revenue**.
- Conducted cohort analysis of customer retention, repeat bookings, and acquisition channels.
- Evaluated AI recommendation performance, identifying a **66.88% acceptance rate**.
- Integrated Google Analytics 4 data through BigQuery to analyze user events, search behavior, and booking journeys.
- Developed DAX measures and visualizations to monitor key business metrics.

**Project:** [Beauty AI — Power BI Analytics](https://github.com/prutkih86-oss/Beauty-AI-PowerBI)

---

### 🛒 E-commerce Sales Analytics

**Overview:** An end-to-end analytics workflow combining SQL data preparation, exploratory analysis in Python, and interactive Tableau dashboards.

**Tech Stack:** `SQL (BigQuery)`, `Python`, `Tableau`, `Google Colab`

**Key Results:**

- Prepared analytical datasets and optimized SQL queries in Google BigQuery.
- Performed exploratory data analysis (EDA) using Python.
- Developed two interactive Tableau dashboards to monitor business performance and user engagement.
- Identified insights into sales trends, customer behavior, and revenue dynamics.

**Project Links:**

- [Python Analysis — Google Colab](https://colab.research.google.com/drive/1eFkfPcgO2uLSQW4Abcbjp8ty9att6olt?usp=sharing)
- [Interactive Tableau Dashboard](https://public.tableau.com/views/E-commerceSalesAnalytics_17850731402860/Dashboard1)

---

### 🧪 A/B Testing — Statistical Analysis

**Overview:** Statistical analysis of four A/B experiments using a dataset containing **800,996 records** of user activity.

**Tech Stack:** `Python`, `Pandas`, `NumPy`, `Statsmodels`, `Tableau`, `Google Colab`, `Hypothesis Testing`

**Key Results:**

- Automated statistical significance testing using the Two-Proportion Z-test at a significance level of 0.05.
- Calculated conversion rates, relative lift, p-values, and 95% confidence intervals.
- Analyzed four conversion metrics: `add_payment_info`, `add_shipping_info`, `begin_checkout`, and `new account`.
- Compared results across countries, devices, marketing channels, and continents.
- Generated **1,811 rows of statistical results** across experiments, metrics, and segments.
- Developed an interactive Tableau dashboard to compare control and test groups, conversion lift, and statistical significance.

**Example — Experiment 1:**

The test variant increased the `add_payment_info` conversion rate from **4.38% to 4.93%**, representing a **12.54% relative lift (p < 0.001)**.

The result was statistically significant at the 0.05 level.

**Project Links:**

- [Python Statistical Analysis — Google Colab](https://colab.research.google.com/drive/1WAMq8exuOHQtcFJdfP37v7G9Dj23IsGx?usp=sharing)
- [Interactive Tableau Dashboard](https://public.tableau.com/views/ABTestingAnalysis_17850804481790/Dashboard1)

---

### 📈 Sales Performance Analysis — Google Sheets

**Overview:** Sales performance analysis of 1,328 orders across 45 countries (2010–2017), using Google Sheets for business reporting, profitability analysis, and interactive visualization.

**Tech Stack:** `Google Sheets`, `Pivot Tables`, `ABC Analysis`, `KPI Dashboard`, `Data Visualization`

**Key Results:**

- Developed a 13-sheet analytical workbook covering sales, revenue, profitability, and business performance.
- Built a KPI dashboard with revenue, profit, average order value, and profit margin metrics.
- Analyzed product categories, geographic markets, sales channels, delivery times, and sales trends.
- Conducted ABC analysis to classify product categories by revenue contribution.
- Identified four Category A product groups accounting for approximately 74.73% of revenue in the ABC analysis table.

**Project:** [View Sales Performance Report — Google Sheets](https://docs.google.com/spreadsheets/d/1-mEMTOA3SfxDvOKRGze0eVKO1u8RQ3qK3RAtcjMS41Y/edit)

---


### 🦋 Beauty AI Platform — Team Lead / Development

**Overview:** A cross-functional team project developing a digital platform for discovering and booking beauty services, featuring personalized AI recommendations.

**My Role:** Team Lead, Frontend Development, Admin Panel Development, Data Integration, and Analytics.

**Tech Stack:** `React`, `TypeScript`, `Vite`, `Python`, `NiceGUI`, `REST API`, `SQLite`, `React Leaflet`, `OpenStreetMap/CARTO`, `Git/GitHub`

**Key Results:**

- Led cross-functional team collaboration, coordinating development tasks and project delivery.
- Developed a responsive frontend for desktop and mobile with search, categories, recommendations, and interactive maps.
- Built an Admin Panel with dashboards, analytics, and management interfaces for bookings, clients, professionals, services, and payments.
- Designed modular frontend and admin application structures for backend and API integration.
- Developed analytical components for monitoring business performance metrics.

**Project Links:**

- [Beauty AI Frontend](https://github.com/prutkih86-oss/beauty-ai-frontend)
- [Beauty AI Admin Panel](https://github.com/prutkih86-oss/beauty-ai-admin)
- [Beauty AI Power BI Analytics](https://github.com/prutkih86-oss/Beauty-AI-PowerBI)

---

## 🎯 Areas of Interest

- Data Analytics & Business Intelligence
- Product Analytics & Customer Behavior
- Data Engineering & ETL Pipelines
- Statistical Analysis & Experimentation
- Business Performance & KPI Development
- AI-Powered Products & Analytics

---

## 📬 Contact

- **LinkedIn:** [Ihor Prudkyi](https://www.linkedin.com/in/ihor-prudkyi/)
- **Email:** [ihor.prudkyi.da@gmail.com](mailto:ihor.prudkyi.da@gmail.com)
- **GitHub:** [prutkih86-oss](https://github.com/prutkih86-oss)
