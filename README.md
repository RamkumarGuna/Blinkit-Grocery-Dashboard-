# Blinkit-Grocery-Dashboard-
Built an interactive dashboard to analyze sales performance, outlet distribution, product categories, and customer preferences across different outlet types and locations.
/blinkit-grocery-dashboard
  ├── README.md        # Overview of project
  ├── /dashboards      # Power BI .pbix files
  ├── /sql-scripts     # SQL queries for data source
  ├── /docs            # Documentation, screenshots
  └── LICENSE          # Usage terms
Built an interactive dashboard to analyze sales performance, outlet distribution, product categories, and customer preferences across different outlet types and locations.



🔍 Key Insights Delivered:

✅ Total Sales, Average Sales, Number of Items, and Average Ratings KPIs

✅ Sales trends by Outlet Establishment Year

✅ Outlet-wise performance analysis (Tier 1, Tier 2, Tier 3)

✅ Product category and Item Type sales breakdown

✅ Fat Content analysis (Low Fat vs Regular)

✅ Outlet Size and Outlet Type performance comparison

✅ Interactive filters for dynamic business exploration



🛠️ Tools & Skills Used:

• Power BI

• Data Modeling

• DAX Measures

• Power Query

• Data Visualization

• Business Intelligence & Analytics

# Measures I have to created 

Average Sales = Average(Blinkit_Grocery[Item_Outlet_Sales])
Avg MRP = average(Blinkit_Grocery[Item_MRP])
Avg Rating = average(Blinkit_Grocery[Item_Visibility])
Avg Sales per Outlet = divide(sum(Blinkit_Grocery[Item_Outlet_Sales]),DISTINCTCOUNT(Blinkit_Grocery[Outlet_Identifier]))
Sales Contribution % = divide(sum(Blinkit_Grocery[Item_Outlet_Sales]),calculate(sum(Blinkit_Grocery[Item_Outlet_Sales]),all(Blinkit_Grocery)))
Sales Per Item = divide(sum(Blinkit_Grocery[Item_Outlet_Sales]),countrows(Blinkit_Grocery))
Total items = COUNTROWS(Blinkit_Grocery)
Total Sales = sum('Blinkit_Grocery'[Item_Outlet_Sales])


#PowerBI #DataAnalytics #BusinessIntelligence #DataVisualization #DashboardDesign #DAX #PowerQuery #Analytics #DataScience #Blinkit #LearningByDoing #PortfolioProject
