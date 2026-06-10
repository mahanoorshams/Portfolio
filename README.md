# Mahanoor Shams | Data Analyst Portfolio

Data analyst with 3 years of experience building SQL pipelines, Power BI dashboards, and operational reporting for cross-functional teams. This portfolio showcases personal projects across customer analytics, business intelligence, data engineering, and data storytelling.

---

## Projects

### 1. NHS RTT Waiting Times Dashboard

**Goal:** Analyse NHS Referral to Treatment waiting times across England from January 2021 to March 2025, surfacing key metrics around waiting list volume, year on year change, and the proportion of patients waiting beyond critical thresholds.

What this covers:

- Power BI: multi-page dashboard with five KPI cards, trend line chart, and specialty breakdown bar charts
- DAX: custom measures for latest month wait list, average monthly wait list, year on year change with conditional formatting, long waiters count, and percentage over 52 weeks
- Data modelling: rebuilt Date_Table as a DAX calculated table with correct relationships, synced slicers across pages
- Healthcare domain: NHS RTT pathway types, incomplete pathways, and the 52-week breach threshold

Key finding: The NHS waiting list grew from approximately 10 million patients at the Pre-Covid baseline to 24 million by March 2025, with Trauma and Orthopaedic Service consistently representing the largest share of both total wait list volume and long waiters beyond 52 weeks.

🔗 [View project](https://github.com/mayasyed/nhs-rtt-waiting-times)

---

### 2. dbt E-commerce Analytics Pipeline

**Goal:** Build a fully tested, documented dimensional model from raw e-commerce transactional data using dbt Core and Google BigQuery, demonstrating modern analytics engineering practices.

What this covers:

- dbt Core: three-layer ELT pipeline with staging and mart models
- Google BigQuery: cloud data warehouse execution
- Dimensional modelling: fact and dimension tables following star schema design
- Data quality: 23 schema tests validating not_null and unique constraints across all models
- Documentation: auto-generated dbt docs with lineage graph

Key outcome: Transformed 181k raw order item records from the thelook_ecommerce public dataset into a clean dimensional model consisting of one fact table and three dimension tables, with full test coverage and lineage documentation.

🔗 [View project](https://github.com/mayasyed/dbt-ecommerce-portfolio)

---

### 3. Customer Churn Analysis

**Goal:** Identify high-risk customer segments and recommend actions to reduce early drop-off for a telecoms subscription business.

What this covers:

- SQL: churn metrics, cohort segmentation, aggregations
- Python: data cleaning, exploratory analysis, visual storytelling
- Tableau: interactive churn dashboard with segment filters

Key finding: Month-to-month contract customers with fibre internet and no add-on services had the highest churn rate, accounting for a disproportionate share of revenue lost in the first 90 days.

🔗 [View project](https://github.com/mayasyed/Portfolio/blob/main/customer-churn) 🔗 [Live Tableau dashboard](https://public.tableau.com/app/profile/mahanoor.shams/viz/TelcoCustomerChurn_17673780438080/CustomerChurnOverview)

---

### 4. Fitness Tracker Dashboard

**Goal:** Explore the relationship between daily physical activity and sleep quality using real Fitbit data, and surface actionable patterns for rest and recovery.

What this covers:

- Power BI: multi-page dashboard with KPI cards, trend lines, and activity/sleep correlation visuals
- DAX: custom measures for average sleep duration, active minutes, step targets, and intensity segmentation
- Data preparation: merging and cleaning multiple CSV sources across activity, intensity, and sleep tables

Key finding: Users with consistently high active minutes during the day showed measurably better sleep duration, while irregular intensity patterns correlated with shorter and more fragmented rest.

🔗 [View project](https://github.com/mayasyed/Portfolio/blob/main/fitness-tracker/README.md)

---

### 5. EMEA Commercial Revenue Reconciliation

**Goal:** Validate H1 2024 commercial revenue records across 7 EMEA markets and 10 media agency partners, identifying discrepancies between reported revenue and invoice amounts before payment authorisation.

What this covers:

- Excel: data cleaning and standardisation across 100 messy records with inconsistent market names, date formats, currencies, and status values
- FX conversion: EUR to GBP using real month-end exchange rates via VLOOKUP and a reference rate table
- Variance analysis: Match, Review, and Escalate classifications with threshold-based logic
- Dashboard: SUMIF-based summary broken down by market, agency, and month
- Escalation log: 17 flagged records with structured columns for action owner and resolution tracking

Key finding: 48 records matched cleanly, 32 required review, and 17 were escalated. France showed the largest negative variance at 16%, partly driven by 3 records with missing invoice amounts. Hearts & Science had the highest agency-level variance at +11.28%.

🔗 [View project](https://github.com/mayasyed/Portfolio/tree/main/emea-commercial-reconciliation) 🔗 [View in Google Sheets](https://docs.google.com/spreadsheets/d/1Ie-t5AwX5xTFWl-XOcmikoPioKNgRpgBFY_QCLhQAY0/edit?usp=sharing)

---

## Project Structure

Each project has its own folder or repository containing the relevant files and a README explaining the approach, findings, and tools used.

---

## Tools Used Across This Portfolio

SQL, dbt Core, Google BigQuery, Python (pandas, matplotlib, seaborn), Power BI, DAX, Tableau, Excel

---

## Get in Touch

- 💼 [LinkedIn](https://linkedin.com/in/mahanoor-shams)
- 📧 [mahanoorshams@outlook.com](mailto:mahanoorshams@outlook.com)
