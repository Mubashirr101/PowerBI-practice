# 📊 Data Jobs Dashboard — Power BI

A comprehensive **Power BI dashboard** analysing the global data job market in 2024, covering salary trends, job demand, hiring platforms, work-from-home rates, and more.

---

## 🖼️ Dashboard Preview

### Page 1 — Overview
![Data Jobs Dashboard Overview](/preview-images/Dashboard-1_page-0001.jpg)


### Page 2 — Drill Through: Data Engineer
![Data Engineer Drill Through](/preview-images/Dashboard-1_page-0002.jpg)


---

## 📌 Features

### Page 1 — Main Overview
| Visual | Description |
|---|---|
| **KPI Cards** | Total jobs (478.895K), Salary Star Rating, Median Yearly Salary ($113.25K), Median Hourly Salary ($47.62) |
| **Job Trends in 2024** | Line chart tracking monthly job counts from Jan–Nov 2024 |
| **Hourly vs Yearly Salary** | Scatter plot comparing hourly and yearly compensation per job title |
| **High Demand Jobs in Data** | Horizontal bar chart ranking job titles by count |
| **Job Title Table** | Detailed table with job count, yearly salary, and mini trend sparklines |
| **Job Title Filter** | Dropdown slicer to filter all visuals by job title |
| **Drill Through Button** | Navigates to a detailed page for the selected job title |

### Page 2 — Drill Through (per Job Title)
| Visual | Description |
|---|---|
| **Salary Gauges** | Median yearly ($126K) and hourly ($59) salary with min/max range |
| **WFH %** | Donut chart — 15% remote, 85% on-site |
| **No Degree Needed %** | Donut chart — 47% require no degree |
| **Health Insurance %** | Donut chart — 10% include health insurance |
| **Global Jobs Distribution** | Bing Maps bubble map showing job locations worldwide |
| **Jobs per Platform** | Bar chart by sourcing platform (LinkedIn, Indeed, BeBee, etc.) |
| **Types of Jobs** | Treemap — Full-time (89%) vs Contractor |




---

## 🗃️ Dataset

The dataset contains data job listings scraped from major job platforms in 2024 with the following key fields:

- `job_title` — Title of the data role
- `salary_year_avg` — Average yearly salary
- `salary_hour_avg` — Average hourly salary
- `job_posted_date` — Date the job was posted
- `job_location` — City/Country of the job
- `job_via` — Platform where the job was listed
- `job_work_from_home` — Boolean: remote or on-site
- `job_no_degree_mention` — Boolean: degree required or not
- `job_health_insurance` — Boolean: health insurance offered
- `job_schedule_type` — Full-time, Part-time, Contractor, etc.



---

## 💡 Insights Highlighted

- **Data Engineer** is the highest-demand role, followed by Data Analyst and Data Scientist
- Job postings peaked in **February 2024** (~55K) and dropped sharply toward **November 2024** (~14K)
- **Senior Data Engineer** and **Machine Learning Engineer** command the highest salaries (~$155K/year, ~$60/hr)
- **LinkedIn** is the dominant job platform by listing volume
- Only **15%** of Data Engineer roles are remote; **89%** are full-time positions
- **47%** of Data Engineer listings do not require a formal degree
