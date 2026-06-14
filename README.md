[README.md](https://github.com/user-attachments/files/28928884/README.md)
# 📊 Sales & Customer Dashboard | Tableau

> An interactive Tableau project featuring two connected dashboards built to help **sales managers** and **marketing teams** analyze sales performance and understand customer behavior — with year-over-year comparisons for 2023 vs 2022.

---

## 🖼️ Dashboard Previews

### 📈 Sales Dashboard
![Sales Dashboard](sales_dashboard.png)

### 👥 Customer Dashboard
![Customer Dashboard](customer_dashboard.png)

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
To present an overview of sales metrics and trends in order to analyze **year-over-year performance** and understand sales trends.

### 📊 KPIs (2023 vs 2022)
| Metric | 2023 Value | Growth |
|---|---|---|
| **Total Sales** | $733K | ▲ 20.4% vs PY |
| **Total Profit** | $93K | ▲ 14.2% vs PY |
| **Total Quantity** | $12K | ▲ 26.8% vs PY |

### Key Requirements

**📌 KPI Overview**
- Display total sales, profit, and quantity for current year vs previous year

**📈 Sales Trends**
- Monthly KPI data for current and previous year
- Highlight months with highest (🔵) and lowest (🔴) sales

**🏷️ Product Subcategory Comparison**
- Compare sales & profit across all product subcategories (Phones, Chairs, Binders, etc.)
- Bar-in-Bar chart showing 2023 Sales vs 2022 Sales

**📅 Weekly Sales & Profit Trends**
- Weekly sales and profit for current year
- Average reference line (Avg. $14K Sales / Avg. $2K Profit)
- Highlight weeks above and below average

### Charts Used
| Chart | Purpose |
|---|---|
| **Sparkline** | Monthly KPI trends |
| **Bar-in-Bar Chart** | Product subcategory comparison |
| **Line Chart** | Weekly sales & profit trends |

---

## 📋 Dashboard 2 — Customer Dashboard

### Purpose
To provide an overview of customer data, trends, and behaviors — helping marketing teams understand **customer segments** and improve customer satisfaction.

### 📊 KPIs (2023 vs 2022)
| Metric | 2023 Value | Growth |
|---|---|---|
| **Total Customers** | 693 | ▲ 8.6% vs PY |
| **Total Sales per Customer** | $1,058 | ▲ 10.8% vs PY |
| **Total Orders** | 1,687 | ▲ 28.3% vs PY |

### Key Requirements

**📌 KPI Overview**
- Display total customers, sales per customer, and total orders for current year vs previous year

**📈 Customer Trends**
- Monthly KPI data for current and previous year
- Highlight months with highest (🔵) and lowest (🔴) values

**🗂️ Customer Distribution by Number of Orders**
- Bar chart showing how many customers placed 1, 2, 3, 4, 5+ orders
- Provides insight into customer loyalty and engagement

**🏆 Top 10 Customers by Profit**

| Rank | Customer | Last Order | 2023 Profit | 2023 Sales | # Orders |
|---|---|---|---|---|---|
| #1 | Raymond Buch | 25/09/2023 | $6,781 | $14,203 | 3 |
| #2 | Hunter Lopez | 17/11/2023 | $5,046 | $10,523 | 2 |
| #3 | Tom Ashbrook | 22/10/2023 | $4,599 | $13,723 | 2 |
| #4 | Andy Reiter | 24/12/2023 | $2,608 | $5,821 | 2 |
| #5 | Jane Waco | 18/11/2023 | $1,953 | $5,385 | 4 |

### Charts Used
| Chart | Purpose |
|---|---|
| **Sparkline** | Monthly customer KPI trends |
| **Bar Chart** | Customer distribution by order count |
| **Table** | Top 10 customers by profit |

---

## 🔗 Dashboard Interactivity

Both dashboards are **fully interconnected** — navigate between Sales and Customer dashboards using the icons in the top right corner. Filters applied on one dashboard reflect across both for seamless analysis.

---

## 📂 Datasets Used

| File | Description |
|---|---|
| `Customers.csv` | Customer names, IDs and segments |
| `Location.csv` | Region, state and country data |
| `Orders.csv` | Order transactions, dates and sales |
| `Products.csv` | Product categories and subcategories |

---

## ✨ Key Insights

- 📈 Sales grew by **20.4%** in 2023 compared to 2022
- 👥 Customer base expanded by **8.6%** year over year
- 📦 Total orders surged by **28.3%** — strongest growth metric
- 🏆 **Raymond Buch** is the most profitable customer with $6,781 profit
- 📉 **Copiers** subcategory shows loss — area for business attention
- 🗓️ Most customers place only **1–2 orders** — loyalty improvement opportunity
