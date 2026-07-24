# 📊 Sales Insight Dashboard using Power BI

An interactive **Power BI dashboard** built for **AtliQ**, designed to help stakeholders track sales performance, profitability, and regional trends at a glance. The dashboard consolidates revenue, quantity, and profit margin data across markets, customers, and products into a single, drill-down-enabled view.

🔗 **Repository:** [Sales-Insight-Dashboard-using-PowerBI](https://github.com/niharikakt024/Sales-Insight-Dashboard-using-PowerBI)

---

## 🖥️ Dashboard Preview

### 1. Sales Overview
Tracks overall revenue, sales quantity, revenue by market, sales quantity by market, monthly revenue trend, and top 5 revenue contributors by customer and product.

### 2. Profit Analysis
Breaks down revenue and profit contribution by customer and by market, along with profit margin % per market — helping identify the most and least profitable regions.

### 3. Performance Insights
An executive summary view with a configurable **profit target slider**, a combined revenue trend (current year vs. last year) with profit margin %, and revenue contribution by region (North, South, Central).

---

## ✨ Key Features

- **KPI Cards** — Total Revenue, Sales Quantity, and Total Profit Margin at a glance
- **Year & Month Slicers** — Filter data across 2017–2020 and by month
- **Market-wise Breakdown** — Revenue and sales quantity by city/market (Delhi, Mumbai, Ahmedabad, Bhopal, Nagpur, Kochi, Chennai, etc.)
- **Top 5 Analysis** — Highest-revenue customers and products
- **Revenue Trend Chart** — Monthly trend line highlighting seasonal peaks and dips
- **Profit Analysis Page** — Revenue/profit contribution %, and profit margin % by market and customer
- **Performance Insights Page** — Region-level (North/South/Central) contribution with adjustable profit target and YoY trend comparison
- **Drill-through Ready** — Customer-level tables with revenue, revenue contribution %, and profit margin contribution %

---

## 🛠️ Tech Stack

- **Tool:** Microsoft Power BI Desktop
- **Data Modeling:** Star schema with fact and dimension tables
- **DAX:** Custom measures for Revenue, Profit Margin %, Contribution %, and YoY comparisons
- **Data Source:** Sales, customer, product, and market transactional data

---

## 📁 Repository Structure

```
Sales-Insight-Dashboard-using-PowerBI/
│
├── Dashboard.pbix          # Power BI dashboard file
├── Screenshots/            # Dashboard preview images
└── README.md                # Project documentation
```

---

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/niharikakt024/Sales-Insight-Dashboard-using-PowerBI.git
   ```
2. Open the `.pbix` file in **Power BI Desktop**
3. Refresh the data source (if connected to live data)
4. Explore the three report pages: **Sales Overview**, **Profit Analysis**, and **Performance Insights**

---

## 📈 Key Insights

- Delhi NCR is the leading market, contributing over **50% of total revenue**
- The **Electrical** customer segment is the single largest revenue contributor
- Overall profit margin stands at **~2.5%**, with wide variance across markets — some regions (e.g., Bengaluru) show negative margins
- Revenue shows a **declining trend** from FY18 through FY20, signaling a need for deeper regional and product-level review

---

## 👤 Author

**Niharika**
GitHub: [@niharikakt024](https://github.com/niharikakt024)

---

⭐ If you find this project useful, consider giving the repository a star!
