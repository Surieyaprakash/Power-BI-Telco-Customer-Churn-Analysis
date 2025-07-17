 📊 Telco Customer Churn Analysis – Power BI Dashboard

## 📌 Overview

This Power BI project focuses on analyzing customer churn patterns in a telecom company using an 80-record dataset. The goal is to identify key factors influencing churn, calculate lost revenue, and provide actionable insights to improve customer retention.

---

## 🗂️ Dataset Description

- **File:** `telco_customer_churn_80rows.csv`
- **Records:** 80 customers
- **Key Columns:** 
  - `gender`, `contract`, `tenure`, `monthly charges`, `total charges`
  - `paymentmethod`, `internetservice`, `streamingtv`, `churn` (target variable)

---

## 📈 Key Visuals

The dashboard is divided into multiple insight-driven visuals:

- **KPI Cards** showing:
  - Churn Rate: **43.75%**
  - Churned Customers: **35**
  - Avg. Total Charges: **$2.19K**
  - Avg. Monthly Charges: **$62.20**
  - MRR Lost from Churn: **$2.04K**

- **Visualizations Include**:
  - Churn by Payment Method (Pie Chart)
  - Churn by Contract Type (Bar Chart)
  - Tenure vs Monthly Charges (Scatter Plot)
  - Churn by Streaming TV Usage
  - Sankey Diagram showing Gender → Contract → Tenure Flow
  - Key Influencers (ML Visual)
  - Churn Rate by Internet Service & Payment Method

---

## 💡 Insights

- **High Churn Rate**: Nearly 44%, indicating customer retention issues.
- **Payment Method Impact**: Customers using **Mailed Cheques** and **Electronic Cheques** have the highest churn rates.
- **Contract Type Matters**:
  - **Month-to-Month** contracts lead to higher churn.
  - **1-Year contracts** surprisingly show higher churn than **2-Year** ones.
- **Streaming Services**: Users without streaming TV tend to churn more.
- **Revenue Impact**:
  - Highest MRR loss is from **1-Year contracts** and **Bank Transfer** customers.

---

## 🛠️ Tools Used

- **Power BI Desktop**
- **Microsoft Excel / CSV**
- Visuals: Pie Charts, Bar Charts, Scatter Plots, ML Key Influencer, Sankey Diagram

---

## 🧠 Recommendations

- Promote **longer-term contracts** to reduce churn.
- Discourage or modernize **cheque-based payments**.
- Improve **digital engagement and billing systems**.
- Offer **retention incentives** for high-risk customers.
- Explore potential issues during **1-Year contract renewals**.

---

## 📂 How to Use

1. Open the `.pbix` file (not included here) in Power BI Desktop.
2. Import the dataset (`telco_customer_churn_80rows.csv`).
3. Refresh visuals and explore the interactive dashboard.
