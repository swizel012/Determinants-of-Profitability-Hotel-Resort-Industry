# 🏨 Intrinsic Determinants of Profitability in the Hotel Resort Industry in India

## 📌 Overview
This project explores how intrinsic financial factors influence profitability in the Indian hotel resort industry. The study uses multiple linear regression to examine the impact of solvency, firm size, cash flow efficiency, and asset turnover on Return on Assets (ROA), based on data from 105 hotels between 1999 and 2024.

---

## 📂 Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Data & Methodology](#data--methodology)
- [Regression Model](#regression-model)
- [Model Diagnostics](#model-diagnostics)
- [Results](#results)
- [Conclusion](#conclusion)
- [Tools Used](#tools-used)
- [References](#references)

---

## 📖 Introduction
The Indian hotel industry is capital-intensive and highly competitive. Profitability is crucial for long-term survival and growth. This project focuses on firm-specific (intrinsic) factors to determine what truly drives profitability.

---

## ❓ Problem Statement
To identify and analyze intrinsic factors that influence profitability (ROA) in the hotel resort industry in India using secondary financial data.

---

## 📊 Data & Methodology
- **Source**: [Capitaline](https://awsone.capitaline.com)
- **Sample**: 105 Indian hotel resorts
- **Period**: 1999–2024
- **Analysis Tool**: EViews
- **Approach**: Multiple linear regression using the least squares method

### Variables:
- **Dependent Variable:**
  - ROA (Return on Assets)
- **Independent Variables:**
  - LFIRMSIZE (Log of Total Assets)
  - CFOR (Cash Flow to Operating Revenue Ratio)
  - NAT (Net Asset Turnover)
  - SOLVENCYRATIO (Solvency Ratio)

---

## 🔍 Regression Model

ROA = β₀ + β₁LFIRMSIZE + β₂CFOR + β₃NAT + β₄SOLVENCYRATIO + ε


Where:
- ROA: Return on Assets
- LFIRMSIZE: Log-transformed Firm Size
- CFOR: Cash Flow to Operating Revenue Ratio
- NAT: Net Asset Turnover
- SOLVENCYRATIO: Solvency Ratio

---

## 🧪 Model Diagnostics
- **R-squared**: 0.9492 (94.92% of variation in ROA explained)
- **Adjusted R-squared**: 0.9460
- **SE of Regression**: 72.21
- **Durbin-Watson**: 1.86 (no autocorrelation)
- **VIF values**: < 10 (no multicollinearity)
- **Breusch-Pagan Test**: Minor heteroskedasticity
- **Ramsey RESET Test**: Possible model misspecification detected

---

## 📊 Results
- **NAT (Net Asset Turnover)**: Only statistically significant factor (p < 0.05)
- **LFIRMSIZE, CFOR, SOLVENCYRATIO**: Not statistically significant
- Implication: Better asset utilization (NAT) leads to higher profitability.

---

## ✅ Conclusion
- Profitability in the hotel resort industry is primarily driven by **efficient asset usage**.
- Firm size, cash flow, and solvency don't significantly influence ROA.
- **Strategic focus** should be on optimizing asset turnover (e.g., increasing room occupancy, improving service utilization).

---

## 🛠️ Tools Used
- [EViews](https://www.eviews.com/)
- Microsoft Excel (for data preparation)
- Capitaline Database


---
