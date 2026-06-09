# 📊 Business Sales Data Analysis
### Future Interns Data Science Track — Task 01

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-lightblue?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Project Overview

This project analyzes business sales data to uncover actionable insights across revenue trends, product performance, category contribution, and regional growth. The goal is to help business stakeholders make data-driven decisions through clean visualizations and KPI reporting.

---

## 🎯 Objectives

- Identify monthly and quarterly **revenue trends**
- Discover **top-selling products** by revenue
- Analyze **high-value categories** and their contribution
- Evaluate **regional performance** across North, East, West, South, and Central
- Calculate key business **KPIs** — revenue, profit, margin, and average order value

---

## 📁 Repository Structure
FUTURE_DS_01/
│
├── Task_01_Sales_Analysis/
│   ├── sales_analysis.ipynb
│   ├── sales_data.csv
│   └── outputs/
│       ├── Sales_Analysis_Report.html
│       ├── category_summary.csv
│       └── (6 chart PNGs)
│
├── Task_02_Churn_Analysis/
│   ├── churn_analysis.ipynb
│   ├── customer_data.csv
│   └── outputs/
│       ├── Churn_Analysis_Report.html
│       ├── retention_summary.csv
│       └── (6 chart PNGs)
│
├── Task_03_Marketing_Funnel/
│   ├── funnel_analysis.ipynb
│   ├── data/funnel_data.csv
│   └── outputs/
│       ├── Funnel_Analysis_Report.html
│       ├── funnel_summary.csv
│       └── (6 chart PNGs)
│
└── README.md

---

## ✅ Task 01 — Business Sales Data Analysis

### 📌 Objective
Analyze business sales data to identify revenue trends, top-selling products,
high-value categories, and regional performance.

### 🛠️ Tools Used
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

### 📊 Key KPIs

| Metric | Value |
|--------|-------|
| 💰 Total Revenue | $4.82M |
| 📦 Total Units Sold | 12,340 |
| 🧾 Avg Order Value | $390 |
| 📈 Gross Margin | 34.1% |

### 🔍 Key Insights
- **Electronics** is the top category with **38% revenue share**
- **North region** leads with **+25.7% YoY growth**
- **Q4** drives **31% of annual revenue** — strong seasonal trend
- **ProBook 15 Laptop** is the single highest-revenue product
- **West region** shows margin pressure despite revenue growth
- **Sports category** underperforms at 3.1% vs 18.4% company average

### 📂 Deliverables
- ✅ 6 publication-quality charts
- ✅ KPI summary CSV
- ✅ Full HTML analysis report
- ✅ Reproducible Jupyter Notebook

### 🔗 Task Folder
[`Task_01_Sales_Analysis/`](./Task_01_Sales_Analysis/)

---

## ✅ Task 02 — Customer Retention & Churn Analysis

### 📌 Objective
Analyze customer data to identify churn patterns, key retention drivers,
and customer lifetime trends for a subscription-based business.

### 🛠️ Tools Used
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

### 📊 Key KPIs

| Metric | Value |
|--------|-------|
| 👥 Total Customers | 50 |
| ✅ Active Customers | 28 |
| ❌ Churned Customers | 22 |
| 📉 Overall Churn Rate | 44% |
| ⏱️ Avg Tenure | 7.2 months |
| 💰 Avg Customer LTV | $312 |

### 🔍 Key Insights
- **Basic plan** has the highest churn rate (~70%) — price-sensitive segment
- **High support tickets (6+)** strongly correlate with churn
- **Inactive users** (45+ days since login) are most likely to churn
- **Premium plan** retains best — higher engagement and perceived value
- **Months 0–6** are the highest churn risk window for all plans
- **North region** has the best retention rate across all plans

### 📂 Deliverables
- ✅ Cohort retention heatmap
- ✅ Retention curves by plan
- ✅ Churn driver analysis charts
- ✅ CLV comparison (Active vs Churned)
- ✅ Retention summary CSV
- ✅ Full HTML analysis report

### 🔗 Task Folder
[`Task_02_Churn_Analysis/`](./Task_02_Churn_Analysis/)

---

## ✅ Task 03 — Marketing Funnel & Conversion Performance Analysis

### 📌 Objective
Analyze marketing funnel data to identify conversion drop-offs, channel
performance, and opportunities to improve lead-to-customer conversion.

### 🛠️ Tools Used
Python · Pandas · Matplotlib · Seaborn · Jupyter Notebook

### 📊 Key KPIs

| Metric | Value |
|--------|-------|
| 🎯 Total Leads | 34,285 |
| 👥 Total Customers | 2,530 |
| 📈 Overall Conv. Rate | 7.38% |
| 💰 Total Revenue | $4.6M |
| 💸 Total Ad Spend | $542K |
| 📊 Overall ROI | 748% |
| 💵 Avg Cost Per Lead | $15.81 |
| 🧾 Avg Cost Per Customer | $214 |

### 🔍 Key Insights
- **Paid Ads** drives the highest revenue but also highest cost per customer
- **Referral channel** has the best conversion rate with lowest cost per lead
- **Leads → Prospects** is the biggest drop-off stage (~40% lost here)
- **SQL → Opportunity** stage needs attention — significant drop-off
- **Age group 25–34** converts best across all channels
- **Q4 (Oct–Dec)** shows the strongest lead volume and conversion spike

### 📂 Deliverables
- ✅ Full funnel visualization
- ✅ Stage-by-stage drop-off analysis
- ✅ Channel performance & ROI comparison
- ✅ Conversion heatmap (Channel × Age Group)
- ✅ Monthly trend analysis
- ✅ Funnel summary CSV
- ✅ Full HTML analysis report

### 🔗 Task Folder
[`Task_03_Marketing`](./Task_03_Marketing)

---

## 🚀 How to Run Any Task

```bash
# 1. Clone the repository
git clone https://github.com/shreyadav14/FUTURE_DS_01

# 2. Install dependencies
pip install pandas matplotlib seaborn jupyter

# 3. Navigate to any task folder
cd Task_01_Sales_Analysis   # or Task_02 / Task_03

# 4. Launch Jupyter Notebook
jupyter notebook

# 5. Open the .ipynb file and run Kernel → Restart & Run All
```

---

## 🛠️ Tech Stack

| Library | Version | Purpose |
|---------|---------|---------|
| Python | 3.x | Core language |
| Pandas | Latest | Data manipulation |
| Matplotlib | Latest | Visualization |
| Seaborn | Latest | Statistical plots |
| Jupyter | Latest | Interactive notebooks |

---

*Submitted as part of the Future Interns Data Science Internship Program* 

---
