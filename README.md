# 🚀 Cryptocurrency Market Analysis Dashboard | Power BI

Business Intelligence • Data Analytics • Financial Analytics • Interactive Dashboard • Power BI

---

## 📌 Project Overview

A professional and interactive **Power BI dashboard** developed to analyze cryptocurrency market behavior using historical market indicators and business intelligence techniques.

The dashboard transforms raw cryptocurrency data into actionable insights using:


✔ Market Capitalization Analysis

✔ Trading Volume Monitoring

✔ High–Low Price Tracking

✔ Symbol Performance Comparison

✔ Monthly Trend Exploration

✔ Quarter-Based Filtering

✔ Interactive Business Intelligence Visualizations


Designed for:

* Data Analysts
* Financial Analysts
* Crypto Researchers
* Traders
* Business Intelligence Professionals

---

## 🎯 Objective

The objective of this project is to simplify large-scale cryptocurrency market data into a visually intuitive analytics experience.

This dashboard enables users to:

* Identify market leaders
* Analyze liquidity and trading activity
* Track monthly market movements
* Compare cryptocurrency performance
* Explore market share distribution

---

## 📊 Dataset

Dataset Source:

https://drive.google.com/file/d/1K-3fkDyFidRlzW7-sU05pE6vQL0jQlkj/view

---

# 🏗 Dashboard Architecture

```text id="slsb7f"
Raw Crypto Dataset
        │
        ▼
Power Query
(Data Cleaning)
        │
        ▼
Data Modeling
(Relationships)
        │
        ▼
DAX Measures
        │
        ▼
Interactive Visualizations
        │
        ▼
Business Insights
```

---

# 📈 Dashboard Features

## 1. Executive KPI Panel

Provides a high-level market summary.

KPIs Included:

* Total High Value
* Total Low Value
* Market Volume
* Market Capitalization
* RankNow Score

Purpose:

Instant understanding of overall market conditions.

---

## 2. Symbol-Wise Trading Volume Analysis

Visual: Horizontal Bar Chart

Insights:

* Compare cryptocurrency trading activity
* Identify highly liquid assets
* Detect dominant market symbols

Example Symbols:

* BTC
* ETH
* USDT
* XRP
* BCH
* EOS

Business Value:

Higher trading volume often indicates greater market participation.

---

## 3. Slug-Wise Price Performance

Visual: Column Chart

Insights:

* Compare highest values across crypto projects
* Detect unusually strong performers
* Explore market outliers

Example Categories:

* bitcoin
* bit20
* project-x
* primalbase
* 42-coin

Business Value:

Highlights high-value crypto opportunities.

---

## 4. Monthly Market Trend Analysis

Visual: Line Chart

Insights:

* Monthly movement patterns
* Market growth cycles
* Volatility behavior
* Trend identification

Business Value:

Supports time-based investment analysis.

---

## 5. Market Share Distribution

Visual: Donut Chart

Insights:

* Relative contribution of each symbol
* Market dominance analysis
* Portfolio exposure understanding

Business Value:

Quick evaluation of market concentration.

---

## 6. Quarter-Based Dynamic Filtering

Visual: Interactive Slicer

Supported Filters:

* Q1
* Q2
* Q3
* Q4

Features:

✔ Dynamic dashboard updates
✔ Cross-filter interactions
✔ Comparative time analysis

Business Value:

Improves exploratory analytics.

---

# 📊 Example Business Questions Answered

* Which cryptocurrency dominates market volume?
* Which assets reached the highest valuation?
* How does market activity change over months?
* Which quarter shows peak performance?
* What is the overall market distribution?

---

# 🛠 Tech Stack

| Category        | Tools            |
| --------------- | ---------------- |
| Dashboard       | Power BI Desktop |
| Data Processing | Power Query      |
| Data Modeling   | DAX              |
| Visualization   | Power BI Visuals |
| Analytics       | Measures & KPIs  |

---

# 📂 Project Structure

```bash id="0ivd8l"
Cryptocurrency-Market-Analysis/
│
├── dashboard/
│     └── Cryptocurrency_Dashboard.pbix
│
├── assets/
│     ├── dashboard_preview.png
│     └── screenshots/
│
└── README.md
```

---

# 📌 Key DAX Metrics

```DAX id="0blv6r"
Total Market Cap =
SUM(Crypto[MarketCap])

Total Volume =
SUM(Crypto[Volume])

Highest Price =
MAX(Crypto[High])

Lowest Price =
MIN(Crypto[Low])

Average Rank =
AVERAGE(Crypto[RankNow])
```

---

# 💡 Insights Generated

✔ Market concentration patterns
✔ Volume-based asset comparison
✔ Price movement understanding
✔ Time-based market behavior
✔ Interactive financial exploration

---

# 📈 Future Enhancements

* Real-Time Crypto API Integration
* Live Power BI Service Deployment
* Forecasting Models
* Sentiment Analysis
* Portfolio Dashboard
* Automated Refresh Pipeline

---

# 👨‍💻 Author

### Abhishek Kumar Gupta

B.Tech CSE (AI & ML)

Data Analytics • Machine Learning • Business Intelligence

GitHub:
https://github.com/AbhishekKumarGuptaDev

---

# ⭐ Support

If you found this project useful:

⭐ Star the repository
📈 Share feedback
🚀 Fork & build upon it
