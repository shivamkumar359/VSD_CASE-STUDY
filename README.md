# HR Analytics: Employee Attrition Analysis

An exploratory data analysis project that examines employee attrition patterns using the IBM HR Analytics Employee Attrition & Performance dataset.

The objective of this project is to identify employee groups with higher attrition and analyze the relationships between attrition, overtime, income, job satisfaction, work-life balance, department, job role, and employee experience.

---

## Project Objective

Employee attrition can increase recruitment costs, training costs, and productivity loss. This project uses data visualization and exploratory analysis to identify patterns associated with employee turnover and derive practical HR recommendations.

The analysis focuses on:

- Overall employee attrition rate
- Department-wise and job-role-wise attrition
- Impact of overtime on attrition
- Monthly income and employee retention
- Age, experience, and tenure patterns
- Job satisfaction and work-life balance
- Education field and attrition
- Correlation between numerical features

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition & Performance

**File:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`

| Attribute | Details |
|---|---|
| Total Records | 1,470 employees |
| Total Features | 35 variables |
| Target Variable | Attrition (`Yes` / `No`) |
| Missing Values | No missing values |
| Data Type | HR administrative records |

The dataset includes demographic, job-related, compensation, satisfaction, and work-life balance information for employees.

---

## Key Performance Indicators

| Metric | Value |
|---|---:|
| Total Employees | 1,470 |
| Employees Who Left | 237 |
| Attrition Rate | 16.12% |
| Average Employee Age | 36.92 years |
| Average Monthly Income | $6,503 |

---

## Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Workflow

1. Loaded and inspected the HR dataset.
2. Checked dataset shape, data types, and missing values.
3. Calculated overall attrition metrics.
4. Performed demographic and workforce analysis.
5. Analyzed attrition across departments and job roles.
6. Examined overtime, salary, experience, job satisfaction, and work-life balance.
7. Created visualizations to identify attrition patterns.
8. Used a correlation heatmap to understand relationships among numerical features.
9. Derived business insights and HR recommendations.

---

## Key Insights

- The overall employee attrition rate is **16.12%**, with 237 employees leaving out of 1,470.
- Employees who work overtime show a higher observed attrition level than employees who do not work overtime.
- Sales and Human Resources show notable attrition patterns relative to workforce size.
- Sales Executives, Laboratory Technicians, and Research Scientists account for high attrition counts.
- Employees with lower monthly income show higher observed attrition.
- Employees with low job satisfaction scores are more likely to appear in the attrition group.
- Poor work-life balance is associated with higher employee turnover.
- Younger employees and employees with shorter tenure represent an important attrition-risk segment.
- Monthly income increases with job level, total working years, and years at the company.

> Note: These findings are based on exploratory analysis and identify observed relationships in the dataset. They should not be interpreted as proof of direct causation.

---

## Visualizations Included

This project includes visual analysis of:

- Employee attrition distribution
- Employee age distribution
- Gender distribution
- Years at company distribution
- Department-wise attrition
- Job role versus attrition
- Overtime versus attrition
- Monthly income distribution
- Monthly income versus attrition
- Experience versus salary
- Education field versus attrition
- Job satisfaction versus attrition
- Work-life balance versus attrition
- Correlation heatmap

---

## Business Recommendations

Based on the analysis, the following actions may help reduce employee attrition:

1. Introduce overtime limits and fair compensation for extended working hours.
2. Review salary levels for junior and mid-level employees.
3. Conduct regular employee satisfaction and engagement surveys.
4. Create structured career-development plans for high-risk job roles.
5. Monitor work-life balance and manager workload allocation.
6. Build targeted retention strategies for employees with 0–5 years of tenure.
7. Review workload, career mobility, and employee support within the Human Resources department.

---

## Repository Structure

```text
hr-employee-attrition-analysis/
│
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── HR_Employee_Attrition_Analysis.ipynb
├── case-study.pdf
├── README.md
└── requirements.txt
