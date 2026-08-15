# HR Analytics Dashboard

An interactive Power BI dashboard built to analyze employee demographics, hiring trends, attrition patterns, and workforce distribution for a multinational organization.

---

## Problem Statement

Organizations today manage large, diverse workforces, making it challenging for HR teams to manually track employee trends and attrition patterns. As an HR Data Analyst in a multinational organization, the goal of this project is to analyze workforce data covering employee demographics, hiring trends, attrition, and workforce distribution, in order to support better workforce planning and employee management decisions. This project involves developing an interactive **HR Analytics Dashboard** using Power BI, built on the **IBM HR Analytics Employee Attrition & Performance dataset** (Kaggle). The dashboard consolidates key metrics — including attrition by department, job role, age group, income, and tenure, along with workforce composition and satisfaction trends — into a single, easy-to-navigate interface, helping HR stakeholders identify why employees leave and make data-driven decisions to improve retention and organizational stability.

---

## Dataset

- **Source:** [IBM HR Analytics Employee Attrition & Performance – Kaggle](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Records:** 1,470 employee records
- **Key fields:** Age, Attrition, Department, Job Role, Education Field, Gender, Marital Status, Monthly Income, Years at Company, Job Satisfaction, Work Life Balance

---

## Tools Used

- **Power BI Desktop** – data modeling, DAX, dashboard design
- **Power Query** – data cleaning and transformation
- **DAX (Data Analysis Expressions)** – KPI measures and calculated columns
- **GitHub** – version control and submission

---

## Methodology / Steps Followed

1. **Data Collection** – Obtained the IBM HR Analytics Employee Attrition & Performance dataset from Kaggle, containing employee-level records on demographics, job details, compensation, and attrition status.
2. **Data Cleaning & Preparation** – Imported the dataset into Power BI using Power Query, checked data types, removed constant/irrelevant columns (e.g., EmployeeCount, Over18, StandardHours), and verified data quality.
3. **Data Transformation** – Created calculated columns to enable meaningful grouping, such as Age Group, Years at Company Bucket, and Monthly Income Group, to support categorical analysis in visuals.
4. **DAX Measures Creation** – Built key measures including Total Employees, Attrition Count, Active Employees, Attrition Rate, Avg Age, and Avg Years at Company to power the KPI cards and charts.
5. **Dashboard Design** – Designed a two-page interactive dashboard (Overview and Workforce Insights) in Power BI, incorporating KPI cards, donut charts, bar charts, and combo charts to visualize demographics, attrition trends, and workforce distribution.
6. **Interactivity** – Added slicers (Department, Job Role, Education, Gender, Attrition) with cross-page slicer sync and a reset filters button, enabling dynamic filtering and exploration of the data.
7. **Insights & Analysis** – Analyzed the visualized data to extract key findings, such as departments and roles with the highest attrition, and the impact of job satisfaction, work-life balance, and income on employee turnover.
8. **Version Control & Documentation** – Followed the GitHub workflow discussed in class: initialized a repository, structured project files (dataset, .pbix file, screenshots, README), committed changes, and pushed the final project to GitHub for submission.

---

## Dashboard Development

The dashboard was developed in Power BI Desktop as a two-page interactive report, designed to give HR stakeholders a complete view of workforce demographics and attrition at a glance.

### Page 1 – Overview
- Provides a high-level summary of the organization's workforce and attrition status.
- Displays key KPIs: **Total Employees, Attrition Count, Attrition Rate, Active Employees, Average Age, and Average Years at Company**.
- Visualizes attrition patterns across departments, gender, age groups, and job roles, as well as hiring trends over the years and attrition rate by years at company.

### Page 2 – Workforce Insights
- Focuses on workforce composition and the underlying drivers of employee attrition.
- Explores employee distribution by education field, job role, department, and marital status.
- Analyzes the relationship between attrition and factors such as monthly income, job satisfaction, and work-life balance, along with a summarized Key Insights panel highlighting major findings.

Both pages share a consistent design — an IBM-themed color palette, rounded KPI cards, a common navigation panel, and synced slicers (Department, Job Role, Education, Gender, Attrition) — allowing users to filter both pages simultaneously and explore the data interactively. A Reset Filters button is included for quick navigation back to the default view.

---

## Key Insights

- Overall attrition rate is 16.12%.
- The R&D department has the highest attrition count.
- Employees with lower job satisfaction and work-life balance show higher attrition.
- Attrition rate decreases as years at company increases.
- Higher income groups show higher attrition compared to lower income brackets.

---

## Conclusion

An interactive HR Analytics Dashboard was successfully developed in Power BI using the IBM HR Analytics Employee Attrition & Performance dataset. The dashboard consists of two interactive pages, each offering a distinct perspective on the workforce:

**Page 1 – Overview** provides a high-level summary of the organization's workforce and attrition status, with KPIs for Total Employees, Attrition Count, Attrition Rate, Active Employees, Average Age, and Average Years at Company, along with attrition breakdowns by department, gender, age group, and job role.

**Page 2 – Workforce Insights** focuses on workforce composition and the underlying drivers of attrition, exploring employee distribution by education field, job role, department, and marital status, and analyzing the relationship between attrition and factors such as income, job satisfaction, and work-life balance.

Interactive slicers synced across both pages, along with a Reset Filters button, make the dashboard user-friendly and allow users to dynamically explore the data. Overall, the dashboard enables HR stakeholders to identify high-risk attrition segments and make informed, data-driven decisions to improve employee retention and support workforce planning.

---

## Learning Outcomes

After completing this experiment, I learned:

- How to import and prepare HR data in Power BI using Power Query.
- How to clean and transform employee data, including handling data types and removing irrelevant columns.
- How to create calculated columns for grouping data (e.g., Age Group, Income Group, Years at Company Bucket).
- How to write DAX measures for HR KPI calculations such as Attrition Rate, Active Employees, and Average Tenure.
- How to design and format interactive KPI cards for a dashboard.
- How to create Donut, Bar, Column, Line, and Combo charts to visualize business data.
- How to use slicers and slicer sync to enable interactive, cross-page filtering.
- How to analyze employee demographics and overall workforce distribution.
- How to identify and analyze key factors influencing employee attrition, such as job satisfaction, income, and work-life balance.
- How to apply consistent formatting, color themes, and professional design principles to a Power BI dashboard.
- How to structure a multi-page report for clear storytelling and easy navigation.
- How to derive and present data-driven HR insights that support workforce planning and retention strategies.

---

## Repository Structure

```
HR-Analytics-Dashboard/
├── data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── HR_Analytics_Dashboard.pbix
├── screenshots/
│   ├── page1_overview.png
│   └── page2_workforce_insights.png
└── README.md
```

---

## How to View the Dashboard

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/HR-Analytics-Dashboard.git
   ```
2. Open `HR_Analytics_Dashboard.pbix` in **Power BI Desktop** (latest version recommended).
3. Use the slicers (Department, Job Role, Education, Gender, Attrition) at the top of each page to filter the data interactively.

---

## Author
Attem Deepak Mudiraj ( Power Bi Assignment 6)
**[Your Name]**
HR Data Analyst (Project Assignment)
