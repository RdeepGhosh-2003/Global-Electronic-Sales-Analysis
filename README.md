# 📊 Electronics Sales Dashboard — Power BI

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Data Analytics](https://img.shields.io/badge/Data%20Analytics-FF6F00?style=for-the-badge&logo=google-analytics&logoColor=white)

> A comprehensive, industry-level Power BI dashboard built on a global electronics retail dataset spanning **2016–2021**, uncovering over **$57M in revenue insights** across 9 countries, 67 stores, and 15,000+ customers.

---

## 🖼️ Dashboard Preview

### Executive Summary
<img width="668" height="375" alt="SUMMARY" src="https://github.com/user-attachments/assets/53b85e15-a073-46f5-aed3-f9aac37e5259" />

### Sales & Revenue Analysis
<img width="668" height="376" alt="SALES AND REVENUE ANALYSIS" src="https://github.com/user-attachments/assets/ef8b3ac3-c4c4-4c15-b79e-10f396b4f708" />

### Product Performance
<img width="669" height="377" alt="PRODUCT PERFORMANCE" src="https://github.com/user-attachments/assets/4ddbaed0-b703-4a6d-b8fe-2204352ce01e" />

### Customer Insights
<img width="669" height="376" alt="CUSTOMER INSIGHTS" src="https://github.com/user-attachments/assets/d52f2370-d9ee-4959-a840-8909887a7f71" />

### Store Performance
<img width="669" height="375" alt="STORES PERFORMANCE" src="https://github.com/user-attachments/assets/4fd059be-ed9c-43db-9865-1457b464e6f8" />

### Insights & Forecasting
<img width="670" height="403" alt="INSIGHTS" src="https://github.com/user-attachments/assets/0df14e63-be37-4f7b-bea6-38cf6ff99f87" />

---

## 📌 Table of Contents
- [Overview](#-overview)
- [Business Problems Solved](#-business-problems-solved)
- [Key Insights](#-key-insights)
- [Dashboard Pages](#-dashboard-pages)
- [Key Metrics](#-key-metrics)
- [Data Model](#-data-model)
- [DAX Measures](#-dax-measures)
- [Tools & Techniques](#-tools--techniques)
- [Data Sources](#-data-sources)
- [How to Use](#-how-to-use)
- [Future Improvements](#-future-improvements)
- [Author](#-author)

---

## 🔍 Overview

This project transforms **62,884 raw sales transactions** into a fully interactive, multi-page Power BI dashboard. It is designed to help business leaders and analysts make fast, data-driven decisions across sales, products, customers, and store operations.

The dataset covers a global electronics retailer operating across **Australia, Canada, France, Germany, Italy, Netherlands, United Kingdom, and the United States**, with both physical stores and an online channel.

---

## 🚨 Business Problems Solved

### 1. 📍 "Where is our revenue coming from — and are we too dependent on one market?"
The United States alone drives **52% of total revenue ($30M)**. This level of dependency is a business risk. If the US market slows, the entire business is affected.

> **Action Recommended:** Accelerate investment in growing markets like UK and Germany which together contribute $15M and show strong potential.

---

### 2. 📦 "Which products and categories should we focus on — and which should we drop?"
- **Computers = 34.64% of all revenue ($19.9M)** — the clear priority category
- **Games & Toys = only 1.3% ($0.75M)** — barely contributing to the business
- Desktops are the single highest-grossing subcategory at **$10.3M**

> **Action Recommended:** Double down on Computers and Home Appliances. Consider running promotions on underperforming categories like Games & Toys or evaluate discontinuing them.

---

### 3. 🌐 "Is our online channel growing fast enough?"
Online sales represent only **20.28% ($11.67M)** of revenue vs. 79.72% for physical stores. In 2019, revenue peaked. The 2020 drop (COVID) likely accelerated online demand but the data shows the channel was already underdeveloped.

> **Action Recommended:** Invest in ecommerce infrastructure, digital marketing, and online-exclusive promotions to grow the online share above 30%.

---

### 4. 🏪 "Which stores are worth keeping — and which are underperforming?"
Using **Revenue per Square Meter** as an efficiency metric:
- **US stores lead at $626/sqm** — most efficient
- **Australian stores lag at $163/sqm** — significantly underperforming
- Netherlands at $295/sqm also warrants review

> **Action Recommended:** Audit low-efficiency stores for restructuring, downsizing, or closure. Reinvest in high-performing US and UK locations.

---

### 5. 👥 "Who are our most valuable customers and how do we retain them?"
- **Top customer (Matthew Flemming) spent $61,871** — nearly 3x the next customer
- **Customer Retention Rate = 61.18%** — meaning 39% of customers never return
- **65+ age group generates $22.9M** — the highest spending segment despite likely being overlooked

> **Action Recommended:** Launch a VIP loyalty programme targeting top spenders. Create targeted marketing campaigns for the 65+ demographic. Investigate why retention is below 65%.

---

### 6. 📅 "Why did revenue drop so sharply after 2019?"
Revenue peaked at **$19M in 2019** then dropped **49.1% in 2020** — clearly COVID-19 impact. The YoY growth shows recovery was beginning in 2021 before data ends.

> **Action Recommended:** Analyse which categories recovered fastest post-COVID and replicate those strategies across slower-recovering ones.

---

### 7. 🚚 "Are our delivery operations performing consistently?"
- **Average delivery = 4.5 days** globally
- **Italy leads at 4.8 days**, Australia is fastest at 4.3 days
- **Undelivered orders (Return Rate) peaked in 2019 at 16.9K** — the same year revenue peaked, suggesting fulfilment was under strain

> **Action Recommended:** Investigate the 2019 delivery failure spike. Review logistics partners in Italy and Canada where delivery times are highest.

---

## 💡 Key Insights

| # | Insight |
|---|---|
| 1 | US market is over-relied upon — 52% revenue concentration is a strategic risk |
| 2 | Computers alone drive 35% of revenue — high dependency on one category |
| 3 | 65+ customers are the highest-spending age group at $22.9M — an underserved segment |
| 4 | Online channel is significantly underdeveloped at only 20% of revenue |
| 5 | Adventure Works is the top brand at $12.3M — nearly 10% more than second place Contoso |
| 6 | Revenue grew 157% from 2016 to 2019 — strong growth trajectory pre-COVID |
| 7 | Profit margin is consistently high at 58.6% — healthy business fundamentals |
| 8 | 39% of customers don't return — retention improvement could significantly boost revenue |
| 9 | Australian stores are the least efficient per square meter — restructuring opportunity |
| 10 | Undelivered orders spiked in 2019 — fulfilment couldn't keep up with demand growth |

---

## 📄 Dashboard Pages

| Page | Purpose | Key Visuals |
|---|---|---|
| **Executive Summary** | High-level overview for leadership | 6 KPI cards, Revenue & Profit by Year, YoY Growth, Channel Split, Revenue by Country |
| **Sales & Revenue Analysis** | Deep dive into trends | Monthly Revenue Trend, Channel over Years, Revenue by Category & Brand |
| **Product Performance** | Product and category profitability | Scatter plot, Top 10 Subcategories, Top 10 Products table, Category share donut |
| **Customer Insights** | Customer demographics and behaviour | Revenue by Gender, Age Group, Country map, Top 10 Customers table |
| **Store Performance** | Physical store efficiency | Revenue per Sqm, Store map, Online vs In-Store by Year |
| **Insights** | Advanced analytics | Revenue Forecast, Customer Retention Rate, Avg Delivery Days, Return Rate Analysis |

---

## 📊 Key Metrics

| Metric | Value |
|---|---|
| 💰 Total Revenue | $57.53M |
| 💵 Total Profit | $33.70M |
| 📈 Profit Margin | 58.6% |
| 🛒 Total Orders | 26,326 |
| 👥 Total Customers | 15,266 |
| 🏪 Total Stores | 66 |
| 📦 Avg Delivery Days | 4.5 |
| 🔄 Customer Retention | 61.18% |
| 🌐 Online Revenue Share | 20.28% |
| 📅 Data Period | Jan 2016 – Feb 2021 |

---

## 🗄️ Data Model

Built as a **Star Schema** — industry standard for analytical dashboards:

```
                    ┌─────────────┐
                    │  Date Table │
                    └──────┬──────┘
                           │
┌──────────┐    ┌──────────▼──────────┐    ┌───────────────┐
│ Products │───▶│        Sales        │◀───│   Customers   │
└──────────┘    │    (Fact Table)     │    └───────────────┘
                │                     │
┌──────────┐    └──────────┬──────────┘    ┌───────────────┐
│  Stores  │───▶           │          ◀────│ Exchange_Rates│
└──────────┘               │               │  (via RateKey)│
                           │               └───────────────┘
```

**Key design decisions:**
- Exchange Rates linked via a **composite RateKey** (Date + Currency) — workaround for Power BI's single-column relationship limitation
- Separate **Date Table** marked as official date table to enable Time Intelligence DAX functions
- All measures stored in a dedicated **`_Measures`** table for clean organisation

---

## 🧮 DAX Measures

| Measure | Description |
|---|---|
| `Total Revenue USD` | SUMX with multi-currency conversion via exchange rates |
| `Total Cost USD` | SUMX with cost and exchange rate |
| `Total Profit USD` | Revenue minus Cost |
| `Profit Margin %` | Profit divided by Revenue |
| `Total Orders` | DISTINCTCOUNT of Order Numbers |
| `Total Customers` | DISTINCTCOUNT of CustomerKeys |
| `Avg Order Value` | Revenue divided by Orders |
| `Avg Delivery Days` | AVERAGEX on delivered orders only |
| `YoY Revenue Growth %` | SAMEPERIODLASTYEAR time intelligence |
| `Revenue Online` | CALCULATE filtered to StoreKey = 0 |
| `Revenue In-Store` | CALCULATE filtered to StoreKey ≠ 0 |
| `Online Revenue %` | Online divided by Total Revenue |
| `Revenue per Sqm` | In-Store Revenue divided by Square Meters |
| `Total Stores` | COUNTROWS excluding online |
| `Customer Retention Rate` | Customers with more than 1 order |
| `Monthly Revenue` | DATESMTD monthly aggregation |

---

## 🛠️ Tools & Techniques

| Tool/Technique | Usage |
|---|---|
| **Power BI Desktop** | Dashboard development |
| **Power Query (M)** | Data cleaning and transformation |
| **DAX** | All custom measures and calculated columns |
| **Star Schema** | Data modelling approach |
| **Time Intelligence** | YoY growth, MTD calculations |
| **Multi-currency conversion** | Exchange rate integration |
| **AI Forecasting** | Built-in Power BI revenue forecasting |
| **Composite Key** | RateKey workaround for multi-column relationships |

---

## 📁 Data Sources

| File | Records | Description |
|---|---|---|
| `Sales.csv` | 62,884 rows | Transaction records with order details |
| `Products.csv` | 2,517 rows | Product catalogue with pricing |
| `Customers.csv` | 15,266 rows | Customer demographics |
| `Stores.csv` | 67 rows | Store locations and sizes |
| `Exchange_Rates.csv` | 11,215 rows | Daily currency rates (USD, CAD, AUD, EUR) |
| `Data_Dictionary.csv` | — | Field descriptions for all tables |

**Currencies covered:** USD · CAD · AUD · EUR

---

## 🚀 How to Use

1. **Download** `Electronics_Sales.pbix` from this repository
2. **Open** in Power BI Desktop (free download from Microsoft)
3. Data is fully embedded — **no additional setup needed**
4. Use the **navigation bar** at the top to switch between pages
5. Use **slicers** to filter by:
   - 📅 Year
   - 🌍 Country
   - 📦 Category
   - 🏷️ Brand
   - 👤 Gender

> ⚠️ **Note:** Map visuals require internet connection to load Bing Maps tiles.

---

## 🔮 Future Improvements

Here are additional features and analyses that could make this dashboard even more powerful:

### 📊 Additional Analyses
- [ ] **Profit trend by category over time** — identify which categories are becoming less profitable year on year
- [ ] **Customer Lifetime Value (CLV)** — predict how much each customer segment will spend over time
- [ ] **Market basket analysis** — which products are frequently bought together
- [ ] **Seasonal trends** — identify peak buying months per category
- [ ] **Price elasticity analysis** — how does pricing affect sales volume

### 🔧 Technical Improvements
- [ ] **Row-level security (RLS)** — restrict data access by region or role
- [ ] **Incremental refresh** — for handling larger and more frequent data updates
- [ ] **Power BI Service deployment** — publish to cloud for web access and scheduled refresh
- [ ] **Mobile layout** — optimised view for phone and tablet
- [ ] **Bookmarks & drill-throughs** — deeper navigation between pages
- [ ] **What-if parameters** — simulate price changes or discount scenarios

### 📡 Data Enhancements
- [ ] **Returns/refunds data** — actual return rate, not just undelivered orders
- [ ] **Marketing spend data** — connect revenue to advertising campaigns
- [ ] **Competitor pricing data** — benchmark against market
- [ ] **Customer satisfaction scores** — NPS or review data
- [ ] **Inventory data** — stock levels and stockout analysis
- [ ] **Employee/salesperson data** — performance by sales rep

### 🎨 Design Improvements
- [ ] **Custom theme file (.json)** — branded colour palette
- [ ] **Tooltip pages** — rich hover-over detail panels
- [ ] **Custom visuals** — from Power BI AppSource marketplace
- [ ] **Animated transitions** — using bookmarks for storytelling

---

## 👤 Author

**Rajdeep Ghosh**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/yourusername)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/yourusername)

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this project useful, please consider giving it a star!**
