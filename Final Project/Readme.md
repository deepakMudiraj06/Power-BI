# 📊 HR Analytics Dashboard

## End-to-End Business Intelligence Project

An end-to-end **HR Analytics Business Intelligence solution** developed using **MySQL, SQL, Power Query, DAX, and Power BI** to analyze employee attrition, workforce characteristics, compensation, satisfaction, performance, and other HR metrics.

---

## 📌 Project Overview

Employee attrition is an important challenge for organizations because employee turnover can increase recruitment costs, training expenses, and productivity loss.

This project analyzes HR employee data to identify patterns related to employee attrition and workforce behavior.

The project follows a complete Business Intelligence workflow:

**Dataset → MySQL → SQL → Data Modeling → Power Query → DAX → Power BI Dashboard → Power BI Service**

The main goal is to transform raw employee data into **meaningful business insights and actionable HR recommendations**.

---

## 🎯 Objectives

The main objectives of this project are:

- Analyze overall employee attrition.
- Identify departments with high employee turnover.
- Identify job roles with higher attrition.
- Analyze the relationship between overtime and attrition.
- Analyze job satisfaction and employee turnover.
- Analyze work-life balance and attrition.
- Analyze compensation and income levels.
- Analyze employee performance.
- Analyze business travel and distance from home.
- Analyze employee tenure.
- Build an interactive HR dashboard.
- Generate business insights and recommendations.
- Deploy the dashboard to Power BI Service.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **MySQL** | Database storage |
| **MySQL Workbench** | Database management |
| **SQL** | Data preparation and analysis |
| **Power Query** | Data cleaning and transformation |
| **Power BI** | Dashboard and visualization |
| **DAX** | Measures and KPI calculations |
| **Power BI Service** | Dashboard deployment |
| **On-Premises Data Gateway** | MySQL connectivity |

---

## 📂 Dataset

The project uses an **HR Analytics employee dataset** containing approximately **1,470 employee records**.

The dataset contains information about:

- Employee demographics
- Department
- Job Role
- Job Level
- Education
- Monthly Income
- Job Satisfaction
- Work-Life Balance
- Performance Rating
- Overtime
- Business Travel
- Distance From Home
- Years at Company
- Attrition

### Important Columns

| Column | Description |
|---|---|
| EmployeeNumber | Unique employee ID |
| Age | Employee age |
| Gender | Employee gender |
| Department | Employee department |
| JobRole | Employee job role |
| JobLevel | Employee job level |
| MonthlyIncome | Monthly employee income |
| JobSatisfaction | Job satisfaction rating |
| WorkLifeBalance | Work-life balance rating |
| PerformanceRating | Performance rating |
| OverTime | Overtime status |
| BusinessTravel | Business travel frequency |
| DistanceFromHome | Distance from home |
| YearsAtCompany | Years worked at the company |
| Attrition | Whether the employee left |

---

# 🔄 Project Workflow

```text
                 HR Dataset
                     │
                     ▼
              MySQL Database
                     │
                     ▼
              SQL Preparation
                     │
                     ▼
          Fact & Dimension Tables
                     │
                     ▼
               Star Schema
                     │
                     ▼
              Power BI Desktop
                     │
              ┌──────┴──────┐
              ▼             ▼
        Power Query        DAX
              │             │
              └──────┬──────┘
                     ▼
            Interactive Dashboard
                     │
                     ▼
             Power BI Service
                     │
                     ▼
          On-Premises Gateway
                     │
                     ▼
               MySQL Server
