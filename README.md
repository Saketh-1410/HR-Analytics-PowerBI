# HR Analytics Dashboard — Power BI

An interactive Power BI dashboard that analyses workforce data to help HR teams monitor employee attrition, headcount trends, satisfaction levels, and departmental performance — enabling data-driven decisions around talent retention.

---

## Problem Statement

High employee attrition is costly and disruptive. HR teams often lack a consolidated view of workforce metrics, making it hard to identify at-risk segments early. This dashboard centralises key HR data so leadership can:

- Identify departments and roles with elevated attrition rates
- Understand the demographic and tenure profiles of employees who leave
- Track job satisfaction and engagement scores over time
- Prioritise retention initiatives with supporting evidence

---

## Tools & Technologies

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Data modelling, DAX measures, report authoring |
| **DAX** | Calculated columns, KPI measures, dynamic filtering |
| **Power Query (M)** | Data cleaning and transformation |
| **Excel / CSV** | Source dataset |

---

## Dashboard Features

- **Attrition Overview** — overall attrition rate with trend line; sliced by department, age band, and gender
- **Headcount & Demographics** — active employee count broken down by age group, gender, education field, and job role
- **Satisfaction Analysis** — job satisfaction, environment satisfaction, work-life balance, and relationship satisfaction scores
- **Tenure & Promotion** — average years at company, years since last promotion, and distance-from-home distribution
- **Department Deep-Dive** — side-by-side comparison of attrition and satisfaction across departments
- **Interactive Slicers** — filter the entire report by department, job role, gender, marital status, and education level

---

## Key KPIs

| KPI | Description |
|---|---|
| Attrition Rate | % of employees who left during the period |
| Active Headcount | Total employees currently employed |
| Avg. Monthly Income | Mean salary across all active employees |
| Avg. Years at Company | Mean employee tenure |
| Job Satisfaction Score | Average self-reported satisfaction (1–4 scale) |
| High-Risk Segment | Job role / age band with the highest attrition |

> **Note:** Exact values are drawn from the embedded dataset inside `HR_Analytics_Dashboard.pbix`. Open the file in Power BI Desktop to see live figures.

---

## Dataset Description

The dashboard uses the IBM HR Analytics Employee Attrition & Performance dataset (publicly available), which contains anonymised records for **1,470 employees** across the following fields:

- Demographics: age, gender, marital status, education, distance from home
- Job details: department, job role, job level, business travel
- Compensation: monthly income, salary hike %, stock option level
- Engagement: job satisfaction, environment satisfaction, work-life balance, relationship satisfaction
- Attrition: binary flag indicating whether the employee left

No personally identifiable information (PII) is present in this dataset.

---

## How to Open the Dashboard

1. Download and install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free).
2. Clone or download this repository.
3. Open **`HR_Analytics_Dashboard.pbix`** in Power BI Desktop.
4. All data is embedded — no external data source connection is required.
5. Use the slicers on each page to explore different workforce segments.

---

## Repository Structure

```
HR-Analytics-PowerBI/
├── HR_Analytics_Dashboard.pbix   # Power BI report file (data embedded)
├── .gitignore                    # Excludes cache, temp, and credential files
└── README.md                     # Project documentation
```

---

## Author

**Pinnelli Shashank Reddy**
[GitHub](https://github.com/Saketh-1410)
