[README.md](https://github.com/user-attachments/files/28928884/README.md)
# 📊 Sales & Customer Dashboard | Tableau

> An interactive Tableau project featuring two connected dashboards built to help **sales managers** and **marketing teams** analyze sales performance and understand customer behavior — with **dynamic year selection** for flexible year-over-year analysis.

---

## 🖼️ Dashboard Previews

### 📈 Sales Dashboard
![Sales Dashboard](sales_dashboard.png)

### 👥 Customer Dashboard
![Customer Dashboard](customer_dashboard.png)

---

## ✨ Key Features

| Feature | Details |
|---|---|
| 🗓️ **Dynamic Year Filter** | Select any year to instantly update all KPIs, charts and trends across both dashboards |
| 🔗 **Interconnected Dashboards** | Filters applied on one dashboard reflect on the other automatically |
| 📊 **Year-over-Year Comparison** | Automatically compares selected year vs previous year for every metric |
| 🔵🔴 **Highest & Lowest Highlights** | Months with highest and lowest values are highlighted automatically |
| ⬆️⬇️ **Above/Below Average** | Weekly trends highlight weeks above and below average |
| 🏛️ **Navigation Icons** | Switch between Sales and Customer dashboards using top-right icons |

---

## 📁 Repository Structure

```
sales-and-customer-dashboard-tableau/
│
├── Sales_Customer_Dashboard.twbx       ← Tableau Packaged Workbook
│
├── datasets/
│     ├── Customers.csv
│     ├── Location.csv
│     ├── Orders.csv
│     └── Products.csv
│
├── docs/
│     └── requirements.pdf
│
├── sales_dashboard.png
├── customer_dashboard.png
└── README.md
```

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Tableau Desktop** | Building dashboards and charts |
| **CSV Files** | Raw data source |

---

## 🔄 Project Workflow

| Phase | Steps |
|---|---|
| **1. Analyse Requirements** | Collect Requirements → Choose Right Charts → Draw Mockups → Choose Colors |
| **2. Build Data Source** | Connect Data → Create Data Model → Rename Fields/Tables → Check Data Types |
| **3. Build Charts** | Create Calculated Fields → Build Charts → Format (Lines, Grids, Axis, Colors, Tooltips) |
| **4. Build Dashboard** | Draw Mockups → Build Container Structure → Assemble Charts → Add Filters & Icons |

---

## 📋 Dashboard 1 — Sales Dashboard

### Purpose
To present an overview of sales metrics and trends in order to analyze **year-over-year performance** and understand sales trends for any selected year.

### 📊 KPIs (Dynamic — updates based on selected year)
| Metric | Example: 2023 | Growth vs PY |
|---|---|---|
| **Total Sales** | $733K | ▲ 20.4% |
| **Total Profit** | $93K | ▲ 14.2% |
| **Total Quantity** | $12K | ▲ 26.8% |

### Key Requirements

**📌 KPI Overview**
- Display total sales, profit and quantity for the selected year vs previous year
- Automatically updates when a different year is selected

**📈 Sales Trends**
- Monthly KPI data for selected year and previous year
- Highlights months with highest (🔵) and lowest (🔴) sales automatically

**🏷️ Product Subcategory Comparison**
- Compare sales & profit across all product subcategories
- Bar-in-Bar chart showing selected year vs previous year sales

**📅 Weekly Sales & Profit Trends**
- Weekly sales and profit for selected year
- Average reference line displayed automatically
- Highlights weeks above and below average

### Charts Used
| Chart | Purpose |
|---|---|
| **Sparkline** | Monthly KPI trends |
| **Bar-in-Bar Chart** | Product subcategory comparison |
| **Line Chart** | Weekly sales & profit trends |

---

## 📋 Dashboard 2 — Customer Dashboard

### Purpose
To provide an overview of customer data, trends and behaviors for any selected year — helping marketing teams understand **customer segments** and improve customer satisfaction.

### 📊 KPIs (Dynamic — updates based on selected year)
| Metric | Example: 2023 | Growth vs PY |
|---|---|---|
| **Total Customers** | 693 | ▲ 8.6% |
| **Total Sales per Customer** | $1,058 | ▲ 10.8% |
| **Total Orders** | 1,687 | ▲ 28.3% |

### Key Requirements

**📌 KPI Overview**
- Display total customers, sales per customer and total orders for selected year vs previous year

**📈 Customer Trends**
- Monthly KPI data for selected year and previous year
- Highlights months with highest (🔵) and lowest (🔴) values

**🗂️ Customer Distribution by Number of Orders**
- Shows how customers are distributed by number of orders placed
- Updates dynamically based on selected year

**🏆 Top 10 Customers by Profit**
- Top 10 customers for the selected year ranked by profit
- Shows Rank, Last Order Date, Sales, Profit and Number of Orders

### Charts Used
| Chart | Purpose |
|---|---|
| **Sparkline** | Monthly customer KPI trends |
| **Bar Chart** | Customer distribution by order count |
| **Data Table** | Top 10 customers by profit |

---

## 🔗 Dashboard Interactivity

- Both dashboards are **fully interconnected**
- **Select any year** from the filter to update all metrics across both dashboards instantly
- Navigate between dashboards using the **icons in the top right corner**
- All charts, KPIs and trends update **automatically** based on the selected year

---

## 📂 Datasets Used

| File | Description |
|---|---|
| `Customers.csv` | Customer names, IDs and segments |
| `Location.csv` | Region, state and country data |
| `Orders.csv` | Order transactions, dates, sales and profit |
| `Products.csv` | Product categories and subcategories |

---

## 💡 Key Insights (2023)

- 📈 Sales grew by **20.4%** compared to 2022
- 👥 Customer base expanded by **8.6%** year over year
- 📦 Total orders surged by **28.3%** — strongest growth metric
- 🏆 **Raymond Buch** is the most profitable customer with $6,781 profit
- 📉 **Copiers** subcategory shows loss — area for business attention
- 🗓️ Most customers place only **1–2 orders** — loyalty improvement opportunity
