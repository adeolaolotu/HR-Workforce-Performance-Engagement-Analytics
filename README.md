# HR-Workforce-Performance-Engagement-Analytics
Interactive Excel dashboards analyzing a 2,845-employee HR dataset focusing on workforce performance, engagement, satisfaction, and training effectiveness.

## Steps I took in this project

### 1. Data Understanding and loading
- Loaded the raw CSV dataset (HR ANALYTICS DATASET) into Excel
- Explored the structure, columns, and data quality

### 2. Data Cleaning & Preparation
- Removed duplicate records using **Employee ID**
- Converted text dates to proper Date format (StartDate, DOB, Training Date, Survey Date)
- Handled missing values and inconsistencies
- Trimmed extra spaces in text columns (especially DepartmentType)
- Created calculated columns using formulas:
  - **Age Group** (using IF function)
  - **Tenure (Years)** (using DATEDIF)
  - **Performance Category** (High, Average, Low)
  - **Satisfaction Level** (Satisfied, Neutral, Unsatisfied)
  - **Engagement Level**

### 3. Exploratory Data Analysis (EDA)
- Built multiple **Pivot Tables** and Pivot Charts as the core engine for dynamic data analysis and visualization
- Conducted in-depth analysis of workforce demographics, department & business unit distribution, and age composition
- Evaluated employee performance levels, engagement scores, satisfaction levels, and work-life balance across departments
- Analyzed training program effectiveness, including attendance, costs, completion rates, and outcomes
- ![Overview Pivot Table]([Overview Pivot Table.png](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/5e5fe8905f15a13f83fd5b86e071da02f9990c2c/Overview%20Pivot%20Table.png))
- ![Performance Pivot Table](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/2a8b0261a25bc40ff8e9492df0b9de5c2333d301/Training%20Pivot%20Table.png)
- ![Training Pivot Table](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/2a8b0261a25bc40ff8e9492df0b9de5c2333d301/Training%20Pivot%20Table.png)

### 4. Dashboard Development
Built **3 professional interactive dashboards** as required:

**Dashboard 1: Workforce Overview**
- KPI Cards (Total Employees, Avg Age, Male/Female Count, Avg Tenure)
- Charts: Employee Count by Department, Gender Distribution, Age Group Distribution
- Added Department Slicer
- 

**Dashboard 2: Employee Performance & Engagement**
- KPI Cards (Avg Engagement, Satisfaction, Work-Life Balance, Employee Rating, High Performer Count)
- Charts: Performance Score by Department, Engagement Level Distribution, Satisfaction by Division, Top Performing Departments
- Added Business Unit Slicer

**Dashboard 3: Training & HR Investment**
- KPI Cards (Total Training Cost, Completion Rate, etc.)
- Charts: Training Attendance, Training Cost by Department, Training Outcome Analysis
- Added Training Program Slicer
