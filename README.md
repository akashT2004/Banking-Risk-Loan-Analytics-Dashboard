# 📊 Banking Risk & Loan Analytics Dashboard

## 📌 Project Overview

The **Banking Risk & Loan Analytics Dashboard** is an interactive Tableau dashboard developed to analyze banking loan data and provide insights into lending patterns, customer creditworthiness, loan distribution, and default risk.

The project helps banks and financial institutions monitor loan performance, identify high-risk customers, and support data-driven lending decisions through intuitive visualizations and KPIs.

---

## 🎯 Project Objectives

- Analyze total loan distribution across banks and states.
- Monitor customer credit score trends.
- Measure loan default rate.
- Identify the most common loan purposes.
- Track loan issuance over time.
- Compare customer income based on education and employment type.
- Provide an interactive dashboard for business users.

---

## 🛠️ Tools & Technologies

- **Python (Pandas, NumPy)** – Data Cleaning & Feature Engineering
- **Jupyter Notebook** – Data Preparation
- **Tableau Public** – Dashboard Development & Visualization
- **CSV Dataset** – Data Source

---

## 📂 Dataset Information

- **Source:** Kaggle Banking Loan Dataset
- **Total Records:** 255,347+
- **Original Columns:** 18
- **Enhanced Dataset:** 30+ Columns

### Additional Columns Created

- Customer ID
- Loan Date
- Loan End Date
- State
- City
- Bank Name
- Branch
- EMI
- Outstanding Balance
- Months Completed
- Loan Status
- Credit Score Band
- Age Group

---

## 🧹 Data Preparation

Data preprocessing was performed using Python before importing into Tableau.

### Tasks Performed

- Data cleaning
- Data type validation
- Feature engineering
- Added business-related attributes
- Created geographic information
- Created customer segmentation fields
- Exported cleaned dataset to CSV

---

## 📈 Dashboard KPIs

- Total Loans
- Total Loan Amount
- Average Credit Score
- Average Interest Rate
- Default Rate

---

## 📊 Dashboard Visualizations

- Loan Amount by Purpose (Bar Chart)
- Credit Score Band Distribution (Pie Chart)
- Loan Amount by Bank (Treemap)
- Loan Amount by State (Filled Map)
- Loan Trend Over Time (Line Chart)
- Average Income by Education & Employment Type (Highlight Table)

---

## 🎛️ Interactive Features

- State Filter
- Bank Name Filter
- Employment Type Filter
- Dynamic Tooltips
- Interactive Dashboard

---

## 📌 Tableau Concepts Used

- Dimensions & Measures
- Calculated Fields
- Aggregations (SUM, AVG, COUNT)
- Filled Maps
- KPI Cards
- Bar Charts
- Pie Charts
- Treemap
- Line Chart
- Highlight Table
- Filters
- Sorting
- Formatting
- Tooltips
- Geographic Roles
- Dashboard Design
- **FIXED LOD Expression**

### Example LOD Calculation

```tableau
{ FIXED [State] : AVG([Credit Score]) }
```

Used to display the average credit score of each state in the map tooltip.

---

## 📊 Business Insights

The dashboard answers key business questions such as:

- Which bank has issued the highest total loan amount?
- Which states receive the highest loan funding?
- What is the average customer credit score?
- What is the overall loan default rate?
- Which loan purposes are most common?
- How does customer income vary by education and employment type?

---

## 🚀 Business Benefits

- Supports lending decisions
- Identifies credit risk
- Monitors loan portfolio performance
- Understands regional lending trends
- Enables interactive business reporting
- Improves decision-making through data visualization

---

## 📁 Project Workflow

```
Kaggle Dataset
        │
        ▼
Python Data Cleaning & Feature Engineering
        │
        ▼
Enhanced CSV Dataset
        │
        ▼
Tableau Public
        │
        ▼
Interactive Banking Risk & Loan Analytics Dashboard
```


- Data Analytics | Python | SQL | Excel | Tableau | Power BI

---
