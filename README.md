# Sales Dashboard

A project that utilizes Microsoft PowerBI to analyze sale data and visualize  through an interactive dashboard.

## Problem Description

I have been use dataset Adventure Workbook to analyze and visualize sales data.


## Project Goals

I would like the Power BI dashboards to analyze 3 aspects:
- Product
- Customer
- Summary Sale
In order to answer these questions, I invested time in planning the PowerBI measures I would need to create and also planned a rough outline of the dashboard visuals I wanted. 

## Hardware and Software Used

- Windows 11 Machine
- Microsoft PowerBI Desktop (v2.93)
- Microsoft Excel


## Overview of Microsoft Power BI

Microsoft Power BI is a data analytics tool used to provide business intelligence capabilities, including loading, modelling, and visualizing data sets. Its initial release was over 10 years ago in July 2011, and since then the Microsoft team has continued to add greater functionality and improve ease-of-use on a monthly basis. 

The program itself can be used both on a local machine (via Power BI "Desktop") and also on the cloud (via Power BI "Services"). It can be used in a similar fashion as how one may use Excel, but also provides the greater ability to more easily create interactive visualizations called 'dashboards'. 


## Explanation of Project Files

Here is a brief description of each file/folder found in this GitHub repository.

## Data Collection Methodology

I collected this data by Adventure Workbook. The dataset have 8 tables: Dim_date, Fact_sale, Dim_customer, Dim_Territories, Dim_Return, Dim_Product, Dim_Product_Categories, Dim_Product_Subcategories

## Data Cleaning

There was quite a bit of data cleaning to do. I had to do some basic editing such as: change Data Type, Standardize Data, Custom Dim_date table,...
Finally, only a few rows contained null entries, so I simply chose to remove these rows from the overall dataset; This would not drastically affect the variance of the overall data.
## Measure Creation & Visualizations

The main visuals I used were 'slicers'. I created calendar slicers for overall date, year, quarter, month, and day of week. With these one has a lot of options as to what granularity they wish to visualize their data with respect to dates. 

## Conclusion

Using PowerBI I was able to visualize sales data in an interactive way. This allowed me to drill deeper into business situation.

