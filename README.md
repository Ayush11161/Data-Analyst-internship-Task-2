# Data-Analyst-internship-Task-2
Superstore Dataset - Power BI Dashboard  

Overview  
This repository contains a Power BI dashboard built using the Sample Superstore dataset.  
The dashboard provides insights into sales, profit, quantity, and customer segments with interactive visuals and KPIs.  

Steps Performed  
1. Load Dataset  
   - Imported the dataset (`Sample - Superstore.csv`) into Power BI using Get Data → Text/CSV.  

2. Create Calendar Table  
   - Built a Date table using CALENDAR() function.  
   - Added helper columns: Year, Month, YearMonth.  
   - Linked Order Date to Calendar Date and marked Calendar as a date table.  

3. Create Measures (KPIs)  
   - Total Sales = SUM(Sales)  
   - Total Profit = SUM(Profit)  
   - Total Quantity = SUM(Quantity)  
   - Profit Margin = Profit ÷ Sales  
   - Average Order Value = Sales ÷ Distinct Order Count  
   - YoY Sales = Current Sales – Previous Year Sales  
   - YoY Sales % = % change compared to last year  

4. Create KPI Cards  
   - Added Card visuals for Total Sales, Total Profit, Profit Margin, and Avg Order Value.  

5. Build Main Visuals  
   - Line Chart: Sales trend by YearMonth with YoY comparison.  
   - Bar Chart: Sales by Category and Sub-Category.  
   - Scatter Plot: Profitability by Sub-Category (Sales vs Profit, bubble size = Quantity).  
   - Filled Map: Regional sales and profit distribution.  
   - Stacked Column: Sales by Customer Segment.  

6. Add Filters (Slicers)  
   - Year slicer from Calendar table.  
   - Region and Category slicers for dynamic filtering.  

7. Formatting & Storytelling  
   - Applied consistent colors (Sales = Blue, Profit = Green, Margin = Orange).  
   - Added titles and captions for insights.  
   - Arranged KPIs at the top, visuals in the middle, and slicers on the side.  

8. Export Deliverables  
   - Saved dashboard as `superstore.pbix`.  
   - Exported PDF version of the dashboard.  
   - Took screenshots of key visuals for documentation.  

Summary  
Metric                | Value  
----------------------|----------------------------  
Dataset Source        | Sample Superstore CSV  
Main KPIs             | Sales, Profit, Quantity, Profit Margin, Avg Order Value  
Time Intelligence     | YoY Sales, YoY Sales %  
Deliverables          | PBIX file, PDF export, Screenshots  

Files Included  
- data/superstore.csv → Raw dataset  
- dashboard_files/superstore.pbix → Power BI file  
- screenshots/dashboard1.png → KPI Cards view  
- screenshots/dashboard2.png → Sales trends  
- screenshots/dashboard3.png → Category & region analysis  
- README.md → This file (dashboard summary)  

Tools Used  
- Power BI Desktop  
- DAX (Data Analysis Expressions)  

Author: Ayush Rawat  
Date: 2025-09-24  

