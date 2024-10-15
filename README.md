
# ROAD ACCIDENT ANALYSIS


## Problem Statement



This dashboard is all about breaking down road accident data into digestible chunks. It helps experts figure out the who, what, where, and why of accidents so they can make our roads safer. For example, by analyzing which vehicle types are most involved in accidents or which road conditions are riskiest, authorities can develop targeted safety measures. Essentially, it turns raw data into actionable insights for improving road safety.


## Steps followed 

 #### Requirement Gathering

Meet with stakeholders to define the goals and key metrics.Ask targeted questions to clarify data needs, expected outcomes, and constraints.Identify the scope, timeline, and resources needed for the project.

#### Stakeholder Identification
Identify internal stakeholders (e.g., business units, managers, executives).
Identify external stakeholders if applicable (e.g., customers, partners).
Understand the data literacy level of stakeholders to tailor insights to their needs.

#### Background Design
Determine the overall architecture of the project (e.g., ETL pipeline, cloud setup, tools like Power BI for visualization).
Identify the types of analysis needed (descriptive, diagnostic, predictive, or prescriptive).Define how data from various sources will be collected, cleaned, and integrated.

#### Data Modeling
Identify the entities and relationships within the data.
Create an Entity-Relationship Diagram (ERD) or other models to represent the data structure.
Set up data tables, fact tables, and dimension tables as per the modeling technique (star schema, snowflake schema).
#### Data Overview
Explore the data to get an overview of its size, structure, and content.
Use summary statistics (e.g., mean, median, mode) and data distributions to get a sense of the data's characteristics.
Identify missing values, outliers, and inconsistencies in the data.
#### Data Connection with Power BI
Connect Power BI to data sources (Excel, SQL databases, APIs, etc.).
Ensure the data is refreshed automatically or on a defined schedule.
Set up relationships between tables if needed within Power BI's data model.
#### Data Cleaning
Handle missing data (e.g., imputation, removal).
Remove duplicates, correct formatting issues, and standardize the data.
Normalize or categorize data where necessary.

#### Data Processing

Use data processing techniques like filtering, sorting, grouping, and joining tables.
Apply calculations and aggregations (e.g., totals, averages, percentages).
Use Power BI’s DAX functions to create calculated columns and measures for analysis.
#### Data Visualization
Choose the right chart types (bar, line, pie, etc.) based on the data and the message.
Use slicers and filters to make the visuals interactive.
Create dashboards with a clear structure that highlights key insights.
#### Report/Dashboard Building
Organize the layout of the dashboard so that the most important insights are prominent.
Include summary metrics and detailed views for drilling down into data.
Allow for different perspectives by enabling user filters, date ranges, and drill-through features.

#### Insights Generation
Analyze the visualized data to identify trends, anomalies, and patterns.
Derive insights and make recommendations based on the analysis.
Prepare a summary of findings, highlighting actionable points and next steps for stakeholders.

#### The dashboard will provide insights into the following key performance indicators (KPIs):

1.Total Casualties and Total Accident values for Current Year and Year-over-Year (YoY) growth
•TOTALYTD(COUNT(Data[Accident_Index]),calender[Date])

•CY casualties=TOTALYTD(SUM(Da[Number_of_Casualties],calender[Date] )

2.Total Casualties by Accident Severity for Current Year and YoY growth
•cy casualties = TOTALYTD(SUM(Data[Number_of_Casualties]),calender[Date] )
•YY casualties = ([cy casualties] - [previous Y casualties])/[previous Y casualties]

3.Total Casualties with respect to vehicle type for Current Year

4.Monthly trend showing comparison of casualties for Current Year and Previous Year

5.Casualties by Road Type for Current year

6.Current Year Casualties by Area/ Location & by Day/Night 

7.Total Casualties and Total Accidents by Location


Snap of Dashboard
![Screenshot 2024-10-15 135351](https://github.com/user-attachments/assets/5b6ea9c0-929b-4040-bc01-163382c4f05e)
