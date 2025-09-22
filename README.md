# Analysing the Ideological Partisanship of Fiscal Policies on Returns  
_Disaggregating Fiscal Policy by Ideological Partisanship: An Empirical Analysis of Conservative and Liberal Fiscal Policies (US) on S&P 500 Returns_ 🔍

## 📌 Project Overview
This project investigates whether disaggregating fiscal policy into **ideological partisan regimes** (Conservative vs. Liberal) provides a clearer understanding of how taxation and spending affect the **S&P 500**.  
Using a **Pooled Vector Autoregression (VAR) with Cholesky recursive ordering**, this study analyzes quarterly U.S. data from **1971–2013**.  

The motivation stems from Tavares & Valkanov (2003), who highlighted that taxation and spending shocks have opposing effects on equity markets, but their aggregated analysis left ideological differences unexplored.

---

## 🎯 Objectives
- Develop a **classification system** to identify Conservative and Liberal fiscal regimes using taxation, spending, redistribution, and macroeconomic context.  
- Measure the effect of fiscal shocks on S&P 500 returns under both regimes.  
- Compare whether **ideological orientation matters** for asset market responses.  

---

## ⚙️ Methodology
- **Model**: Pooled VAR with Cholesky recursive identification  
- **Data**: Quarterly U.S. data (1971–2013)  
  - Fiscal variables: taxation (% GDP), spending (% GDP)  
  - Controls: inflation, output growth, federal funds rate  
  - S&P 500 excess returns (Yahoo Finance)  
- **Classification**: Regimes identified as Conservative or Liberal based on unemployment, redistribution indices (Piketty dataset), and defense spending context.  
- **Validation**:  
  - Impulse Response Functions (IRFs)  
  - Forecast Error Variance Decompositions (FEVDs)  
  - Bootstrapped confidence intervals  
  - Robustness checks (different lags, variable reordering, additional controls)  

---

## 📊 Key Findings
- **Spending Shocks**  
  - Conservative regimes: long-run **positive effect** on S&P 500.  
  - Liberal regimes: short-run **negative effect**, converging to positive in the long run.  

- **Taxation Shocks**  
  - Conservative regimes: **initially positive**, then negative in the medium-to-long run.  
  - Liberal regimes: weaker and more ambiguous, generally **negative**.  

- **Variance Decompositions**  
  - In Conservative regimes, fiscal shocks explained **7–9%** of S&P 500 variation.  
  - In Liberal regimes, fiscal shocks were weaker (**2–5%**), while monetary policy shocks dominated (**~20%**).  

---

## 📚 Implications
- Ideological orientation **does matter** for how markets process fiscal shocks.  
- Conservative fiscal shocks (especially taxation) have more persistent market effects.  
- Liberal spending initially creates uncertainty (possibly due to crowding-out concerns) but converges to growth-supportive effects.  
- Supports the argument that **disaggregation by ideology clarifies fiscal policy impacts** on financial markets.  

---

## 🔮 Future Research
- Extend the dataset **beyond 2013** and include microdata on top income groups (0.1%, 0.01%).  
- Explore effects on other asset classes (government bonds, corporate bonds, ETFs).  
- Use **event study / Narrative VAR approaches** to capture market reactions to exact fiscal announcements.  

---

## 🏛️ Academic Context
- MSc Dissertation in Finance and Data Analytics, University of Stirling (2025).  
- Builds upon the foundational work of **Tavares & Valkanov (2003)** and expands by introducing ideological classification.

---

## 🤝 Get in Touch
If you’d like to discuss this project, collaborate, or exchange ideas on fiscal policy, econometrics, or financial markets, feel free to connect with me on **[LinkedIn](https://www.linkedin.com/in/lorcangourley/)**
