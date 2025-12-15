# 📊 Loan Portfolio Risk Analysis Dashboard (Excel)

An interactive **Excel dashboard** built to analyze a large loan portfolio, uncover risk drivers, explore borrower behavior patterns, and highlight key performance metrics — empowering lenders with actionable insights for loan approvals, pricing strategies, and credit risk mitigation.

---

## 🖼️ Dashboard Preview

Risk Analysis Dashboard

![Risk Analysis Dashboard](Screenshot/risk_analysis_dashboard.png)

---

## 📌 Project Overview

This dashboard explores the risk profile of over **70,000 loan records**, enabling data-driven decision-making for underwriting and portfolio management. It brings together key risk metrics, borrower behavior patterns, and segmented loan performance into a consolidated interactive interface.

---

## 🧾 About the Data

- **Records:** 70,000+ loans
- **Key Attributes:**
  - Loan amount & purpose
  - Interest rate
  - Annual income
  - Credit score (FICO)
  - Debt-to-Income (DTI) ratio
  - Loan status
  - Term & installment
  - Issue date

The dataset was cleaned and enhanced with engineered features such as:
- **Risk Category**
- **Installment-to-Income Ratio**
- **Loan Profitability**
- **Behavioral Segments** based on DTI and loan purpose

---

## ⚙️ Preprocessing Workflow

- Cleaned missing values and standardized financial metrics
- Normalized borrower attributes for comparative analysis
- Engineered analytical features (e.g., Risk Buckets)
- Segmented borrowers using DTI and loan characteristics
- Performed ETL using **Python**, and built the interactive dashboard using **Excel**

---

## 📊 Dashboard Highlights

This Excel dashboard enables interactive exploration of:

### 📍 Key KPIs
- **Total Loans:** 70,000+
- **Total Loan Amount:** ₹ 98,44,19,675
- **Average Interest Rate:** 13.69%
- **Historical Default Rate:** 12.81%
- **Risk-Adjusted Return (RAR):** 0.88%

### 📈 Visualizations Include
- Loan status breakdown (Good vs Bad loans)
- Default rate by DTI category
- Default trend by loan grade and year
- Risk rate by loan purpose (radar chart)
- Region-wise default rate
- Year and grade slicers for ad-hoc filtering

---

## 🔍 Actionable Insights

1. **Portfolio Default Risk**  
   The overall default rate stands at **12.81%**, with **small business** and **debt consolidation** loans showing the highest risk.

2. **Risk-Adjusted Return**  
   A **RAR of 0.88%** indicates tight margins and highlights opportunities to optimize pricing strategies.

3. **Debt-to-Income (DTI) Influence**  
   Borrowers with **DTI > 40%** exhibit a **2–2.5× higher likelihood of default** compared to lower DTI segments.

4. **Credit Score Impact**  
   Loans issued to borrowers with **FICO < 680** account for **~60% of total defaults**, signaling credit quality concerns.

5. **Purpose-Based Performance**  
   Loans for **medical purposes** show the **lowest default risk** and the best repayment behavior among segments.

---

## 📌 Key Results

- Processed **70,000+ loan records** into an interactive Excel dashboard
- Identified high-risk borrower segments and risk concentrations
- Demonstrated correlation between borrower behavior and default outcomes
- Built a **risk framework** to support underwriting adjustments and pricing optimization

---

## 📥 How to Use

1. Download the Excel file (`.xlsx`)
2. Open it in **Microsoft Excel**
3. Use the slicers and filters to explore the data interactively:
   - Year
   - Loan Grade
   - Purpose
   - Region
   - DTI segments

> Tip: Enable filters and slicers for dynamic pivot table interaction

---
