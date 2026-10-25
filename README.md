# employee-analytics
HR Analytics Dashboard --- Power BI

Project Overview
This project uses Power BI to analyze workforce composition, employee terminations, employee profiles, compensation, and performance review outcomes.

The report contains three dashboard pages:
1. Workforce Overview
2. Employee Attrition Analysis
3. Employee Profile & Performance
   
Dashboard Pages
1. Workforce Overview
Key metrics:
- Total Employees: 2,000
- Active Employees: 1,658
- Average Tenure: 2.18 years
- Active Employee Rate: 82.90%
Visuals:
- Active Employees vs. Terminations Trend
- Employee Count by Business Unit and Status
- Employee Count by Department
- Employee Count by Employment Status
- Employee Count by Job Level

3. Employee Attrition Analysis
Key metrics:
- Terminated Employees: 342
- Voluntary: 215
- Median Tenure at Termination: 267.00 (as displayed in the dashboard)
- Termination Rate: 17.10%
Visuals:
- Employee Count by Age Group and Status
- Termination Type Overview
- Termination Rate by Business Unit
- Termination Rate by Department
- Employee Terminations Over Time.
- Termination types shown in the dashboard are Voluntary, Involuntary, and Retirement.

5. Employee Profile & Performance
Key metrics:
- Average Review Score: 3.23/5
- Employees UnReviewed: 834
- Median Base Salary: Rp8,450,000
- Average Base Salary: Rp9,034,000
Visuals:
- Termination Rate by Age Group
- Employee Count by Review Outcome and Employment Status
- Employee Count by Review Outcome
- Median Base Salary by Job Level
- Salary statistics by department, including minimum, maximum, median, and average base salary.
- Review outcomes shown in the dashboard include Unreviewed, Meets, Exceeds, Needs Support, and Outstanding.

Key Findings
The workforce consists of 2,000 employees, of whom 1,658 are active and 342 are terminated. The displayed active employee rate is 82.90%, while the termination rate is 17.10%.
There are 342 termination recorded in the report. The termination-type chart shows voluntary terminations as the largest
category (62.87%), followed by involuntary terminations (28.95%) and retirement (8.19%).
834 employees are marked as unreviewed in the performance dashboard. This indicates a sizeable group without a recorded performance review in the displayed analysis and may warrant further review of performance-management coverage.
The average review score is 3.23 out of 5. This provides a high-level summary of recorded performance scores; it should be interpreted alongside review coverage and outcome categories.
Median base salary is Rp8,450,000, compared with an average of Rp9,034,000. The higher average suggests that some salaries above the median may be pulling the average upward, though the underlying salary distribution should be checked before drawing firm conclusions.
Median base salary varies by job level. The dashboard shows Lead as the highest median-salary group, followed by Senior, Specialist, and Associate.
Termination rates differ across departments and business units in the displayed charts. Finance appears highest among departments in the shown department chart, while Product & Technology appears highest among business units. These comparisons should be interpreted with the report's filters and rate calculations in mind.

Tools
Power BI Desktop
Power Query
DAX

Interactive Filters
The dashboard includes slicers for: - Employment Status - Job Level - Department Name - Business Unit
These filters allow users to explore the metrics across employee groups.

Data Source
https://www.analyticsengineering.com/datasets/workforce-employee-attrition

Repository Contents
`dashboard/` --- Power BI report file (`.pbix`).
`images/` --- dashboard screenshots for preview.
`README.md` --- project overview and documentation.

Notes
The findings above are based on the supplied dashboard PDF and reflect the values shown there. Confirm definitions, filter behavior, and underlying calculations before using these figures for formal HR decisions.
