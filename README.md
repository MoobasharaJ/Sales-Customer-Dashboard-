# Sales-Customer-Dashboard-
# 📊 Sales & Customer Performance Dashboard (Tableau)

## 🧠 Overview

This project is an end-to-end Tableau dashboard built to understand how business performance can be tracked using key metrics and interactive visuals.

It includes two main dashboards:

* Sales Dashboard
* Customer Dashboard

The goal of this project was to learn how to structure a dashboard properly — from working with raw data to building something clean, interactive, and easy to use.

---

## ⚙️ What this project covers

### 🔹 Data Understanding & Modeling

* Worked with an Orders dataset and connected it with related information like customers and products
* Understood how data should be structured for analysis (fact vs dimension concept)
* Checked and fixed data types to avoid calculation issues

---

### 🔹 Key Metrics (KPIs)

* Sales
* Profit
* Quantity
* Customers
* Sales per Customer

Each KPI is shown with:

* Current year value
* Comparison with previous year
* A small trend (sparkline)

---

### 🔹 Year-over-Year Comparison

Instead of fixing a specific year, the dashboard allows selecting a year dynamically.
Based on that selection, the dashboard compares current year performance with the previous year.

---

### 🔹 Visualizations Used

* **KPI cards (BANs)** for quick summaries
* **Sparklines** to show monthly trends
* **Bar-in-bar charts** for comparing current vs previous year
* **Histogram** (in customer dashboard) to understand customer behavior

---

### 🔹 Calculations & Logic

* Created dynamic year-based metrics
* Highlighted highest and lowest points in trends
* Compared performance against averages
* Calculated sales per customer

---

## 🎨 Design Approach

* Kept the layout clean and minimal
* Avoided unnecessary elements like gridlines and extra labels
* Maintained consistent spacing across charts
* Focused on readability and clarity

---

## 🔄 Interactivity

* Select year dynamically
* Charts interact with each other on click
* Collapsible filter panel to save space
* Custom tooltips for better readability

---

## 🛠️ Tools Used

* Tableau
* CSV dataset

---

## 🔗 Live Dashboard

[Tableau Public Dashboard Link](https://public.tableau.com/app/profile/moobashara.jawed/viz/SalesCustomerDashboard_17739473770430/SalesDashboard)

---

## 📁 Repository Structure

```
sales-customer-dashboard/
│
├── dashboard/
│   └── Sales_Customer_Dashboard.twbx
│
├── data/
│   └── dataset.csv
│
├── images/        (optional)
│   └── dashboard_preview.png
│
└── README.md
```

---



---
