# data-analyst-internship-task8
created a Sales Dashboard in Power Bi to analyze business performance.The dashboard provides an efficient view of sales trends over time, regions, and product categories, enabling business users to quickly identify the top performing areas and potential losses

# Sales Dashboard - Task 8 (Data Analyst Internship)
# Objective:
Build a simple, interactive dashboard for analysis of *Sales Performance* by *Product Category, Region, and Month-Year* using *Power BI*.


# Tools Used:
* Power BI Desktop - dashboard creation
* Power Query - cleaning & transforming the data
* Dataset - Sample Superstore (CSV)


#  Dataset Overview:
The dataset contained sales transactions with columns including:
* Order Date
* Ship Date
* Region
* Category
* Sales
* Profit

# Data Cleaning Steps:
1. Imported *Sample Superstore (CSV)* into Power BI.
2. In the Power Query Editor:
   * Made sure Order Date and Ship Date  --> Date type.
   * Made sure Sales and Profit --> Decimal Number type.
   * Made sure Region and Category -->Text type.
3. Removed any unnecessary/blank rows & columns.
4. Added a new column Month-Year by extracting it from Order Date using:

   DAX
   MonthYear = FORMAT([Order Date], "MMM-YYYY")
   
# Dashboard Design:
The development of the dashboard included the following:
1. Line Chart - Sales trend over Month-Year
2. Bar Chart - Sales by Region
3. Donut Chart - Sales by Category
4. Slicer - To filter by Region

# Formatting:
* Applied colours to accentuate the highest performing regions & categories
* Titles added to the charts; arrangement of visuals for clarity

# Insights:
1. The *West region* had the highest sales overall.
2. The *Technology category* was the highest contributor in revenue.
3. Sales peaked in *December* and declined in *February*.
4. *Office Supplies* category had steady sales but in moderate amounts relative to other categories.
# Deliverables:
* Dashboard Screenshot/PDF (attached in repo)
* Insights (this README)
* Dataset (CSV)
# Outcome:
This was a demonstration of how to develop a clean, interactive dashboard to illustrate business insights visually in Power BI.
