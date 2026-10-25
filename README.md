# Datheon_Data_Analytics_Power_BI_Internship
Data Analytics and Power BI Internship Projects – Excel, SQL, Python, and Power BI.
Task 3: Python Data Analysis

Tool: Python

Libraries: Pandas, NumPy, and Matplotlib, where applicable.

Includes: Data cleaning, analysis, and visualization
Skills Developed

Data Cleaning and Analysis

Microsoft Excel and PivotTables



Python

Power BI

Data Visualization

Business Insights

Repository Structure

Project files are organized into separate folders for easy navigation.

Project Status

Data Cleaning & Preparation (Power Query)
Handled raw CSV loading errors and filtered out extra non-numeric rows and header discrepancies using Power Query Editor.

Removed blank rows and assigned appropriate data types (Whole Numbers, Decimal Numbers, Dates) for seamless data modeling.

📈 Key Performance Indicators (KPIs)
Total Orders: ~10K

Total Profit: $286.40K

Total Sales: $2.30M

YoY Sales Growth: 46.88%

Profit Margin: 12.47%

📊 Dashboard Visualizations & Features
Sales Trend Analysis: Monthly sales breakdown highlighting peak performance months (e.g., December with $325.29K).

Category & Sub-Category Insights: Tree map showing Total Sales by Sub-Category (Phones, Storage, Chairs, etc.) and funnel chart for Total Profit by Sub-Category.

Regional Profitability: Breakdown of Total Profit by Category and Region (Technology, Office Supplies, Furniture across East, West, South, Central).

Interactive Slicers: Global filters for Month, Product Name, Country, and Region to dynamically slice and dice the data.

 DAX Measures Used
Total Sales: SUM('superstore_sales'[Sales])

Sales LY: CALCULATE([Total Sales], DATEADD('superstore_sales'[Order Date], -1, YEAR))

YoY Sales Growth %: DIVIDE([Total Sales] - [Sales LY], [Sales LY], BLANK())

Files Included
superstore_sales.csv - Raw dataset used for analysis.

Superstore_Sales_Dashboard.pbix - Power BI report file.

Capture.PNG - Dashboard preview screenshot.

Completed tasks and supporting files are included in this repository.

Acknowledgment

Thank you to Datheon for providing this internship opportunity to develop practical data analytics skills.
