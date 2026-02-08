# HR Attrition Analysis 

## Business Objective
Analyze employee attrition patterns to identify key workforce segments and operational drivers contributing to exits, enabling HR teams to design targeted, data-driven retention interventions.

---

## Page 1 — Workforce & Attrition Overview

### Key Metrics & Calculations (Power BI / DAX)
- Calculated **Overall Attrition Rate**, **Early Attrition Rate**, and **Average Exit Tenure** using DAX measures.
- Segmented attrition by **Department, Age Group, Gender, and Tenure cohorts** using dimensional slicing.
- Built **department-level attrition distributions** to distinguish between attrition driven by headcount volume versus elevated exit risk.

### Key Insights
- Overall attrition stands at **16%**, with **early attrition (~5%)** indicating potential onboarding and expectation-alignment gaps.
- **Research & Development** shows the highest attrition volume, largely driven by its workforce size rather than disproportionate attrition risk.
- Attrition is concentrated in the **26–35 age group**, suggesting higher mobility among early-to-mid career employees.

---

## Page 2 — Attrition Drivers (Workload, Pay, Travel)

### Key Metrics & Calculations (Power BI / DAX)
- Created a **Pay Position** metric by benchmarking individual salary against **median compensation by Job Role and Job Level**.
- Bucketed **PercentSalaryHike** into bands to analyze non-linear compensation effects.
- Modeled attrition rates across **Overtime, Business Travel, Work-Life Balance (ordinal scale), and Pay Position** dimensions.

### Key Insights
- **Overtime emerges as a dominant attrition driver**, with overtime employees exhibiting materially higher exit rates than non-overtime peers.
- Employees **paid below their role-level median** show higher attrition, highlighting potential **internal pay equity risks**.
- **Frequent business travel** is strongly associated with increased attrition, while non-travel roles show the lowest exit rates.
- Lower **Work-Life Balance scores (1–2)** correlate with significantly higher attrition, reinforcing workload sustainability as a critical retention lever.
- Salary hikes alone demonstrate **limited protective impact**, indicating that compensation adjustments without workload correction are insufficient.

---

## Executive Summary
Attrition is primarily driven by **workload intensity and internal pay positioning**, rather than tenure stagnation alone. Employees facing overtime pressure, frequent travel, and below-median pay represent the highest retention risk and should be prioritized for targeted HR interventions.
