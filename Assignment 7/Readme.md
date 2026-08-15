# Finance KPI Dashboard

An interactive Power BI dashboard built to track budget vs. actual spending, budget utilization, and variance across departments, regions, categories, and payment methods for a manufacturing company.

---

## Problem Statement

As a Financial Analyst in a manufacturing company, senior management needs clear visibility into how spending compares against approved budgets across departments, regions, and expense categories, since manually tracking thousands of transactions makes it difficult to spot overspending and support timely financial decisions. This project involves developing an interactive **Finance KPI Dashboard** in Power BI using the **Budget vs Actual Financial dataset** (Kaggle), tracking key metrics such as total budget, actual spend, budget gap, and budget utilization, while breaking down variance by department, region, category, and payment method to help management identify overspending and strengthen budget control.

---

## Dataset

- **Source:** [Budget vs Actual Financial Dataset – Kaggle](https://www.kaggle.com/datasets/kennathalexanderroy/budget-vs-actual-financial-dataset)
- **Records:** ~10,000 transaction-level rows
- **Time period:** 2021–2023
- **Columns:** Date, Department, Category, Region, Budget Amount, Actual Amount, Payment Method, Transaction ID
- **Departments:** Sales, Marketing, IT, Finance, HR, Operations
- **Categories:** Salaries, Marketing, Travel, Training, Utilities, Infrastructure
- **Regions:** North, South, East, West, Central
- **Payment Methods:** Card, Bank Transfer, Cash, UPI

> **Note:** The dataset contains budget and actual spending figures only — it does not include revenue or profit columns. KPIs in this dashboard are therefore built around **budget, actual spend, variance, and utilization** rather than revenue/profit margin.

---

## Tools Used

- **Power BI Desktop** – data modeling, DAX, dashboard design
- **Power Query** – data cleaning and transformation
- **DAX (Data Analysis Expressions)** – KPI measures and calculated columns
- **GitHub** – version control and submission

---

## Methodology / Steps Followed

1. **Data Collection** – Obtained the Budget vs Actual Financial dataset from Kaggle, containing transaction-level records of budgeted and actual spending across departments, categories, regions, and payment methods (2021–2023).
2. **Data Cleaning & Preparation** – Imported the dataset into Power BI using Power Query, verified and corrected data types (Date, numeric amounts, text fields), and removed blank/null rows in Department, Category, and Region.
3. **Data Modeling** – Created a dedicated Date table using DAX (Year, Month Name, Quarter) and linked it to the Budget table via a one-to-many relationship to enable proper time-based filtering and sorting.
4. **Data Transformation** – Added calculated columns such as Variance, Variance %, and Budget Status (Over Budget / Under Budget) to support categorical and comparative analysis.
5. **DAX Measures Creation** – Built key measures including Total Budget, Total Actual, Total Variance, Budget Gap, Budget Utilization %, and Transactions to power the KPI cards and visuals.
6. **Dashboard Design** – Designed a two-page interactive dashboard (Overview and Budget Variance Analysis) incorporating KPI cards, donut charts, bar charts, and line charts to visualize budget performance, spend distribution, and trends over time.
7. **Interactivity** – Added slicers (Department, Category, Region, Payment Method) with cross-page slicer sync and a Reset Filters button, enabling dynamic filtering and exploration of the data.
8. **Insights & Analysis** – Analyzed the visualized data to extract key findings, such as departments and regions with the highest budget overrun, and payment methods driving actual spend.
9. **Version Control & Documentation** – Followed the GitHub workflow discussed in class: initialized a repository, structured project files (dataset, .pbix file, screenshots, README), committed changes, and pushed the final project to GitHub for submission.

---

## Dashboard Development

An interactive Finance KPI Dashboard was successfully developed in Power BI using the Budget vs Actual Financial dataset. The dashboard consists of two interactive pages, each offering a distinct perspective on the organization's financial performance:

### Page 1 – Overview
- Provides a high-level summary of the organization's budget and spending status.
- Displays key KPIs: **Total Budget, Actual Spend, Budget Gap, Budget Utilization %, and Transactions**.
- Visualizes spend distribution by category, regional budget vs actual comparison, department-wise budget utilization, and monthly budget vs actual trends over 2021–2023.

### Page 2 – Budget Variance Analysis
- Focuses on identifying where and why spending deviates from planned budgets.
- Analyzes variance by category, department-wise budget utilization against a 100% target line, and actual spend by payment method.
- Includes a **Key Insights** panel summarizing major findings, such as the highest overspending department and region.

Both pages share a consistent design — a dark navy sidebar with branding and navigation, rounded KPI cards, and synced slicers (Department, Category, Region, Payment Method) — allowing users to filter both pages simultaneously and explore the data interactively. A Reset Filters button is included for quick navigation back to the default view.

---

## Key Insights

- Overall actual spending exceeds the approved budget, indicating a net budget overrun.
- Certain departments show higher budget utilization than others, pointing to specific areas needing closer cost control.
- Spend is spread fairly evenly across expense categories, with Salaries and Marketing among the largest contributors.
- Regional spend patterns show variation, with some regions consistently spending above their allotted budget.
- Card and Bank Transfer are among the most used payment methods for actual spend.

---

## Conclusion

An interactive Finance KPI Dashboard was successfully developed in Power BI using the Budget vs Actual Financial dataset, enabling clear visibility into the organization's budget performance across departments, regions, categories, and payment methods. The Overview page consolidates key financial metrics into a single, easy-to-navigate interface, supported by donut charts, trend lines, and bar charts that break down spending by category, department, region, and month.

The dashboard reveals that actual spending exceeds the approved budget overall, with certain departments and regions showing higher utilization and overspend than others, highlighting specific areas that require closer budget monitoring. Interactive slicers and a Reset button allow users to dynamically filter and explore the data, while the Key Insights panel summarizes the major findings for quick decision-making. Overall, the dashboard equips management with the visibility needed to track financial performance, identify overspending trends, and make informed, data-driven decisions to strengthen budget control and planning.

---

## Learning Outcomes

After completing this experiment, I learned:

- How to import and prepare financial data in Power BI using Power Query.
- How to clean and transform transaction-level data, including handling data types and removing blank/null rows.
- How to build a Date table using DAX and create relationships for time-based analysis.
- How to create calculated columns for variance and budget status classification.
- How to write DAX measures for finance KPI calculations such as Total Budget, Total Actual, Budget Gap, and Budget Utilization %.
- How to design and format interactive KPI cards for a financial dashboard.
- How to create Donut, Bar, Column, and Line charts to visualize budget vs actual performance.
- How to use slicers and slicer sync to enable interactive, cross-page filtering.
- How to analyze spending distribution across departments, regions, categories, and payment methods.
- How to identify and interpret budget variance and overspending trends.
- How to apply consistent formatting, color themes, and professional design principles to a Power BI dashboard.
- How to derive and present data-driven financial insights that support budget control and decision-making.

---

## Repository Structure

```
Finance-KPI-Dashboard/
├── data/
│   └── Budget_vs_Actual_Data.xlsx
├── Finance_KPI_Dashboard.pbix
├── screenshots/
│   ├── page1_overview.png
│   └── page2_budget_variance_analysis.png
└── README.md
```

---

## How to View the Dashboard

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/Finance-KPI-Dashboard.git
   ```
2. Open `Finance_KPI_Dashboard.pbix` in **Power BI Desktop** (latest version recommended).
3. Use the slicers (Department, Category, Region, Payment Method) at the top of each page to filter the data interactively.

---

## Author

**[Your Name]**
Financial Analyst (Project Assignment)
