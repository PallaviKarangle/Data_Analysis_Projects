# Data_Analysis_Projects

 # IPL 2022 Data Analysis
* Analyzed the IPL 2022 season to identify trends in match outcomes.
* Winning Patterns: Determined which teams won by runs vs. wickets.
* Branded Visualizations: Used official IPL team colors for better insights.
* Graphical Representation: Created stacked bar charts & pie charts using Plotly.
* Toss & Match Winners: Found teams that won both toss & match.

 # iPhone Sales Data Analytics
* Performed an in-depth analysis of iPhone sales trends.
* Sales Performance: Examined how ratings, discounts, and pricing impact sales.
* Correlation Analysis: Identified relationships using scatter plots & trendlines.
* Geographic Insights: Explored region-wise sales patterns.
* Interactive Dashboards: Used Plotly for engaging bubble charts & bar graphs.
* Tech Stack: Python, Pandas, Plotly, Seaborn, Matplotlib

# Amazon Global Sales Dashboard – Power BI
# Problem Statement:
This dashboard provides detailed insights into Amazon's global sales performance, helping business stakeholders analyze sales trends, customer segments,
and product profitability. The goal is to identify key growth areas, track sales projections, and improve business strategies based on real-time data.

# Steps Followed:
1. Data Loading & Cleaning
Imported the dataset (CSV) into Power BI Desktop.
Opened Power Query Editor to check for column distribution, column quality, and column profile.
Ensured data consistency by removing null values in relevant columns (e.g., profit analysis).
2. Data Transformation & Calculations
Applied DAX formulas to calculate sales, profit margins, and key performance indicators (KPIs).
Created calculated columns and measures to analyze customer profitability and product performance.
Segmented data based on market regions, product categories, and customer types.
3. Data Visualization & Dashboard Design
Designed an interactive dashboard in Power BI Report View.
Added slicers (filters) for Product Category, Region, and Year to enable dynamic data analysis.
Created bar charts, KPI cards, and map visualizations to present key findings.
4. Key Insights & Business Impact
A. Sales & Market Analysis
* Total Sales: $12.64M across different market segments.
* Top Performing Regions: Asia Pacific (31.98%), followed by Europe (26%) and USCA (18.7%).
* Top Customer Segments: Consumer (51.48%), followed by Corporate (30.25%) and Home Office (18.2%).
B. Product Profitability Analysis
#Top 5 Most Profitable Products:
1.Canon Imaging (Profit: $25K)
2.Cisco Smart Devices (Profit: $17K)
3.Motorola Accessories (Profit: $17K)
#Bottom 5 Least Profitable Products:
1.Bevis Router (-$3.6K)
2.Cubify Printer (-$8.9K)
#Customer Profitability
* Top 10 High-Value Customers contributing to overall profit.
* Used customer segmentation analysis to track profitability trends.

5. Publishing & Reporting
*Published the dashboard to Power BI Service for business-wide access.
*Enabled real-time data refresh to keep insights up-to-date.
# Conclusion:
This Power BI dashboard helps Amazon stakeholders make data-driven decisions by analyzing sales trends, regional performance, and customer profitability. 
It provides a comprehensive view of global sales performance and helps in identifying opportunities for business growth.


# COVID-19 Data Analysis with SQL
This project involves analyzing COVID-19 data using SQL Server, focusing on key metrics like total cases, deaths, infection rates, and vaccinations. The queries perform data cleaning, aggregations, and trend analysis to uncover insights.

# Key SQL Operations & Insights
* Data Exploration
  1.Fetching raw data from CovidDeaths and CovidVaccinations tables.
  2.Identifying countries with the highest infection and death rates.
* Statistical Analysis
  1.Total Cases vs. Total Deaths – Evaluating fatality rates for each country.
  2.Cases vs. Population – Measuring the percentage of population infected.
  3.Global Trends – Summarizing new cases, deaths, and mortality rates over time.
* Data Transformation & Advanced SQL
  1.Joins – Merging vaccination and case data for deeper insights.
  2.Window Functions – Calculating rolling totals for vaccinations.
  3.Common Table Expressions (CTEs) – Structuring data for better readability.
  4.Views & Temporary Tables – Creating reusable datasets for visualization.

# Bike Sales Dashboard - Excel Analysis

* Introduction
   This project presents an interactive Bike Sales Dashboard built using Microsoft Excel. The dataset includes customer demographics, financial details, and bike 
   purchase records. The dashboard provides insights into buyer behavior using Pivot Tables, Charts, and Slicers for enhanced visualization.

* Key Features & Steps Followed
  1.Data Cleaning & Preparation
    * Removed duplicate records to ensure data accuracy.
    * Segmented customers into three age groups:
        * Adolescent
        * Middle Age
        * Old
    * Sorted and filtered data based on relevant attributes.

  2.Data Transformation & Analysis
    * Created a Pivot Table summarizing key sales insights based on:
       * Marital Status, Gender, Income, Children, Occupation, Cars, and Commute Distance
       * Bike purchase trends across different regions
    * Segmented buyers based on whether they purchased a bike or not.

  3.Data Visualization & Dashboard Creation
    * Designed various charts to visualize sales trends, including:
       * Line Charts (Bike purchases by demographic)
       * Column Charts (Income distribution across bike buyers)
    * Implemented Slicers for interactive filtering by:
       * Region, Age Brackets, Gender, and Occupation
    * Built a user-friendly dashboard to provide real-time insights.
 

  # HR Analytics Dashboard

This project presents an interactive HR Analytics Dashboard built using Power BI, designed to help Human Resources teams gain deeper insights into employee attrition trends and patterns.

* Key Features & Implementation:
1.Data Preparation with Power Query:
   * Removed duplicate values to ensure data quality and accuracy.
   * Used conditional columns to derive key metrics, such as Attrition Count.

2.DAX Measures Created:
   * Attrition Rate = (Attrition Count / Total Employees) * 100
   * Additional calculated measures to dynamically display KPIs like average age, salary, and tenure.

3.Interactive Visualizations:
   * Attrition by Department, Gender, and Job Role
   * Attrition by Education, Age Group, and Salary Slab
   * Job Satisfaction-Based Attrition Table
   * Tenure-Based Attrition Line Chart

4.User-Friendly Insights:
   * Easy-to-understand visualizations to identify high attrition segments.
   * Helps HR quickly pinpoint problem areas like specific departments, salary ranges, or job roles with higher attrition.

*  Tools Used
   * Power BI Desktop
   * Power Query Editor
   * DAX (Data Analysis Expressions)
