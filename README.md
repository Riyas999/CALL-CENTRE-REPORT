# CALL-CENTRE-REPORT
This repository contains the call centre performance report.it includes data and analysis related to call volume, Agent performance, customer satisfaction metrics and other key performance indicators (KPIs).the report is prepared in excel format and intended for internal for internal analytics, operational planning, and performance review.

**Contents**
	•	File:Call-centre-Report.xlsx
	•	Format: Microsoft Excel Workbook
	•	Sheets Included:
	•	CUSTOMER CENTRE REPORT – Main dashboard containing KPIs across branches.
	•	PIVOTS – Summary statistics using pivot tables.
	•	Data – Raw transactional data used for analysis.
	•	Sheet2 – Supporting data, historical comparisons, or draft calculations.
 
**Features & Techniques Used**
1. Data Cleaning
	•	Used Power Query to import, clean, and shape raw data
	•	Removed nulls, handled missing values, and standardized formats
	•	Add additional columns for useful for pivot table 
2. Power Query
	•	Queries created to transform and normalize multiple source tables
	•	Steps include column renaming, type casting, merging datasets, and indexing
3. Data Model
	•	Relationships established between tables using primary and foreign keys (customer id)
	•	One-to-many relationships enable consistent aggregation and filtering across sheets
	•	Optimized for PivotTables and Power Pivot functionality
4. DAX (Data Analysis Expressions)
	•	Used for calculated columns and measures such as:
	•	Total Calls
	•	total revenue
	•	Customer Satisfaction rating
	•	total calls count

**Business Insights Enabled**
	•	KPI Tracking: Call volumes,total revenue, satisfaction rating
	•	representative Comparison: Performance across different service locations
	•	Trend Analysis: Monthly/quarterly patterns.

 **Use Cases**
	•	Operations Managers: Monitor live performance and agent efficiency
	•	Data Analysts: Drill into metrics and run custom reports
	•	Executives: Get an at-a-glance view of KPIs and trends
	•	Trainers/HR: Identify training needs based on performance gaps
