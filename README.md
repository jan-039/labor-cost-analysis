# U.S. Labor Cost Analysis

> 🔄 **Status: In Progress:** The Power BI dashboard is currently underway.

## Table of Contents

1. [Project Background and Overview](#project-background-and-overview)
2. [Repository Contents](#repository-contents)
3. [Terminology](#terminology)
4. [Data & Methodology](#data-and-methodology)
5. [Next Steps](#next-steps)

<!--
3. Executive Summary
4. Key Insights
5. Recommendations / Next Steps
-->

## Project Background and Overview

This project analyzes labor-cost trends across U.S. industries from 2017 to 2024 using employment, wages and salaries, and total compensation data from the Bureau of Economic Analysis (BEA).

The goal is to explore which U.S. industries experienced the greatest changes in employment and labor costs from 2017 to 2024, and where did compensation growth outpace workforce growth?

## Repository Contents
* `labor_cost_analysis.xlsx` — Revised individual analysis focused on U.S. industry employment, wages, compensation, and labor-cost growth from 2017–2024.
* `data/` — Source data files used in the revised analysis.
* `To What Extent Is The American Dream Still Attainable.pdf` — Original group datathon presentation. The datathon was hosted by the Association for Information Systems from California State University, Long Beach. My contribution focused on the wage-growth analysis shown on **Slide 3**, which examined how earning opportunities varied across industries.
* `README.md` — Project overview, methodology, terminology, and analysis progress.

> **Note:** This repository expands on the original team datathon submission. The current Excel and Power BI analysis is an individual revision that develops the labor-cost portion of the project in greater depth.

## Terminology
* **Employees:** Full-time and part-time wage-and-salary employees within an industry.
* **Wages:** Total wages and salaries paid within an industry, including direct employee pay such as salaries, bonuses, and commissions.
* **Compensation:** Total employer labor cost, including wages and supplements to wages and salaries.
* **Supplements:** Employer-paid additions to wages, calculated as `Compensation - Wages`.
* **Wage per Employee:** Total wages divided by employee headcount.
* **Compensation per Employee:** Total compensation divided by employee headcount.
* **Supplements per Employee:** Supplements divided by employee headcount.
* **Wage Share:** Wages as a percentage of total compensation.
* **Supplements Share:** Supplements as a percentage of total compensation.
* **Employee Growth:** Percentage change in employee headcount from 2017 to 2024.
* **Wage Growth:** Percentage change in total wages from 2017 to 2024.
* **Compensation Growth:** Percentage change in total compensation from 2017 to 2024.
* **Compensation per Employee Growth:** Percentage change in compensation per employee from 2017 to 2024.
* **Compensation Growth vs. Employee Growth:** Compensation growth minus employee growth, used to identify industries where labor costs grew faster than workforce size.

## Data and Methodology

- **Primary Tools**
     * Excel
     * Power Query
     * Power BI
- **Datasets Used:**
    * Employees by industry
    * Wages and salaries by industry
    * Compensation of employees by industry
- **Data Cleaning:**
    * Used Excel Power Query to clean category labels
    * Preserved industry hierarchy
    * Reshaped yearly columns
    * Checked for missing values and duplicates
- **Data Integration:**
     * Merged the three datasets using Sector, Subsector, Industry, Level, and Year as matching fields.
- **Calculated Metrics:**
     * Supplements
     * Wage per employee
     * Compensation per employee
     * Supplements share
     * Growth measures
- **Analysis Approach:**
     * Compare 2017 and 2024 values to evaluate employment growth, labor-cost growth, and whether compensation increased faster than workforce size.

## Next Steps

> **Status:** The following analyses are planned and reflect work that is still in progress.

- **Dashboard:**
     * Present the most important findings in **Power BI** through KPIs, rankings, trend charts, and interactive filters.
  
