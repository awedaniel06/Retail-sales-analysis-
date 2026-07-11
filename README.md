# Retail Sales Performance Dashboard (Power BI)

A 3-page Power BI reporting suite analyzing retail sales performance across five regions and twenty store branches in Nigeria, covering **484 transactions**, **2,580 units sold**, **182 unique customers**, and **₦102.19M+** in tracked sales between **January 2023 and July 2024**.

The report is built as three linked pages — **Overview**, **Regional**, and **Customer** — each sharing a consistent slicer panel (Year, Month, SalesRepID) and region quick-filter buttons for seamless cross-page filtering.

---

## 📊 Dashboard Pages

### 1. Executive Summary Dashboard
High-level snapshot of overall business performance: revenue, transactions, quantity sold, and return rate, alongside monthly revenue trends, category mix, payment type breakdown, and returns.

![Executive Summary Dashboard](executive_summary_dashboard.png)

**Key metrics:** Revenue · Total Transactions · Total Quantity · Return Rate · No-Return Rate

### 2. Regional Performance Dashboard
Drills into performance by city, region, and individual store branch, with a sortable branch-level table (transactions, quantity, total sales).

![Regional Performance Dashboard](regional_performance_dashboard.png)

**Key metrics:** Total Regions · Total Transactions · Avg. Quantity · Avg. Revenue

### 3. Customer Performance Dashboard
Profiles the customer base by loyalty status, customer type, age group, and gender, and identifies top individual customers by revenue.

![Customer Performance Dashboard](customer_performance_dashboard.png)

**Key metrics:** Total Customers · Total Transactions · Quantity per Customer · Average Order Value (AOV)

---

## 🔑 Key Insights

- **Category concentration:** Electronics drives **78.7%** of total revenue, far ahead of Home & Kitchen (10.9%), Clothing (6.6%), Health & Beauty (2.5%), and Groceries.
- **Regional stronghold:** The **South South** region — led by **Benin City** — is the top-performing region and city, outperforming Lagos despite Lagos's reputation as Nigeria's leading commercial hub.
- **Payment preference:** **POS** is the leading payment method, followed by Transfer, Cash, Card, and Online — pointing to a customer base still favoring in-person and bank-transfer payments over digital checkout.
- **Customer retention:** **72.53%** of customers are returning customers (132 of 182), a healthy retention signal.
- **Elevated returns:** A **22.73%** product return rate is flagged as the most significant area for further investigation.
- **Customer type:** Walk-In customers generate more revenue and transactions than the Loyal segment, suggesting room to grow loyalty program enrollment.

*See the full [analysis report](./Retail_Dashboard_Performance_Report.pdf) for detailed findings and recommendations.*

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — data modeling, DAX measures, and report design
- **Power Query** — data cleaning and transformation
- **DAX** — calculated KPIs (Revenue, Return Rate, AOV, Avg. Revenue, etc.)

---

## 📁 Repository Contents

```
├── README.md                                    # Project overview (this file)
├── Retail_Dashboard_Performance_Report.pdf       # Full written analysis report
├── executive_summary_dashboard.png               # Overview page screenshot
├── regional_performance_dashboard.png            # Regional page screenshot
└── customer_performance_dashboard.png            # Customer page screenshot
```

---

## 👤 Author

**Sphere (Daniel Awe Olamilekan)**
Data Analytics Intern, AnalystLab Africa
[LinkedIn](https://www.linkedin.com) · [GitHub](https://www.github.com)

---

## 📄 License

This project is shared for portfolio and educational purposes. Data has been anonymized/aggregated for public sharing.
