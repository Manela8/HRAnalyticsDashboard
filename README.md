# 👥 HR Analytics — Power BI Dashboard

## 📌 Project Overview

This project analyzes employee attrition data to help HR teams and management understand **why employees are leaving**, which departments and roles are most affected, and what salary, age and education patterns drive attrition — enabling data-driven retention strategies.

---

## 📂 Dataset

| Property | Details |
|----------|---------|
| **Total Employees** | 1,413 |
| **Total Attrition** | 229 |
| **Attrition Rate** | 16.2% |
| **Avg Age** | 37 years |
| **Avg Monthly Salary** | 6.5K |
| **Avg Years at Company** | 7.0 |
| **Departments** | Human Resources, Research & Development, Sales |

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Power BI** | Data modelling, DAX measures, interactive dashboard |
| **Excel** | Raw data source |

---

## 🗂️ Project Structure

```
hr-analytics-dashboard/
├── HR_Analytics.xlsx              # Raw dataset
├── HR_Analytics_Dashboard.pbix   # Power BI dashboard file
├── HR_Analytics_Dashboard.pdf    # Exported dashboard PDF
└── README.md
```

---

## 📊 Dashboard Overview

Single-page interactive dashboard with department slicers (Human Resources, Research & Development, Sales) featuring:

- **KPI Cards** — Total Employees, Attrition Count, Attrition Rate, Gender Split, Avg Age, Avg Salary, Avg Years
- **Attrition by Education** — Donut chart showing education field breakdown
- **Attrition by Age Group** — Bar chart across 5 age bands
- **Attrition by Salary Slab** — Horizontal bar chart by salary range
- **Attrition by Job Role** — Horizontal bar chart for top affected roles
- **Attrition by Years at Company** — Line chart showing tenure patterns
- **Job Satisfaction Matrix** — Rating (1-4) by Job Role with totals

---

## 💡 Key Findings

1. **16.2% attrition rate** — 229 out of 1,413 employees left, with male attrition (136) nearly double female (76), suggesting gender-specific retention issues worth investigating.

2. **Low salary is the biggest attrition driver** — 158 out of 229 employees who left (69%) earned under 5K/month, pointing to compensation as the primary retention lever.

3. **26-35 age group accounts for the highest attrition (111 employees)** — early-career professionals are the most at-risk segment, likely due to better external opportunities.

4. **Laboratory Technicians (60), Sales Executives (55) and Research Scientists (44) are the top 3 roles losing talent** — together accounting for 69% of total attrition.

5. **Life Sciences (38%) and Medical (25%) graduates make up 63% of attrition** — despite being the most educated segments, suggesting dissatisfaction beyond compensation alone.

---

## 📋 Business Recommendations

- **Review compensation** for sub-5K salary band — majority of attrition is concentrated here
- **Target retention programs** at Laboratory Technicians and Sales Executives — highest attrition roles
- **Focus on 26-35 age group** with career development and growth opportunities
- **Investigate Life Sciences and Medical graduate dissatisfaction** — may be role-fit or growth related
- **Gender-specific retention analysis** — male attrition is disproportionately high

---
