# 🏪 Retail Audit Dashboard – Branch Performance & Risk Monitoring

## 🔍 Project Overview

This project presents a **Retail Audit Dashboard** designed to evaluate **branch-level performance, risk exposure, and operational health** across a retail network of **200 stores**.  
The dashboard provides both an **executive-level summary** and a **branch-level deep dive**, enabling stakeholders to identify underperforming branches, assess risk dimensions, and monitor performance trends over time.

The analysis is done  **at a Quarterly level**, with **quarter-over-quarter comparisons** to track changes in performance.


### Executive Summary View
![Retail Audit Executive Summary](Retail%20Audit%20Dashboard%20Screen%201.png)

### Branch Summary View
![Retail Audit Branch Summary](Retail%20Audit%20Dashboard%20Screen%202.png)

---

## 🎯 Business Objectives

- Monitor overall retail network health
- Identify high-risk and underperforming branches
- Track performance trends across quarters
- Evaluate branches across multiple audit dimensions
- Support proactive operational and governance decisions

---

## 📊 Executive Summary – Retail Network Overview

### Key Metrics
- **Overall Retail Network Score** 
- **Risk Distribution of Branches in the Retail Network** - **Low/Medium/High Risk Category**
- **Overall Audit Dimension Score across 4 Audit Dimensions**
- **Risk Distribution of Branches based on selected Audit Dimension** - **Low/Medium/High Risk Category**
- **Branch Level Overall Score, Audit Dimension Scores and Risk Category**

---

## 🧩 Audit Dimensions and Scoring Methodology

Each branch is evaluated across the following audit dimensions:

- **Governance**
- **Liquidity**
- **Operations**
- **Profitability**

- **Each of the Audit Dimensions get scored in a 0-3 score range and then a Risk Category(High/Medium/Low) is assigned based on the score**

- **Scoring Criteria**

For **High Risk Category**, the branch score across an **audit dimension(Governance/Liquidity/Operations/Profitability)** must be between **0-1.66**.
For **Medium Risk Category**, the branch score across an **audit dimension(Governance/Liquidity/Operations/Profitability)** must be between **1.66-2.33**.
For **Low Risk Category**, the branch score across an **audit dimension(Governance/Liquidity/Operations/Profitability)** must be between **2.34-3**.

- **Scoring and Risk Categorization at the Branch Level**

**Each of the 4 audit dimensions have their respective KPIs based on which the performance is evaluated.**
For **Governance -** **10 KPIs**, 
For **Liquidity -** **5 KPIs**, 
For **Operations -** **6 KPIs**, 
For **Profitability -** **8 KPIs**

**Each of the KPIs for an audit dimension are scored from 0-3 and the audit dimension score is arrived at by taking the average of the scores across the KPIs for that audit dimension. (Governance has 10 KPIs, so the Governance Score is the average of the scores of the 10 KPIs)**


**For each branch, each Audit Dimension is scored (0-3)** and categorized as **High, Medium, or Low**. **Then, the branch score is arrived at by taking the **average of the scores across the 4 audit dimensions** thereby providing a multidimensional view of branch risk and performance.** 


- **Scoring and Risk Categorization at an Overall Level(across the 200 branches in the Retail Network)**

**The Overall Governance, Liquidity, Operations and Profitability score is computed by taking the average of audit dimension scores for each of the dimension (Overall Governance Score = Sum of Governance Score across 200 branches/200)
and the Risk Categorization for the audit dimension (High/Medium/Low) is then done based on the score thresholds mentioned above.**

**The Overall Retail Network Score is then computed by taking the average of each of the 4 Overall Audit Dimension Scores and the corresponding Risk Category is assigned as well following the same scoring thresholds**


---

## 🚨 Critical Branch Identification

The dashboard highlights **critical branches** based on low or deteriorating scores across key dimensions.  
This enables targeted audits, operational interventions, and risk mitigation actions.

---

## 🏬 Branch Summary Dashboard View (Gives Branch Level Insights for each of the 200 Branches in the Retail Network)

### Key Metrics**
**Overall Branch Score**
**Branch Level Audit Dimension Score (Governance/Liquidity/Operations/Profitability)** 
**KPI Risk Category Distribution based on Selected Audit Dimension**
**KPI Level Scoring and Risk Categorization based on Selected Audit Dimension (Liquidity)**
---

## 🧠 Tools & Technologies

- Tableau – Dashboard development and visualization
- Retail audit scoring frameworks
- Alteryx - Scoring Calculation Automation
- Python - Data Manipulation
- Excel - Dataset

---

## 💼 Business Value

This dashboard enables retail leadership to:

- Detect underperforming branches early
- Prioritize audits and corrective actions
- Monitor governance and financial risk
- Improve operational efficiency
- Support data-driven expansion or consolidation decisions


---

