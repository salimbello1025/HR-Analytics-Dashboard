# 📊 HR Analytics Dashboard — Employee Attrition Analysis

By Salim Bello Muhammad 
---

## 📋 Overview
Built a fully interactive HR Analytics Dashboard to help 
management understand why employees leave and what can be 
done to retain them. This project was built using both 
Microsoft Excel and Python (Plotly Dash) to create two 
professional versions of the same dashboard.

---

## 📁 Dataset
| Feature | Details |
|---|---|
| Source | HR Analytics Dataset |
| Original Size | 1,480 rows × 38 columns |
| After Cleaning | 1,473 rows × 35 columns |
| Employees Left | 237 (16.1%) |
| Employees Stayed | 1,236 (83.9%) |

---

## 🔧 Tools Used
- **Microsoft Excel** — Pivot Tables, PivotCharts, 
  Slicers, Dashboard Design, Navigation
- **Python** — Pandas, Matplotlib, Plotly, Dash,
  Dash Bootstrap Components, Jupyter Notebook

---

## 🧹 Data Cleaning Steps
| Step | Action | Result |
|---|---|---|
| 1 | Removed duplicate rows | 7 removed |
| 2 | Filled missing values in YearsWithCurrManager | 57 filled with median (3.0) |
| 3 | Deleted redundant columns | StandardHours, Over18, EmployeeCount removed |
| 4 | Renamed analysis sheets | Descriptive names added |
| Final | Clean dataset | 1,473 rows × 35 columns |

---

## 📊 Analyses Built (5 Pivot Tables)

### 1. AttritionRate
Overall attrition rate across all employees
- **16.1%** of employees left (237 out of 1,473)

### 2. AttritionByDept
Attrition breakdown by department
- **Sales**: 20.6% — highest attrition 🔴
- **Human Resources**: 19.0% — second highest 🟠
- **Research & Development**: 13.8% — most stable 🟢

### 3. AttritionByAge
Attrition breakdown by age group
- **18-25**: 35.8% — highest risk group 🔴
- **26-35**: 19.1%
- **36-45**: 9.1% — most stable 🟢
- **46-55**: 11.5%
- **55+**: 17.0%

### 4. OvertimeImpact
Impact of overtime on attrition
- **With Overtime**: 30.5% attrition 🔴
- **Without Overtime**: 10.4% attrition 🟢
- Overtime employees are **3x more likely to leave!**

### 5. SalaryByRole
Average monthly income by job role
- **Highest**: Manager — $17,182 🥇
- **Lowest**: Sales Representative — $2,630 🔴
- **Gap**: Managers earn 6.5x more than Sales Reps

---

## 🎨 Excel Dashboard Features
- ✅ Professional dark blue theme
- ✅ 4 KPI metric boxes prominently displayed
- ✅ 5 interactive charts with consistent styling
- ✅ 4 slicers — Department, Gender, AgeGroup, OverTime
- ✅ All slicers connected to all 5 Pivot Tables
- ✅ Charts update dynamically when filters clicked
- ✅ Navigation button on Insights sheet
- ✅ How to Use guide included
- ✅ Last Updated timestamp

---

## 🌐 Web Dashboard (Plotly Dash)
Built a fully interactive web dashboard using Plotly Dash
that runs in the browser with real-time filtering!

### Web Dashboard Features
- ✅ Dark professional theme (#0d1117 background)
- ✅ 4 color coded KPI metric cards
- ✅ 4 dropdown filters (Department, Gender, AgeGroup, OverTime)
- ✅ 5 interactive charts with hover effects
- ✅ All charts update dynamically when filters change
- ✅ Donut chart, grouped bar charts, horizontal bar chart
- ✅ Built with Dash Bootstrap Components

### How to Run the Web Dashboard
1. Install requirements: pip install dash plotly dash-bootstrap-components openpyxl
2. Run the app: python HR_Dashboard_App.py
3. Open browser and go to:  http://127.0.0.1:8050
---

## 🗂️ Workbook Structure
| Sheet | Content |
|---|---|
| HR_Dashboard | Interactive dashboard with KPIs and charts |
| AttritionRate | Overall attrition Pivot Table and chart |
| AttritionByDept | Department attrition Pivot Table and chart |
| AttritionByAge | Age group attrition Pivot Table and chart |
| OvertimeImpact | Overtime effect Pivot Table and chart |
| SalaryByRole | Salary analysis Pivot Table and chart |
| HR_Analytics_Clean | Cleaned dataset |
| Insights | Professional insights report |

---

## 🔍 Key Findings
1. Overall attrition rate is **16.1%** — 1 in 6 employees left
2. **Sales** department loses most staff at 20.6%
3. **Young employees** aged 18-25 are most at risk at 35.8%
4. **Overtime** is the strongest driver of attrition (3x risk)
5. **Low salary** roles show consistently higher attrition

---

## 💡 Recommendations
1. Reduce mandatory overtime especially in Sales department
2. Improve compensation for Sales Representatives
3. Create retention programs for employees aged 18-25
4. Review HR department management practices
5. Introduce flexible working to reduce employee burnout

---

## 📂 Files
| File | Description |
|---|---|
| HR_Analytics_Dashboard.xlsx | Complete Excel workbook with dashboard |
| HR_Analytics_Dashboard.ipynb | Python analysis and visualizations |
| HR_Dashboard_App.py | Plotly Dash web application |
| HR_Dashboard_Screenshot.png | Screenshot of web dashboard |
| README.md | Project documentation |

---

## 🖥️ How to Use the Excel Dashboard
1. Open **HR_Analytics_Dashboard.xlsx**
2. Go to **HR_Dashboard** sheet
3. Click any value in the **Department** slicer to filter
4. Click any value in the **Gender** slicer to filter
5. Click any value in the **AgeGroup** slicer to filter
6. Click any value in the **OverTime** slicer to filter
7. All 5 charts update automatically!
8. Click **Return to Dashboard** button on Insights sheet

---

## 🖥️ How to Use the Web Dashboard
1. Run **HR_Dashboard_App.py** in terminal
2. Open browser → **http://127.0.0.1:8050**
3. Use dropdown menus to filter by Department, 
   Gender, Age Group or Overtime
4. Hover over charts to see detailed numbers
5. All 5 charts update instantly when filters change

---

*Last Updated: June 2026*
*Prepared by: Salim Bello Muhammad  
    
