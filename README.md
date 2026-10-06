Dashboard Design | Sales & Financial Executive Dashboard
Data Analyst Internship (Elevate Labs)
Objective
Design an interactive dashboard in Power BI that gives business stakeholders a quick view of sales and profit performance.
Tools & Dataset
Tool: Power BI
Dataset: Sales & financial data (financial_data.csv), cleaned into financial_data_cleaned.csv before loading into Power BI
What I Did
Cleaned the raw dataset and saved it as financial_data_cleaned.csv.
Imported the cleaned file into Power BI.
Built the Sales & Financial Executive Dashboard with KPI cards, a slicer and a time-series chart.
Summarized the dashboard in a PPT.
Dashboard Features
Feature
Details
KPI cards
Total Sales, Total Profit, Profit Margin %, Total Orders
Slicer
Region (Central, East, South, West)
Time-series
Line chart: Sum of Sales by Order Date
Theme
Rounded cards on a grey canvas with a purple accent
Metric
Value
Total Sales
678.78K
Total Profit
91.52K
Profit Margin %
13.48% (Profit ÷ Sales)
Total Orders
1.401K (Count of Order ID)
Selecting another region in the slicer updates all cards and the chart.
Repository Contents
├── financial_data.csv                # raw dataset
├── financial_data_cleaned.csv        # cleaned dataset used in Power BI
├── dashboard.pbix                    # Power BI dashboard file
├── dashboard_screenshot.png          # dashboard screenshot
├── Task4_Dashboard_Summary.pptx      # PPT summary
└── README.md
Possible Improvements
Sort the trend chart by Order Date (Year → Month) to show the true sales trend.
Add a Growth % (year over year) KPI.
Add a navigation menu and more views (Category, Segment).
