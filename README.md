                                 Presence Insights Dashboard | Power BI
Project Overview

  Developed an interactive HR analytics dashboard in Power BI to monitor employee attendance, Work From Home (WFH), and leave patterns across the organization.

The source data was maintained in separate monthly attendance sheets (April, May, June) where employee attendance status was recorded daily. Using Power Query, the monthly sheets were transformed and consolidated into a single analytical dataset for reporting and trend analysis.



  Business Problem

HR teams often manage attendance records across multiple spreadsheets, making it difficult to:

* Track employee attendance trends
* Monitor WFH utilization
* Analyze leave patterns
* Generate consolidated workforce reports

This dashboard provides a centralized view of employee presence and attendance behavior.



                             Dataset
                         Source Structure

* Multiple monthly worksheets (Apr 2022, May 2022, Jun 2022)
* Employee-wise daily attendance records
* Attendance codes such as:

  * P (Present)
  * WFH (Work From Home)
  * SL (Sick Leave)
  * PL (Paid Leave)
  * WO (Weekly Off)





   Data Transformation

Performed ETL operations using Power Query:

* Combined multiple monthly attendance sheets into a single dataset
* Implemented parameterized data loading for scalable sheet management
* Unpivoted date columns into a row-based structure
* Standardized attendance status values
* Cleaned and formatted date fields
* Removed unnecessary columns
* Created an analytics-ready data model



 DAX Measures & Calculations

Created measures and calculated columns using:

* CALCULATE()
* DIVIDE()
* SUM()
* COUNTROWS()
* switch()


   Key Metrics

* Attendance %
* WFH %
* Sick Leave %
* Present Days
* Employee Attendance Summary



   Dashboard Features

* Attendance KPI Tracking
* WFH Analysis
* Sick Leave Analysis
* Employee-Level Attendance Monitoring
* Attendance Trend Analysis
* Weekday-Based Attendance Insights
* Dynamic Date Filtering


 Tools & Technologies

* Power BI
* Power Query
* DAX
* Excel



 Skills Demonstrated

* Data Cleaning
* Data Transformation
* ETL
* Power Query
* Parameterized Queries
* DAX
* Calculated Columns
* Measures
* Data Modeling
* Dashboard Development
* HR Analytics
* Business Intelligence



 Key Outcome

Successfully transformed multi-sheet attendance records into a scalable reporting solution, enabling automated attendance analysis, workforce monitoring, and actionable HR insights through interactive Power BI dashboards.
