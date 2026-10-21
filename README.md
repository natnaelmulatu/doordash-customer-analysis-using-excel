# DoorDash Customer Segmentation & Demographic Analysis

> **Executive Summary:** A data-driven analysis challenging common demographic assumptions in food delivery customer data. This project demonstrates how misinterpreting aggregated customer metrics (specifically age and income groupings) leads to misallocated marketing spend, and provides an actionable segmentation framework using Excel.

---

## 📌 Project Overview

Marketing teams frequently rely on high-level demographic averages to guide customer acquisition and retention strategies. However, relying on broad demographic buckets often creates a **"Demographics Trap"**—where key high-value sub-segments are hidden within skewed statistical averages.

This project analyzes DoorDash customer transaction and demographic data to:
1. **Uncover hidden trends** obscured by standard age and income averages.
2. **Evaluate customer order frequency, average order value (AOV), and retention rates** across granular demographic cohorts.
3. **Provide actionable recommendations** to optimize targeting and customer lifetime value (LTV).

📖 **Read the full write-up on LinkedIn:** [The $1M Demographics Trap: How Misreading Customer Age is Costing Delivery Platforms](https://www.linkedin.com/pulse/1m-demographics-trap-how-misreading-customer-age-costing-nate-mulatu-md8fe/)

---

## 🔑 Key Insights & Business Impact

* **The Demographic Fallacy:** Relying solely on average customer age masks critical bimodal distributions in purchasing behavior between younger, high-frequency buyers and older, high-AOV buyers.
* **AOV vs. Frequency Trade-off:** While younger cohorts drive transaction volume, mature demographic segments yield significantly higher basket sizes per order.
* **Optimization Opportunity:** Targeted messaging and tailored promo structures based on behavioral cohorting rather than broad age buckets can reduce customer acquisition cost (CAC) while boosting repeat purchase rates.

---

## 🛠️ Tools & Skills Demonstrated

* **Tool:** Microsoft Excel (Advanced Pivot Tables, Dynamic Formulas (`XLOOKUP`, `INDEX/MATCH`, `SUMIFS`), Data Validation, Conditional Formatting, Interactive Dashboards)
* **Data Analysis:** Exploratory Data Analysis (EDA), Demographic Segmentation, Behavioral Cohort Analysis, Descriptive Statistics
* **Business Intelligence:** Data Visualization, Dashboard Design, Executive Storytelling, Metric Definition (AOV, Order Frequency, Customer Lifetime Value indicators)

---

## 📂 Repository Structure

```text
├── data
│   ├── raw_doordash_data.xlsx       # Raw transaction & demographic dataset
│   └── analyzed_doordash_data.xlsx  # Cleaned and analyzed excel file
└── README.md                       # Project documentation
```

---

## 📊 Methodology & Analytical Process

1. **Data Cleaning & Preparation:**
   * Handled missing values, standardized data formats, and removed duplicates.
   * Calculated derived metrics including **Order Frequency**, **Total Revenue per User**, and **Custom Age/Income Brackets**.

2. **Exploratory Data Analysis (EDA):**
   * Segmented customers by age groups, income tiers, and ordering behavior.
   * Analyzed variance and distribution of Average Order Value (AOV) across cohorts.

3. **Dashboard Construction:**
   * Built dynamic pivot tables and charts linked via slicers (Age, Region, Order Volume).
   * Formatted metrics for executive presentation with a focus on quick insight retrieval.
