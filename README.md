# HR Attrition Analytics Dashboard
### Power BI · SQL · Excel



## Project Overview

Analyzed HR data for TechIT Solutions — a service-based IT company with 10,000 employees across finance, healthcare, and retail sectors — to identify root causes of a 22.47% attrition rate affecting project delivery and team stability. Built an interactive Power BI dashboard answering 10 business questions across departments, job roles, and company policies to enable data-driven retention strategies.

---

## Key Metrics

| Metric | Value |
|---|---|
| Total Employees | 10,000 |
| Total Attrition | 2,247 |
| Active Employees | 7,753 |
| Attrition Rate | 22.47% |
| Average Employee Age | 40 years |
| Departments Tracked | 5 |
| Business Questions Answered | 10 |

---

## Business Problem

TechIT Solutions was experiencing increasing employee attrition with no clear visibility into the root causes. The analysis was scoped around 10 business questions:

1. What is the overall attrition rate?
2. Which departments are facing the highest attrition and why?
3. How does job role influence attrition rates?
4. Is there a correlation between distance from home and attrition rate?
5. Is overtime contributing to higher attrition?
6. How do job satisfaction and environment satisfaction affect employee retention?
7. Are employees with low work-life balance scores more likely to quit?
8. Are employees with frequent business travel more likely to leave?
9. Does the number of years in the same role correlate with the likelihood of leaving?
10. Are salary hikes influencing employee retention effectively?

---

## Dashboard Preview

![HR Attrition Dashboard]("")

---

## Key Insights (Quantified)

### Attrition by Overtime
- Employees working overtime account for **35.5% of total attrition (798 employees)**
- Non-overtime employees account for 64.5% (1,449 employees)
- Indicates burnout as a significant attrition driver

### Attrition by Department
| Department | Attrition Count | % of Total Attrition |
|---|---|---|
| Cyber Security | 503 | 22.4% |
| Software Development | 462 | 20.6% |
| Data Science | 442 | 19.7% |
| IT Services | 430 | 19.1% |
| Network Administration | 410 | 18.2% |

### Attrition by Business Travel
- Travel Frequently: **690 employees (31%)** — highest attrition group
- Travel Rarely: second highest attrition segment
- No Travel: 375 employees (17%) — lowest attrition

### Attrition by Tenure (Years in Role)
- **Year 1: 208 employees** — highest attrition of any tenure band
- Year 2: 190 employees
- Year 5: 227 employees — secondary peak
- Year 7: 221 employees
- Insight: Early-tenure employees and mid-career stagnation are two distinct risk points

### Attrition by Salary Hike
- Employees receiving **0–10% hike: 241 attritions** — highest band
- Hike bands from 11–100% show relatively stable attrition (200–228 range)
- Salary hike alone does not prevent attrition uniformly across bands

### Attrition by Education
| Education Level | Attrition Count |
|---|---|
| Graduation | 702 |
| Degree | 686 |
| Master's | 438 |
| PhD | 221 |
| Below College | 200 |

### Job Satisfaction (Scale 1–5)
- Score 1 (lowest): **545 employees left** — highest dissatisfaction group
- Score 2: 541 employees
- Scores 3–5 show progressively lower attrition

### Work-Life Balance (Scale 1–5)
- Score 2: **628 employees** — highest attrition bucket
- Score 1: 604 employees
- Low work-life balance scores (1–2) collectively account for the majority of attrition

---

## Why It Matters (Business Impact)

| Problem (Before) | Insight (After Analysis) |
|---|---|
| Loss of talent and high costs | Identified top 2 departments driving 43% of attrition |
| No visibility into drivers | Overtime and early tenure pinpointed as primary risk factors |
| Generic HR initiatives | Data now supports targeted, department-level retention policies |

---

## Tech Stack

| Tool | Purpose |
|---|---|
| Power BI Desktop | Interactive dashboard, DAX measures, slicers, KPI cards |
| MySQL | Data querying, aggregation, business question analysis |
| Microsoft Excel | Initial data cleaning, exploratory data analysis |

---

## Dashboard Features

- **KPI Cards** — Total Employees, Total Attrition, Active Employees, Attrition Rate, Avg Age
- **Satisfaction Slicers** — Job Satisfaction, Job Environment, Work Life Balance, Job Involvement (scales 1–5)
- **Filters** — Job Role, Job Level, Gender (Select All / Female / Male)
- **Reset Button** — Clears all filters to default view
- **Visuals included:**
  - Donut chart — Attrition by Overtime
  - Donut chart — Attrition by Travel Frequency
  - Line chart — Attrition by Number of Years in Role
  - Scatter/dot chart — Attrition by Distance from Home
  - Pie chart — Attrition by Department
  - Bar chart — Attrition by Job Role
  - Bar chart — Attrition by Salary Hike
  - Bar chart — Attrition by Education

---

## Business Recommendations

### 1. Address Overtime-Driven Burnout
35.5% of all attrition came from overtime workers. HR should review mandatory overtime policies — particularly in Cyber Security and Software Development — and consider compensatory time-off or workload redistribution.

### 2. Strengthen Early-Tenure Retention
208 employees left within their first year — the highest of any tenure band. Implementing structured 30/60/90-day onboarding check-ins and assigning mentors to new hires could significantly reduce Year 1 exits.

### 3. Review Travel Policies
Employees who travel frequently account for 31% of travel-related attrition. Evaluating remote-first options for roles currently requiring frequent travel could improve retention without impacting project delivery.

### 4. Calibrate Salary Hikes to Market Benchmarks
The 0–10% hike band shows the highest attrition (241 employees). Aligning annual increments with industry benchmarks for high-risk roles — especially in Cyber Security and Data Science — would strengthen retention.

### 5. Target Low Satisfaction Scores Proactively
Job Satisfaction scores of 1 and 2 collectively account for 1,086 attritions (48% of total). Quarterly anonymous satisfaction surveys with department-level action plans could catch dissatisfaction before it leads to resignation.

