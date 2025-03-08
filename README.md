# HR-Analytics
The objective of this project is to analyze employee attrition patterns and identify key factors contributing to employee turnover. This interactive Power BI dashboard provides insights into the relationship between attrition and variables like salary, age, job role, education, and work experience.

# Project Objective
The objective of this project is to analyze employee attrition patterns and identify key factors contributing to employee turnover. This interactive Power BI dashboard provides insights into the relationship between attrition and variables like salary, age, job role, education, and work experience.

# Key Questions & KPIs
## Key Questions:
- How does salary and job role influence employee attrition?
- What is the attrition rate across different age groups?
- Is there a relationship between work experience and attrition?
- How does education level impact attrition?
- Which job roles experience the highest employee attrition?
## Key Performance Indicators (KPIs):
- Total Employee Count
- Total Attrition Count
- Attrition Rate
- Average Age
- Average Salary
- Average Years at Company

# Process of the Project
## Data Collection:
Dataset used: HR_Analytics 
- Key columns: 'EmpID', 'Age', 'AgeGroup', 'Attrition', 'BusinessTravel', 'Department', 'JobRole', 'Education', 'Gender', 'MonthlyIncome', 'YearsAtCompany', and others.
Data Cleaning & Transformation:
- Checked for missing values and handled them appropriately.
- Ensured proper data types for each field (e.g., numerical, categorical).
- Created calculated measures: 
  - Attrition Rate = (Total Attrition / Total Employees) * 100
  - Average Age
  - Average Salary
  - Average Years at Company
Dashboard Creation:
- Built interactive visualizations using Power BI: 
  - Attrition by Salary and Job Role (Stacked Bar Chart)
  - Attrition by Age (Stacked Column Chart)
  - Attrition by Experience (Area Chart)
  - Attrition by Education (Donut Chart)
  - Attrition Count by Job Role (Matrix)
  - Key Metrics (Cards for Total Employees, Total Attrition, Attrition Rate, Average Age, Average Salary, and Average Years)
- Added interactive slicers for Department and Gender to enable dynamic exploration.
