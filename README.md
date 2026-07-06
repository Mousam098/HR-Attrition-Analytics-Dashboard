# 📊 HR Attrition Analytics Dashboard

A complete, GitHub-ready **Power BI HR Analytics Project** focused on employee attrition analysis, workforce risk identification, and retention insights.

This project uses a reproducible **synthetic HR dataset** containing **1,470 employee records** with realistic patterns and deliberate correlations. The dashboard helps analyze why employees leave, which groups are at higher risk, and how much attrition may cost the organization.

---

## 📌 Project Overview

Employee attrition is one of the most important problems in workforce management. High attrition increases hiring cost, training cost, productivity loss, and business disruption.

This project analyzes employee data to answer key HR questions such as:

- Which employees are more likely to leave?
- What factors drive attrition?
- How does overtime impact attrition?
- Are new hires leaving faster than experienced employees?
- What is the estimated annual cost of attrition?
- Which active employees match the profile of past leavers?

The final output is a professional **Power BI dashboard** supported by clean data, documented DAX measures, Power Query transformation logic, and business insights.

---

## 🚀 Key Features

- 1,470-row synthetic HR dataset
- 17.0% attrition rate
- Reproducible data generation script
- Full data dictionary
- Power Query M transformation code
- Explained DAX measures
- Custom Attrition Risk Score model
- Business questions and insights
- Retention watch-list logic
- GitHub-ready project structure
- Step-by-step Power BI build guide

---

## 📊 Real Insights from the Dataset

The findings below are computed directly from the included CSV dataset:

| Insight Area | Finding |
|---|---|
| Overall Attrition | 17.0% attrition rate |
| Overtime Impact | Overtime employees leave at 23.5% vs 14.2% for non-overtime employees |
| New Hire Risk | Employees with ≤1 year tenure leave at 22.0% vs 13.8% for others |
| Estimated Cost | Estimated annual attrition cost is approximately $7.0M |
| Risk Watch-list | 31 active employees match the risk profile of past leavers |

---

## 🧠 Business Problem

The HR team needs to understand employee attrition patterns and identify employees who may be at risk of leaving.

The main business goals are:

- Reduce employee attrition
- Identify high-risk employee groups
- Understand key drivers of resignation
- Estimate financial impact of attrition
- Support proactive retention planning
- Build a data-driven HR decision-making dashboard

---

## 📁 Repository Structure

```text
HR-Attrition-Analytics-Dashboard/
│
├── data/
│   ├── hr_attrition_synthetic.csv
│   └── data_dictionary.md
│
├── scripts/
│   └── generate_data.py
│
├── powerbi/
│   ├── Power_Query_M_Code.md
│   ├── DAX_Measures.md
│   ├── Attrition_Risk_Score.md
│   └── Build_Guide.md
│
├── docs/
│   ├── Business_Questions.md
│   ├── Insights.md
│   └── GitHub_Push_Instructions.md
│
├── README.md
├── LICENSE
└── .gitignore
