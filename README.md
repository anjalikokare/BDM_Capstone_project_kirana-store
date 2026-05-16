# 🏪 Data-Driven Sales & Inventory Optimization for a Rural Kirana Store

> BDM Capstone Project — IIT Madras BS Data Science Program

[![IIT Madras](https://img.shields.io/badge/IIT%20Madras-BS%20Data%20Science-blue)](https://study.iitm.ac.in)
[![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-green?logo=microsoftexcel)](https://microsoft.com/excel)
[![Python](https://img.shields.io/badge/Python-Pandas%20%7C%20Matplotlib-blue?logo=python)](https://python.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

---

## 📌 Project Overview

This is a real-world data analytics capstone project conducted for **Bhavana Provision General Store**, a rural B2C kirana shop located in **Pimpri Khurd, Taluka Mangrulpir, District Washim, Maharashtra**, owned by Mr. Sunil Surve (operating since 2015).

The project applies data-driven techniques to solve two core business problems:
1. **Poor cash flow** due to untracked credit transactions
2. **Inefficient inventory management** due to lack of structured sales analysis

---

## 🏪 About the Business

| Detail | Info |
|--------|------|
| Store Name | Bhavana Provision General Store |
| Location | Pimpri Khurd, Washim, Maharashtra |
| Owner | Mr. Sunil Surve |
| Est. | January 2015 |
| Type | B2C Rural Kirana Store |
| Annual Revenue | ₹10–12 Lakhs (approx.) |
| Products | Groceries, Cooking Oil, Pulses, Packaged Goods |

---

## 📊 Dataset Details

| Attribute | Value |
|-----------|-------|
| Total Records | 6,465 transactions |
| Total Sales | ₹6,34,657 |
| Amount Received | ₹3,76,798 |
| Pending Dues | ₹2,57,859 (40.6%) |
| Avg. Transaction | ₹98.17 |
| Median Transaction | ₹50 |

### Features in Dataset:
`Date` · `InvoiceID` · `CustomerName` · `ItemName` · `Category` · `Quantity` · `PricePerUnit` · `TotalAmount` · `PaymentMode` · `AmountPaid` · `PendingDues` · `Month`

---

## 🔍 Key Findings

### 1. 💸 Credit & Cash Flow
- **40.6% of total sales** remain unpaid as credit
- Only ₹3,76,798 received as actual cash — limits restocking ability
- Manual credit tracking makes recovery difficult

### 2. 📈 Sales Trends
- Peak sales in **November**, decline in January
- Essential items (rice, oil, flour) maintain **stable demand year-round**
- Non-essential packaged goods show **seasonal fluctuations**

### 3. 🏆 Top Products by Revenue
| Rank | Product | Type |
|------|---------|------|
| 1 | Groundnut Oil (1L) | Staple |
| 2 | Sunflower Oil (1L) | Staple |
| 3 | Tur Dal (Arhar) | Staple |
| 4 | Wheel Powder (1kg) | Household |
| 5 | Red Label Tea (100g) | Beverage |

### 4. 📦 ABC Inventory Classification
| Category | Items | Sales Contribution |
|----------|-------|-------------------|
| A (Fast-moving) | 20 items | **78.8%** of sales |
| B (Moderate) | 13 items | 16.1% of sales |
| C (Slow-moving) | 11 items | 5.1% of sales |

### 5. 👥 Customer Behaviour
- **57% Cash** / **43% Credit** transactions
- Majority of purchases in **₹0–50 range** (small, frequent purchases)
- Customers prefer daily small purchases over bulk buying

---

## 🛠️ Tech Stack & Tools

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Data entry, Pivot Tables, charts, dashboards |
| Python (Pandas) | Data cleaning, transformation, analysis |
| Matplotlib / Seaborn | Visualizations |
| NumPy | Numerical computations |

---

## 📋 Analysis Workflow

```
1. Data Collection
   └─ Digitized 6,465 handwritten store records into Excel

2. Data Cleaning & Preprocessing
   └─ Standardized product names, fixed missing values,
      removed duplicates, converted data types

3. Exploratory Data Analysis (EDA)
   └─ Descriptive stats, distribution analysis,
      payment mode analysis

4. Sales Trend Analysis
   └─ Monthly revenue patterns, seasonal demand

5. Product Profitability Analysis
   └─ Total profit vs profit margin per product
      (consistent 32%–36% margin range)

6. ABC Inventory Classification
   └─ Pareto analysis — top 20 items = 78.8% of sales

7. Customer Behaviour Analysis
   └─ Purchase frequency, credit patterns, pending dues

8. Sales Forecasting
   └─ Jan 2026 actual vs Feb 2026 forecasted comparison

9. Recommendations
   └─ 11 actionable business improvements
```

---

## 💡 Key Recommendations

1. **Reduce Credit Dependency** — Customer ledger, credit limits, cash discounts
2. **Fast-Moving Stock Management** — Keep 2–3 weeks buffer for Category A items
3. **Reduce Slow-Moving Investment** — Combo offers & discounts for Category C
4. **Implement ABC Classification** — Prioritize inventory by demand category
5. **Digital Credit Tracking** — Excel-based dues tracker with weekly follow-ups
6. **Sales Dashboard** — Excel Pivot Table dashboard for daily/monthly monitoring
7. **Demand-Based Purchasing** — Use historical data, not guesswork
8. **Better Product Placement** — High-demand items near counter
9. **Combo Offers** — Bundle slow movers with fast movers
10. **Weekly Review System** — Stock, dues, and sales tracked every week

---

## 📁 Project Structure

```
kirana-store-data-analysis/
│
├── BDM_Proposal_Report.pdf        # Initial proposal & problem statement
├── BDM_MidTerm_Report.pdf         # Midterm: data collection & EDA
├── BDM_Final_Report.pdf           # Final: complete analysis & recommendations
├── README.md                      # Project documentation
└── LICENSE                        # MIT License
```

---

## 📄 Project Reports

| Report | Description |
|--------|-------------|
| [`BDM_Proposal_Report.pdf`](BDM_Proposal_Report.pdf) | Problem statement, background, approach & timeline |
| [`BDM_MidTerm_Report.pdf`](BDM_MidTerm_Report.pdf) | Data collection, metadata, EDA & initial findings |
| [`BDM_Final_Report.pdf`](BDM_Final_Report.pdf) | Complete analysis, results & 11 recommendations |

---

## 🔗 Data Source

Original transaction data (handwritten registers → digitized Excel):
📁 [Google Drive — Supporting Evidence](https://drive.google.com/drive/folders/116h5_MviqgJ0XKVU8xHpdkw5FaKSRN7j?usp=sharing)

Includes: store photos, owner interaction video, scanned registers, confirmation letter, dataset

---

## 👩‍💻 Author

**Anjali Kokare**
- 🎓 BS Data Science & AI — IIT Madras (Roll: 24f2002015)
- 📍 Washim, Maharashtra, India
- 🔗 [LinkedIn](https://www.linkedin.com/in/anjali-kokare-645488382)
- 💼 Open to Data Science, Analytics & ML roles

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

> *This project was completed as part of the BDM (Business Data Management) Capstone course under the IIT Madras Online BS Degree Program.*
