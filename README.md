# Digital-Marketing-Campaigns-Power-BI-dashsbaords
## 📊 Digital Marketing Campaigns Analysis Dashboard

This project showcases an interactive Power BI dashboard focused on analyzing digital marketing campaigns. It helps monitor and optimize campaign performance by providing key performance indicators (KPIs) to support data-driven decision-making.

---

## 🧠 Objectives

- Analyze the effectiveness of digital marketing campaigns.
- Visualize key performance indicators.
- Identify the most efficient marketing channels.
- Understand user behavior through conversion funnel tracking.

---

## 🛠️ Tools and Technologies

- **Power BI Desktop** – Data visualization
- **Excel / CSV** – Simulated from python software
- **DAX (Data Analysis Expressions)** – Custom KPIs and metrics

---

## 🧱 Data Modeling

The data model follows a **star schema architecture**, optimized for performance and easy analysis in Power BI.

### 🔹 Star Schema Overview

- **Fact Table:**
  - `MarketingPerf_data`: contains quantitative metrics (clicks, impressions, conversions, costs, ROI, allocated budget, etc.)

- **Dimension Tables:**
  - `dim_date`: temporal dimension (year, quarter, month, week…)
  - `dim_budgetallocation data`
  - `dim_leadgeneration data`


### ✅ Benefits

- Fast query performance
- Clean and scalable data model
- Easier DAX implementation
- Enhanced readability for business users

---

## 📈 Key Features

- **Campaign performance overview**: impressions, clicks, conversions, costs
- **Channel analysis**: compare efficiency across traffic sources
- **Conversion and ROI tracking**: understand the financial impact of campaigns
- **Budget allocation analysis**: view how marketing budget is distributed and spent per channel or campaign
- **Temporal heatmaps**: performance by day, week, or month
- **Interactive filtering**: by time period, channel, country, device…

---

## 💰 Budget Allocation Analysis

The dashboard includes a **dedicated section** to analyze how the marketing budget is:

- **Allocated across channels and campaigns**
- **Spent relative to conversions and ROAS**
- **Utilized over time**

This allows marketing teams to **identify underperforming or overspending areas** and make smarter investment decisions.

---

## 🔍 Sample KPIs

- **CPC (Cost Per Click)**
- **CTR (Click-Through Rate)**
- **Conversion Rate**
- **ROAS (Return On Ad Spend)**
- **Impressions / Clicks / Conversions**
- **Budget Utilization Rate**

---

## 📥 Data

The datasets used are simulated. It includes:

- Campaign and channel identifiers
- Traffic sources
- Budget allocation and spending
- Impressions, clicks, conversions
- Costs and conversion value
- Date, country, device type

---

## 🚀 How to Use

1. Download the `DigitalMarketingDashboard.pbix` file.
2. Open it with Power BI Desktop.
3. If needed, reconfigure data source paths via:
   **Transform Data > Data Source Settings**

---

## 📌 About the Project

This dashboard was built as part of a marketing analytics initiative. The goal is to provide a strategic, visual, and interactive tool to monitor campaign performance, optimize budget allocation, and support decision-making for marketing professionals.

---
