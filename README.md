#HR Analytics Dashboard

## Overview
Built an interactive HR Analytics Dashboard analysing employee 
attrition, salary distribution, and workforce trends for 1,473 employees.

## Dataset
- Source: HR Analytics Dataset
- Records: 1,473 employees (after cleaning)
- Columns: 35 columns
- Original: 1,480 rows × 38 columns

## Tools Used
- Python (Pandas, Matplotlib, Jupyter Notebook)
- Microsoft Excel (Pivot Tables, PivotCharts, Dashboard)

## Data Cleaning Steps
- Removed 7 duplicate rows
- Filled 57 missing values in YearsWithCurrManager with median (3.0)
- Deleted 3 useless columns (StandardHours, Over18, EmployeeCount)
- Final clean dataset: 1,473 rows × 35 columns

## Dashboard Features
- 4 KPI metrics (Total Employees, Attrition Rate, Left, Stayed)
- 5 interactive charts
- Professional dark blue theme

## Key Findings
1. Overall attrition rate is 16.1% (237 employees left)
2. Sales department has highest attrition at 20.6%
3. Youngest employees (18-25) have 35.8% attrition rate
4. Overtime employees are 3x more likely to leave (30.5% vs 10.4%)
5. Managers earn 6.5x more than Sales Representatives

## Files
- HR_Dashboard_Analysis.ipynb — Python analysis and visualizations
- HR_Analytics_Dashboard.xlsx — Excel dashboard with all analyses
- README.md — Project documentation

## Dashboard Preview
The dashboard includes:
- Employee Attrition Rate (Pie Chart)
- Attrition by Department (Bar Chart)
- Attrition by Age Group (Bar Chart)
- Impact of Overtime (Clustered Bar)
- Average Salary by Job Role (Horizontal Bar)
