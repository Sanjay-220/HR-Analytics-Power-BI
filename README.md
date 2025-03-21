# Atlas Lab Employee Data Analysis

## Overview
This project analyzes Atlas Lab's employee data using Power BI to uncover insights on workforce demographics, attrition, and performance. It focuses on employee headcount, retention patterns, and satisfaction metrics to support HR decisions, with interactive dashboards visualizing trends from 2012 to 2022.

The complete Power BI dashboard is uploaded in this Repository.

## Dataset
The CSV files are attached in this repository.

## Approach

### Data Loading and Cleaning
I started by loading the employee dataset into Power BI. To ensure data quality, I performed the following steps:
- Checked for missing or inconsistent values in key columns like age, gender, and salary.
- Standardized date formats for fields such as hire dates and review dates.
- Ensured consistency in categorical variables like department, job role, and ethnicity.
- Removed duplicates and handled outliers in numerical fields like salary and tenure.

### Exploratory Data Analysis
Explored the dataset using Power BI visualizations (histograms, bar charts, line charts, treemaps) to identify trends in employee demographics, attrition, and performance metrics.

## Key Insights

### Workforce Overview
- Atlas Lab has **1,470 employees** (1,233 active, 237 inactive) with a **16.1% attrition rate**.
- **Technology** leads with ~600 active employees, followed by **Sales (~400)**, while **HR has the fewest (~50)**.
- **Sales Executives** and **Data Scientists** are the most common roles, with Technology dominating the workforce.

### Demographic Insights
- Workforce ranges from **18 to 51 years old**, with most (~1,000) aged **20-29**.
- Gender distribution is balanced, with slight variations by age.
- **Marital status:** 37.33% married, 20.2% single, 42.45% divorced.
- **Ethnicity:** Whites (~800) are the largest group, followed by **Black/African American (~300)**.
- **Salary:** Highest for White employees ($120K), lowest for Native Hawaiian/Pacific Islander employees ($100K).

### Attrition Trends
- **Sales Executives** and **Research Scientists** face the highest attrition (~40%).
- Attrition peaked at **25% in 2016-2017** but stabilized at **15% by 2022**.
- Employees with **0-2 years tenure** and those with **high travel or overtime demands** also see ~40% attrition, indicating early-stage and workload-related retention challenges.

### Performance Insights
- **Estelle Chung (hired 7/15/2018)** had stable **job and environment satisfaction** (3-4) from 2019-2022.
- **Work-life balance** dropped to **1 in 2021** before improving.
- **Performance ratings** dipped in **2021 (to 2)** but recovered in **2022 (to 4)**.
- **Relationship satisfaction** declined from **4 (2019) to 2 (2022)**, indicating potential interpersonal issues.

## Conclusion
The project highlights:
- **High attrition** in Sales and Research roles, early-tenure employees, and those with demanding work conditions.
- **A young, diverse workforce** with salary disparities.
- **Work-life balance and relationship issues** impacting satisfaction.

These insights can guide HR to improve **retention and engagement**.
