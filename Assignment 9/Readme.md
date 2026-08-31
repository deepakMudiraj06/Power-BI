Student Learning Analytics Dashboard
📌 Project Overview

The Student Learning Analytics Dashboard is a Power BI project developed to perform Exploratory Data Analysis (EDA) on student learning and academic performance data.

The dashboard helps analyze student study habits, attendance, coding practice, learning platform usage, and performance. It provides interactive visualizations and KPIs to identify important patterns and relationships in the dataset.

🎯 Objectives
Analyze student learning behavior.
Understand overall academic performance.
Compare performance across academic years.
Analyze the relationship between study hours and performance.
Analyze the relationship between attendance and performance.
Identify commonly used learning platforms.
Understand student performance segments.
Provide an interactive and professional dashboard.
📊 Dataset

A synthetic dataset containing 500 student records and 14 columns was used.

Dataset Attributes
Column	Description
Student_ID	Unique student ID
Year	Academic year
Semester	Current semester
Study_Hours_Per_Day	Daily study hours
Learning_Platform	Primary learning platform
AI_Tool_Used	AI tool used for learning
Coding_Hours_Per_Week	Weekly coding practice
Attendance_Percent	Attendance percentage
Assignment_Completion_Percent	Assignment completion percentage
YouTube_Hours_Per_Week	Weekly YouTube usage
Group_Study	Participation in group study
Mock_Tests_Per_Month	Monthly mock tests
Performance_Score	Student performance score
Student_Segment	Performance category
🛠️ Tools Used
Microsoft Power BI
Power Query
DAX
CSV Dataset
📈 Dashboard KPIs

The dashboard contains five main KPI cards:

Total Students
Average Performance
Average Attendance
Average Study Hours
Average Coding Hours

These KPIs provide a quick overview of the student dataset.

📊 Dashboard Visualizations

The dashboard contains six important visualizations:

1. Average Performance by Year

A column chart used to compare average student performance across 1st, 2nd, and 3rd year.

2. Study Hours vs Performance

A scatter chart used to analyze the relationship between daily study hours and performance scores.

3. Attendance vs Performance

A scatter chart used to examine the relationship between attendance and academic performance.

4. Student Performance Segments

A donut chart showing the distribution of:

High Performer
Average Performer
Needs Improvement
5. Students by Learning Platform

A bar chart showing the number of students using different learning platforms.

6. Coding Practice & Performance by Year

A combo chart comparing average coding hours and average performance across academic years.

🎛️ Interactive Filters

The dashboard includes the following slicers:

Year
Semester
Learning Platform
Student Segment

Users can select different filter values to explore specific groups of students.

🔢 DAX Measures
Total Students
Total Students =
DISTINCTCOUNT(Student_Data[Student_ID])
Average Performance
Average Performance =
AVERAGE(Student_Data[Performance_Score])
Average Attendance
Average Attendance =
AVERAGE(Student_Data[Attendance_Percent])
Average Study Hours
Average Study Hours =
AVERAGE(Student_Data[Study_Hours_Per_Day])
Average Coding Hours
Average Coding Hours =
AVERAGE(Student_Data[Coding_Hours_Per_Week])

🔄 Dashboard Workflow
Student Dataset
      ↓
Data Import
      ↓
Data Cleaning
      ↓
Data Type Validation
      ↓
DAX Measures
      ↓
KPI Creation
      ↓
Charts & Visualizations
      ↓
Interactive Filters
      ↓
Final Power BI Dashboard
      ↓
EDA Insights
💡 Key Insights

The dashboard helps identify:

Differences in student performance across academic years.
The relationship between study time and performance.
The relationship between attendance and performance.
The distribution of student performance levels.
Popular learning platforms among students.
Differences in coding practice across academic years.

🎨 Dashboard Theme

The dashboard uses a professional dark theme with:

Black background
Blue highlights
Teal and green accents
Purple and orange accents
White text
Modern KPI cards
Clean and organized visual layout


🚀 How to Use
Download the dataset.
Open Power BI Desktop.
Import the CSV file.
Create the required DAX measures.
Create the dashboard visuals.
Add the required slicers.
Apply the dark dashboard theme.
Save the Power BI file.
Use the interactive dashboard to explore student learning patterns.

📌 Conclusion

The Student Learning Analytics Dashboard demonstrates how Power BI can be used for exploratory data analysis. It converts student learning data into meaningful KPIs and visualizations that make patterns and relationships easier to understand.

The dashboard can support data-driven decisions by helping identify student performance trends, learning behaviors, and areas where additional academic support may be required.
