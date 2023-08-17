# Business_Sales_Analysis_SQL_PowerBI

### Setup
- This project requires SQL Server (SQL Express), Power BI Desktop
- We will work with backup Data Warehouse (DW) data and Lightweight (LT) data. Obtain data and restore following instructions from [here.](https://docs.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)
- Compare DW and LT data to understand the difference between structured and unstructured data. We will primarily be working with Data Warehouse data.
- Update Data Warehouse data using [sql script.](https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql)

### Business Request & User Stories
- We need to improve our internet sales reports and want to move from static reports to visual dashboards.
- Essentially, we want to focus it on how much we have sold of what products, to which clients and how it has been over time.
- Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also.
- We measure our numbers against budget so I added that in a spreadsheet so we can compare our values against performance. 
- The budget is for 2021 and we usually look 2 years back in time when we do analysis of sales.


### Clean the Data using SQL
- Understand the difference between FACT tables & Dimension tables.
- Identify which tables in the data are of interest with the help of the Business Request form.
- Choose which columns are of interest to export by preparing and transforming these columns in SQL using concepts such as: renaming columns, combining columns, commenting in SQL script, formatting of SQL statements, WHERE clause, ORDER BY, LEFT JOIN, CASE() function and ISNULL() function. 

### Create Dashboard in Power BI
- Load Data
- Organize & Prepare Tables
- Connect Tables for Data Model
- Import Fact_Budget
- Calculation Measures
- Dashboard Design
- Import Custom Visual
- Measure Table
- Pie Chart
- Line Chart
- Bar Charts
- Map Graph
- Top 10 Graphs
- Gradient Bar Chart Color
- Customer Details
- Pivot Table
