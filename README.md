# U.S. Labor Cost Analysis

> 🔄 **Status: In Progress:** Excel analysis are currently underway. A Power BI dashboard will be added in a later phase of the project.

## Table of Contents

1. [Project Background and Overview](#project-background-and-overview)
2. [Data & Methodology](#data-and-methodology)
3. [Next Steps](#next-steps)

<!--
3. Executive Summary
4. Key Insights
5. Recommendations / Next Steps
-->

## Project Background and Overview

This project analyzes labor-cost trends across U.S. industries from 2017 to 2024 using employment, wages and salaries, and total compensation data from the Bureau of Economic Analysis (BEA).

The goal is to explore which U.S. industries experienced the greatest changes in employment and labor costs from 2017 to 2024, and where did compensation growth outpace workforce growth?

## Data and Methodology

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

- **Industry Summary:**
     * Compare 2017 and 2024 industry-level results and calculate key growth metrics for employment, wages, compensation, and compensation per employee.
- **Variance Analysis:**
     * Measure how much labor-cost growth exceeded headcount growth and separate compensation changes into headcount-driven and rate-driven effects.
- **Trend Analysis:**
     * Use annual data from 2017–2024 to visualize labor-cost and employment trends across industries.
- **Dashboard:**
     * Present the most important findings in **Power BI** through KPIs, rankings, trend charts, and interactive filters.
  
