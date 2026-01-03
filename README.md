Data Leverager – Power Query Transformation Project
Overview

This project simulates a real-world ETL workflow using Power BI Power Query. The focus is only on data extraction, cleaning, transformation, merging, and aggregation. No DAX or visualizations are used.

Data Sources

Sales data: Monthly Excel files loaded via Folder (Jan–Apr)

Employee master data: Excel file

Web table: HTML table imported from the web

Key Transformations Performed

Removed blank rows and columns

Promoted headers and standardized column names

Applied correct data types using locale

Removed duplicates and null values

Cleaned customer names using text tools (TRIM, CLEAN, UPPER)

Split address fields

Rounded revenue and cost

Created Profit column

Extracted day, month, year, and quarter from Order Date

Created fiscal month

Calculated employee age from Birthdate

Added conditional Sales Category (High/Medium/Low)

Added 0-based and 1-based index columns

Demonstrated pivot and unpivot

Appended monthly sales files

Merged sales and employee data

Grouped by Region to calculate total sales, average order value, and transaction count

Used data profiling tools to check quality

Created a parameter for dynamic folder path

Simulated refresh by adding Sales_Apr file

Outcome

A fully automated and refresh-ready ETL pipeline.
All transformations are managed inside Power Query to simulate data engineering workflows.

Challenges and Solutions

Mixed formats and nulls were handled through data profiling

Dynamic monthly data handled via Folder query and Parameters

Join mismatches resolved using consistent keys

Tools Used

Power BI Desktop – Power Query Editor
