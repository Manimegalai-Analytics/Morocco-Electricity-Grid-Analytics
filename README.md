# Morocco-Electricity-Grid-Analytics
Data cleaning and Interactive Dashboard analysis of 52,417 rows of Morocco's Electricity Consumption data.

# ⚡ Morocco Electrical Grid: Advanced Demand & Load Analytics

![Excel](https://shields.io)
![Data Scale](https://shields.io)
![Status](https://shields.io)

## 📌 Project Overview
An end-to-end data diagnostics, optimization, and business intelligence tracking framework executed on a high-volume public utilities dataset. This project processes **52,417 rows** of continuous 10-minute interval power consumption telemetry across localized distribution zones to isolate, quantify, and visualize electrical grid load anomalies.

---

## 🛠️ Data Architecture & Pipeline

### 1. Data Cleaning & Optimization Layer
* 🔹 **Structural Rectification:** Programmatically adjusted column spacing and text widths to eliminate overflow parameters.
* 🔹 **Imputation Engineering:** Isolated system telemetry dropouts and zero-readings using structured filtering arrays; applied target adjustments to prevent math skewing.
* 🔹 **Data Backup:** Instituted isolated multi-tier worksheets (`Raw` vs `Cleaned Data`) to preserve source audit trail integrity.

### 2. Analytical KPI Engineering
A custom performance-tracking column (**Grid Load Status**) was engineered across all 50k+ records using advanced logic arrays to isolate systemic peak stress periods dynamically:

$$\text{Load Classification} = \text{IF}\left(\text{Zone1\_Power} > \text{AVERAGE}(\text{Zone1\_Power}), \text{"High Demand"}, \text{"Normal"}\right)$$

### 3. Business Intelligence Dashboard
* 🔹 **Pivot Multi-Threading:** Aggregated temporal logs to extract operational hourly and seasonal consumption averages.
* 🔹 **Dynamic Visualization:** Modeled trend lines mapping grid load fluctuations against timeline vectors.
* 🔹 **Interactive Slicer Integration:** Connected physical interface controls allowing immediate cross-filtering of peak vs normal grid states.

---

## 📊 Dataset Structural Map

| Column Name | Data Type | Analytical Utility |
| :--- | :--- | :--- |
| **Datetime** | Temporal (Date/Time) | Core timeline vector tracking 10-minute grid logs |
| **PowerConsumption_Zone1** | Numeric (Continuous) | Primary electrical grid load tracking metric |
| **Grid Load Status** | Alphanumeric (KPI) | Engineered logical flag isolating demand spikes |

---

## 🎯 Key Analytical Insights Delivered
* 📈 Identified precise, recurring temporal windows where regional consumption exceeded baseline grid averages.
* 📈 Scaled spreadsheet calculation workflows across a high-volume 52,417 row processing matrix without computing lag.
* 📈 Built an executive-ready reporting asset allowing system managers to filter grid stress data points in one click.

---
### 👨‍💻 Candidate Technical Blueprint
* **Name:** [MANIMEGALAI S]
* **Education:** BCA Graduate (2026)
* **Core Competencies:** Advanced Spreadsheet Modeling, Structural Data Cleaning, KPI Logic Design, Pivot Dashboarding
* **Availability:** Immediate Joiner

📬 [Connect with me on LinkedIn](https://www.linkedin.com/in/manimegalai-s-319734381) | 📁 [View My Full Portfolio](Manimegalai-Anlytics)
