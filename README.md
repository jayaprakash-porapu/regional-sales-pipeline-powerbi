# 📊 Regional Sales & Pipeline Analytics — Power BI

## 📌 Project Overview

This project presents an interactive **Regional Sales and Sales Pipeline Analytics Dashboard** developed using **Microsoft Power BI**.

The dashboard provides insights into sales opportunities, revenue performance, pipeline health, win/loss ratios, products, industries, territories, sales owners, and forecasting.

The objective is to help sales managers and business stakeholders monitor sales performance, identify high-performing areas, understand opportunity trends, and make better data-driven sales decisions.

---

## 🎯 Business Problem

Sales teams need visibility into both completed sales and opportunities currently moving through the sales pipeline.

This dashboard helps answer important business questions such as:

* How much revenue has been won?
* How much revenue is currently in the sales pipeline?
* What is the overall opportunity close rate?
* Which products generate the most revenue?
* Which territories perform best?
* Which industries provide the strongest opportunities?
* How are individual sales owners performing?
* How does sales performance change over time?
* What factors influence whether an opportunity is won?
* What factors affect the number of days an opportunity remains open?
* How does discount percentage influence sales opportunities?

---

## 📈 Key Performance Indicators

The report analyzes several important sales KPIs:

| KPI                       | Description                                           |
| ------------------------- | ----------------------------------------------------- |
| 💰 Revenue Won            | Revenue generated from successfully won opportunities |
| 🔄 Revenue in Pipeline    | Potential revenue from active sales opportunities     |
| 📂 Revenue Open           | Revenue associated with open opportunities            |
| 🎯 Close %                | Percentage of opportunities successfully closed       |
| 📊 Opportunity Count      | Total number of sales opportunities                   |
| 💵 Average Deal Size      | Average revenue generated from won deals              |
| 🎯 Revenue Goal           | Sales revenue target                                  |
| 🔮 Forecast %             | Forecasted sales performance                          |
| 📈 Pipeline Opportunities | Number of opportunities currently in the pipeline     |

---

# 📊 Dashboard Pages

## 1. Overview

Provides a high-level view of overall sales and pipeline performance.

The page analyzes performance across:

* Territories
* Products
* Product Categories
* Sales Owners
* Sales Stages
* Accounts
* Revenue
* Pipeline
* Forecasts

It provides management with a quick overview of current sales performance.

---

## 2. Win/Loss Ratio

Analyzes successfully won and lost sales opportunities.

This page helps evaluate:

* Win/loss performance
* Sales owner performance
* Product performance
* Opportunity trends
* Close percentage
* Won opportunities

This analysis can help identify sales representatives, products, or periods associated with stronger conversion performance.

---

## 3. Industries Overview

Provides sales performance analysis across different industries.

The dashboard compares:

* Industries
* Accounts
* Sales owners
* Revenue
* Opportunities
* Industry trends

This helps identify industries that contribute strongly to the sales pipeline and revenue.

---

## 4. Trend Analytics

Analyzes sales and opportunity performance over time.

The dashboard uses time-based analysis to identify:

* Revenue trends
* Pipeline trends
* Opportunity trends
* Changes in sales performance
* Monthly performance patterns

This allows stakeholders to understand whether sales performance is improving or declining.

---

## 5. Pipeline Trends

Focuses specifically on opportunities currently progressing through the sales pipeline.

The analysis includes:

* Accounts
* Sales owners
* Products
* Territories
* Industries
* Opportunity counts
* Pipeline revenue

This page helps sales managers understand the current health and composition of the pipeline.

---

## 6. Won Key Influencers

Uses Power BI's **Key Influencers** functionality to investigate factors associated with successfully won opportunities.

The analysis can help determine which factors have the strongest relationship with successful sales outcomes.

---

## 7. Days Key Influencers

Analyzes factors that influence how long sales opportunities remain open.

The analysis considers dimensions such as:

* Sales owners
* Industries
* Opportunity characteristics

This can help identify factors associated with longer or shorter sales cycles.

---

## 8. % Off Key Influencers

Analyzes factors associated with discount percentages across opportunities.

The analysis considers areas such as:

* Territories
* Sales owners
* Opportunity characteristics

This helps stakeholders better understand discounting patterns within the sales process.

---

## 9. Decomposition Analysis

Uses a **Decomposition Tree** to perform deeper analysis of sales performance.

The analysis allows users to drill into dimensions including:

* Products
* Opportunities
* Industries
* Territories
* Sales owners

This helps identify the underlying contributors to sales and revenue performance.

---

# 🗂️ Data Model

The Power BI report works with several business entities, including:

* Opportunities
* Accounts
* Products
* Product Categories
* Territories
* Owners
* Managers
* Industries
* Campaigns
* Opportunity Calendar
* Forecast Adjustments
* Calculations

These entities allow sales performance to be analyzed from multiple business perspectives.

---

# 🔍 Important Analysis Dimensions

### 🌎 Territory Analysis

Compare sales and pipeline performance across different territories.

### 📦 Product Analysis

Analyze revenue and opportunities by:

* Product
* Product Category

### 🏢 Industry Analysis

Understand which industries contribute most strongly to opportunities and revenue.

### 👤 Sales Owner Analysis

Evaluate sales performance across:

* Sales Owners
* Managers

### 📅 Time Analysis

Analyze sales performance using monthly and date-based trends.

### 🏦 Account Analysis

Understand performance and opportunities associated with individual customer accounts.

---

# 🧮 Measures & Metrics

The Power BI model includes measures related to:

* Revenue Won
* Revenue in Pipeline
* Revenue Open
* Close %
* Opportunity Count
* Revenue Goal
* Forecast %
* Forecast
* Average Won Deal Size
* Count of Won Opportunities
* Pipeline Opportunity Count

These measures support interactive analysis throughout the dashboard.

---

# 📊 Visualizations

The report uses a variety of Power BI visualizations, including:

* KPI Cards
* Bar Charts
* Column Charts
* Line Charts
* Combo Charts
* Funnel Charts
* Ribbon Charts
* Tables
* Matrix Visuals
* Scatter Charts
* Shape Maps
* Key Influencers
* Decomposition Tree
* Slicers
* Page Navigation

---

# 🛠️ Tools & Technologies

* Microsoft Power BI
* DAX
* Power Query
* Data Modeling
* Data Visualization
* Business Intelligence
* Sales Analytics
* Data Analysis

---

# 💡 Business Value

This dashboard can help sales management:

* Monitor sales performance
* Track revenue won and pipeline revenue
* Evaluate opportunity conversion
* Compare territory performance
* Identify high-performing products
* Analyze industry performance
* Monitor sales representatives
* Understand sales trends
* Evaluate pipeline health
* Improve forecasting
* Investigate factors influencing sales outcomes
* Support data-driven sales decisions

---

# 📂 Recommended GitHub Structure

```text
regional-sales-pipeline-powerbi/
│
├── README.md
│
├── dashboard/
│   └── Regional_Sales_Dashboard.pbix
│
├── screenshots/
│   ├── overview.png
│   ├── win-loss-ratio.png
│   ├── industries-overview.png
│   ├── trend-analytics.png
│   ├── pipeline-trends.png
│   ├── won-key-influencers.png
│   └── decomposition-analysis.png
│
└── documentation/
    └── business_questions.md
```

---

# 🚀 Skills Demonstrated

This project demonstrates practical skills in:

### 📊 Power BI

* Dashboard Development
* Interactive Reports
* Report Navigation
* Slicers and Filters
* KPI Development
* Drill-down Analysis

### 🧮 DAX

* Measures
* Revenue Calculations
* Opportunity Metrics
* Percentage Calculations
* Forecast Metrics
* KPI Calculations

### 🔄 Data Preparation

* Power Query
* Data Cleaning
* Data Transformation
* Data Preparation

### 🗃️ Data Modeling

* Relationship Management
* Multiple Business Entities
* Calendar/Date Analysis
* Measures and Calculations

### 📈 Data Visualization

* KPI Cards
* Bar and Column Charts
* Line Charts
* Funnel Charts
* Scatter Charts
* Maps
* Matrix Visuals
* Ribbon Charts

### 🤖 Advanced Power BI Analytics

* Key Influencers
* Decomposition Tree
* Forecast Analysis
* Trend Analysis

### 💼 Business & Sales Analytics

* Sales Performance Analysis
* Sales Pipeline Analysis
* Revenue Analysis
* Win/Loss Analysis
* Product Analysis
* Territory Analysis
* Industry Analysis
* Sales Representative Analysis
* Opportunity Analysis
* Sales Forecasting

---

# 👨‍💻 Author

**Jayaprakash Porapu**

**Data Analyst | Power BI | SQL | Python | Generative AI & RAG**
