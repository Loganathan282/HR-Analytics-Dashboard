# 📊 HR Analytics Dashboard — Attrition Analysis

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Domain](https://img.shields.io/badge/Domain-Human%20Resources-blue?style=flat)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)

## 📌 Project Overview

This project is an interactive **HR Attrition Analysis Dashboard** built using **Power BI**. It analyzes employee attrition patterns across an organization of 1,480 employees, identifies key risk factors, and provides actionable insights to help HR teams reduce turnover.

---

## 🎯 Objective

- Identify **who is leaving** the organization and why
- Discover **key drivers** of employee attrition
- Analyze the impact of **tenure, salary, overtime, and promotions** on attrition
- Help HR decision-makers take **data-driven retention actions**

---

## 📂 Dataset

| Detail | Info |
|--------|------|
| Source | IBM HR Analytics Employee Attrition Dataset |
| Records | 1,480 employees |
| Features | 35 columns (age, salary, tenure, job role, department, etc.) |
| Type | Public dataset (Kaggle) |

---

## 📊 Dashboard Pages

### Page 1 — Attrition Overview
> *Who is leaving and where are they from?*

- Attrition by **Age Group, Gender, Marital Status**
- Attrition by **Job Role and Department**
- Key finding: Single employees aged 18–25 and Sales Representatives show highest attrition

### Page 2 — Attrition Drivers & Insights
> *Why are they leaving?*

- Attrition by **Salary Slab, Overtime, Job Level**
- **Tenure vs Attrition** and **Promotion Gap vs Attrition**
- Key finding: Low salary + overtime + no promotion = highest attrition risk

---

## 🔑 Key KPIs Tracked

| KPI | Value |
|-----|-------|
| Total Employees | 1,480 |
| Active Employees | 1,242 |
| Inactive Employees | 238 |
| Attrition Rate | 16.08% |
| Average Salary | $6.50K |
| Average Tenure | 7.01 years |
| Average Salary Hike | 15.21% |
| High Risk Employee Count | 31 |

---

## 💡 Key Insights

1. **Salary is the top driver** — Employees earning below $5K account for the highest attrition volume (737 out of 1,480)
2. **Overtime triples attrition risk** — Employees doing overtime show 30.6% attrition vs 10.4% for non-OT employees
3. **Entry-level employees are most vulnerable** — Job Level 1 has 26% attrition rate
4. **New joiners are unstable** — Employees with 0–2 years tenure show 29% attrition
5. **Promotion gap matters** — Employees not promoted within 2 years show the highest churn
6. **Sales department is most at risk** — Sales Representatives top the attrition list at ~40%
7. **Single employees aged 18–25** show the highest attrition among demographic groups

---

## 🛠️ Tools & Skills Used

- **Power BI Desktop** — Dashboard design, DAX measures, interactive visuals
- **DAX** — Calculated columns and measures (Attrition Rate, High Risk Count, etc.)
- **Data Modeling** — Relationships and data transformation in Power Query
- **Data Visualization** — Bar charts, donut charts, KPI cards, slicers

---

## 📸 Dashboard Screenshots

### Attrition Overview
![Attrition Overview](screenshots/attrition_overview.png)

### Attrition Drivers & Insights
![Attrition Drivers](screenshots/attrition_drivers.png)

---

## 🚀 How to Use

1. Download the `.pbix` file from this repository
2. Open it in **Power BI Desktop** (free download from Microsoft)
3. Explore the two dashboard pages using the navigation tabs
4. Use slicers to filter by department, gender, or job role

---

## 📁 Repository Structure

```
hr-analytics-dashboard/
│
├── HR_Analytics_Dashboard.pbix     # Power BI dashboard file
├── HR_Employee_Data.csv            # Dataset used
├── README.md                       # Project documentation
└── screenshots/
    ├── attrition_overview.png
    └── attrition_drivers.png
```

---

## 👤 Author

**LOGANATHAN.R**
- 🎓 Fresher | Aspiring HR Analyst
- 💼 LinkedIn: www.linkedin.com/in/lr735
- 📧 Email: loganathan73582@gmail.com

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

> ⭐ If you found this project helpful, please give it a star!
