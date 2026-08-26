# sales-analytics-powerbi
The objective of this project is to analyse sales performance and identify trends in revenue, profit, products, customers, and regions.
# 📊 Sales Analytics Dashboard — Power BI

## 📌 Project Overview

This project is an interactive **Sales Analytics Dashboard** developed using **Microsoft Power BI**.

The dashboard analyzes sales performance across different products, customers, regions, and time periods. It provides key business metrics and visual insights to help stakeholders understand sales trends, profitability, and overall business performance.

---

## 🎯 Business Problem

Businesses need to continuously monitor their sales performance to understand:

* How much revenue is being generated?
* Which products generate the most sales and profit?
* Which regions perform the best?
* How are sales changing over time?
* Which areas require improvement?
* What is the overall profitability of the business?

The objective of this project is to analyze sales performance and identify trends in **revenue, profit, products, customers, and regions** using an interactive Power BI dashboard.

---

## 📈 Key Performance Indicators (KPIs)

The dashboard includes the following key metrics:

| KPI                    | Description                               |
| ---------------------- | ----------------------------------------- |
| 💰 Total Sales         | Total revenue generated from all sales    |
| 📊 Total Profit        | Total profit generated                    |
| 🛒 Total Orders        | Total number of orders                    |
| 💵 Average Order Value | Average revenue generated per order       |
| 📈 Profit Margin       | Percentage of sales converted into profit |
| 📅 Sales Growth        | Change in sales over time                 |

---

## 📊 Dashboard

The Power BI dashboard provides interactive visualizations for analyzing:

* Sales performance
* Profit performance
* Sales trends over time
* Product performance
* Regional performance
* Customer performance
* Profitability
* Order trends

### Dashboard Preview

![Sales Analytics Dashboard](screenshots/dashboard.png)

> 📌 **Note:** Add your Power BI dashboard screenshot to the `screenshots` folder with the filename `dashboard.png`.

---

## 🛠️ Tools & Technologies

* **Microsoft Power BI**
* **DAX**
* **Power Query**
* **Excel / CSV**
* **Data Visualization**
* **Data Cleaning**
* **Business Intelligence**

---

## 🔄 Project Workflow

```text
Raw Sales Data
      ↓
Data Cleaning
      ↓
Power Query
      ↓
Data Transformation
      ↓
Data Modeling
      ↓
DAX Measures
      ↓
Interactive Dashboard
      ↓
Business Insights
```

---

## 🧹 Data Preparation

The data was prepared using **Power Query**.

The data preparation process included:

* Removing duplicate records
* Handling missing values
* Correcting data types
* Cleaning column names
* Creating calculated columns where required
* Transforming the data into an analysis-ready format

---

## 🧮 DAX Measures

The dashboard uses DAX measures to calculate important business metrics.

Example measures include:

```DAX
Total Sales =
SUM(Sales[SalesAmount])
```

```DAX
Total Profit =
SUM(Sales[Profit])
```

```DAX
Total Orders =
DISTINCTCOUNT(Sales[OrderID])
```

```DAX
Average Order Value =
DIVIDE([Total Sales], [Total Orders])
```

```DAX
Profit Margin =
DIVIDE([Total Profit], [Total Sales])
```

> These formulas should be adjusted to match the actual column names in your dataset.

---

## 🔍 Business Questions

This dashboard answers questions such as:

1. What is the total sales revenue?
2. What is the total profit?
3. How many orders were placed?
4. What is the average order value?
5. What is the overall profit margin?
6. How are sales changing over time?
7. Which products generate the highest revenue?
8. Which products generate the highest profit?
9. Which regions have the highest sales?
10. Which regions have the highest profit?
11. Which customers contribute the most revenue?
12. Which areas have lower profitability?

---

## 💡 Key Insights

The dashboard can be used to identify:

* Top-performing products
* Most profitable products
* High-performing regions
* Sales trends
* Profit trends
* High-value customers
* Low-performing business segments
* Changes in sales performance over time

> 📌 Add your actual findings here after completing the dashboard.

### Example

```text
• The highest-performing region generated the largest share of total revenue.
• A small number of products contributed significantly to overall profit.
• Sales increased during specific periods of the year.
• Some products generated high revenue but had comparatively lower profit margins.
```

**Important:** Replace these examples with the actual insights from your dataset.

---

## 📂 Project Structure

```text
sales-analytics-powerbi/
│
├── README.md
│
├── data/
│   └── sales_data.csv
│
├── dashboard/
│   └── Sales_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
└── documentation/
    └── business_questions.md
```

---

## 🚀 How to Use

### 1. Download the repository

```bash
git clone https://github.com/yourusername/sales-analytics-powerbi.git
```

### 2. Open the Power BI file

Navigate to:

```text
dashboard/Sales_Dashboard.pbix
```

Open the file using **Microsoft Power BI Desktop**.

### 3. Explore the dashboard

Use the available filters and visualizations to analyze:

* Sales
* Profit
* Orders
* Products
* Customers
* Regions
* Time periods

---

## 📚 Skills Demonstrated

This project demonstrates practical experience with:

* Power BI
* DAX
* Power Query
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Development
* Data Visualization
* Business Analysis
* Dashboard Development

---

## 🎯 Project Goals

The main goals of this project are to:

* Build an interactive business dashboard
* Analyze sales and profitability
* Identify important business trends
* Create meaningful KPIs
* Present data in an easy-to-understand format
* Support data-driven decision making

---

## 👨‍💻 Author

**Jayaprakash Porapu**

Data Analyst | SQL | Power BI | Python | Generative AI & RAG

---

⭐ If you find this project useful, feel free to explore the repository and connect with me.
