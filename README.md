# SimpleStoreAnalysis
This reporsitoy links to a project on my portfolio. The project is based on a dataset from kaggle that was used to create a simple Power BI dashboard.
## About 
This dashboard is using data sourced from an online Kaggle dataset as well as some custom code used to create the DIM_DATE.  This dashboard was designed to give a high level overview to multiple stakeholders, ranging from C-Suite to Store Managers. 



A dynamic Date Dimension was joined to this datamodel within Power BI to allow for date related calculations such as MoM and YoY calculations. This data has a set date range from February 2010 into November 2012. 

The data in this dashboard includes Sales, Headcount, External factors such as Weather, CPI, Fuel Price. MoM sales growth, YoY sales growth, and sales difference. 



Data cleaning process for this datamodel: 

Create the Dim_Date table using a function created in Power BI. 
Create a standardized date dimension in the existing data to join to Dim_Date. 
Ensure all Data types are correct (Date, Currency, Whole Number). 


Measures Created: 

Average Unemployment
Previous Month Sales 
Sales (Weekly) 
Sales Difference (Dynamic based on date range) 
Sales Growth % (Dynamic based on date range) 
Average CPI 
Average Temperature 
Holiday Sales 
Total Sales by Store 
Total Sales by Department 
Total Sales on Markup
