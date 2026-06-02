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
- ![Overview Pivot Table](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/f62e81a1ebc2f1fbc72a075ff3ff4be6cc3f69cb/Overview%20Pivot%20Table.png)
- ![Performance Pivot Table](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/2a8b0261a25bc40ff8e9492df0b9de5c2333d301/Training%20Pivot%20Table.png)
- ![Training Pivot Table](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/2a8b0261a25bc40ff8e9492df0b9de5c2333d301/Training%20Pivot%20Table.png)

### 4. Dashboard Development
Built **3 professional interactive dashboards** as required:

**Dashboard 1: Workforce Overview**
- KPI Cards (Total Employees, Avg Age, Male/Female Count, Avg Tenure)
- Charts: Employee Count by Department, Gender Distribution, Age Group Distribution
- Added Department Slicer
  ![Overview Dashboard](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/d6500793b06911ffc288bcdf55fa695450016484/Workforce%20Overview.png)

**Dashboard 2: Employee Performance & Engagement**
- KPI Cards (Avg Engagement, Satisfaction, Work-Life Balance, Employee Rating, High Performer Count)
- Charts: Performance Score by Department, Engagement Level Distribution, Satisfaction by Division, Top Performing Departments
- Added Business Unit Slicer
  ![Employee Performance and Engagement Dashboard](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/d6500793b06911ffc288bcdf55fa695450016484/Empployee%20Performance%20and%20Engagement.png)

**Dashboard 3: Training & HR Investment**
- KPI Cards (Total Training Cost, Completion Rate, etc.)
- Charts: Training Attendance, Training Cost by Department, Training Outcome Analysis
- Added Training Program Slicer
  ![Training and HR investment Dashboard](https://github.com/adeolaolotu/HR-Workforce-Performance-Engagement-Analytics/blob/d6500793b06911ffc288bcdf55fa695450016484/Training%20and%20Investment.png)

  ## 5. Insights
- The organization currently has a workforce of 2,845 employees accross 6 departments and 10 business units.
- The workforce is slightly female dominated, with females making up 55.82% and males 44.18%
- The average employee age is 50 years old and has spent approximately 4.77 years in the company.
- Age distribution analysis reveals that over 66% of the workforce is middle-aged or older. This highlights a significant lack of young talents and potential future succession risk.
- Only 346 employees (12.2%) are classified as high performers. The majority of workforce falls into Average or Low performers caterories
- Production dominates the workforce  (1,910 employees) and contributes the highest number of high performers
- Software engineering shows notable weak performance raising concerns about critical functions
- The company spent $1.59 million on training yet the training completion rate is critically low at 25.91%. A large portion of employees either fail or do not complete their training programs.
- Internal and external trainings achieved similar results, implying that training effectiveness may not depend on delivery method.

## 6. Recommendation
- Redesign training initiatives with better accountability and follow-up, aim to raise completion rates above 70%
- Implement structured improvent plans for underperforming units especially  Software Engineering
- Implement succession planning; Increase the proportion of young adults and create knowledge transfer programs between senior and junior employees
- Introduce recognition programs for high performing employess and focus on improving career growth opportunities

## 7. References




