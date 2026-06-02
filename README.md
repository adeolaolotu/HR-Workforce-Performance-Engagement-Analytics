# HR-Workforce-Performance-Engagement-Analytics
Interactive Excel dashboards analyzing a 2,845-employee HR dataset focusing on workforce performance, engagement, satisfaction, and training effectiveness.

## Steps I took in this project

### Data Understanding and loading
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
