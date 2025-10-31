# Bank-Loan-Report
Bank Loan Analysis Dashboard

This project is a complete Bank Loan Analysis System built using MS SQL Server for data processing and Power BI for interactive visualization.
The purpose of this project is to analyze loan applications, track funded vs received amounts, measure loan performance, and identify patterns in good vs bad loans.

## 📊 Project Overview

The dataset contains loan application records with details such as:
Loan Amount,
Amount Received,
Interest Rate,
Debt-to-Income Ratio (DTI),
Loan Status,
Loan Purpose,
State & Home Ownership,
Employee Length, etc.


Using SQL, various KPIs and aggregated metrics were generated. These insights were then visualized in Power BI across three report pages:

Page	Description

**Summary :** Displays top-level KPIs, Good vs Bad loan distribution, and loan status overview.

 **Overview :** Shows monthly trends, term-based split, employee length impact, ownership & purpose-based loan performance.
 
 **Details :** Contains a detailed tabular loan-level view for deep analysis.


### 🛠 Tools & Technologies Used

| Tool	               | Purpose                                   |
|--------------------- | ------------------------------------------|
| **MS SQL Server**	   | Data Cleaning, KPI Calculation & Aggregations|
| **Power BI Desktop**  | Visualization & Dashboard Development        |
| **DAX Measures**	     | Month-over-Month and MTD Metrics            |
| **Excel / CSV**	       | Base Data Source                          |


### 📈 Key KPI Metrics Derived

Total Loan Applications,
 Total Funded Amount,
 Total Amount Received,
 Average Interest Rate,
 Average DTI (Debt-to-Income Ratio),
 Good Loan vs Bad Loan Percentage,
 MTD (Month-to-Date) & PMTD (Previous Month-to-Date) performance metrics

 📂 Power BI Report Structure

| Page	        | Visuals Included |
|-------------  | --------------------|
| **Summary** 	| KPI Cards, Donut Charts, Loan Status Matrix |
| **Overview**	       | Line Chart, Donut Split, Bar Charts, Treemaps |
| **Details**	        | Loan-Level Table with filters |


### 🎯 Insights Derived

Majority of loans fall under Good Loan category (Fully Paid / Current).

Bad Loans form a small but financially significant segment.

Loans with longer employee work experience tend to perform better.

Debt Consolidation is the most common loan purpose.

Majority funded loans belong to individuals under Mortgage & Rent ownership.

### Dashboard Previews

![Summary Dashboard]
#### Overview Dashboard
![Overview Dashboard]
#### Details Dashboard
![Details Dashboard]
