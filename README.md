# Sales Performance Dashboard #
The Sales Performance Dashboard Excel workbook provides a comprehensive view of sales, customer behavior, product performance, and geographic trends. Using pivot tables, PowerPivot relationships, and data modeling, this workbook enables in-depth analysis for decision-making, trend identification, and profitability insights.


# The workbook Sales_Performance.xlsx contains 8 sheets, each serving a specific purpose for sales analysis #

1. Customers
Description: Lists unique customers.
Columns: Customer ID, Customer Name
Rows: ~793 unique customers
Use Case: Identify top customers, segment analysis, order frequency insights

2. Orders
Description: Detailed transaction-level data
Columns: Row ID, Order ID, Order Date, Ship Date, Ship Mode, Customer ID, Segment, Postal Code, Product ID, Sales, Quantity, Discount, Profit, Year, Month, Week
Rows: ~9,994 orders spanning 2020–2023
Notes: Dates are in Excel numeric format (e.g., 44873 → November 8, 2022)
Use Case: Sales trends, shipping patterns, profitability analysis

3. Products
Description: Catalog of products sold
Columns: Product ID, Category, Sub-Category, Product Name
Rows: ~1,894 products
Use Case: Product performance, category-level profitability

4. Locations
Description: Geographic information of orders
Columns: Postal Code, City, State, Region, Country/Region
Rows: ~632 unique locations across the US
Use Case: Regional sales analysis, geographic heatmaps

5. PVT_Weekly_Analysis
Description: Weekly sales and profit pivot table

Key Insights:
Total Sales: ~$2.3M
Avg Sales per order: ~$229.86
Avg Profit per order: ~$28.66
Use Case: Weekly trends, seasonality detection

6. PVT_M&Y_Analysis
Description: Monthly & yearly sales/profit analysis by sub-category

Key Insights:
Top Sub-Categories: Phones (~$330k), Chairs (~$328k)
Yearly Sales: 2020 (~$484k), 2023 (~$733k)
Monthly Peaks: November (~$352k), December (~$325k)
Use Case: Growth analysis, seasonality, sub-category performance

7. PVT_Customer_Analysis
Description: Customer-level pivot table

Key Insights:
Total Customers: 793
Top Customer: Sean Miller (~$25k, 15 orders)
Yearly Orders: 2020 (1,993) → 2023 (3,312)
Use Case: Customer segmentation, loyalty analysis

8. KPI
Description: Placeholder sheet for Key Performance Indicators
Use Case: Users can add custom metrics like Profit Margin (~12.5% overall), Sales Growth, or Average Order Value

File Structure
Sales_Performance.xlsx
├── Customers
├── Orders
├── Products
├── Locations
├── PVT_Weekly_Analysis
├── PVT_M&Y_Analysis
├── PVT_Customer_Analysis
└── KPI

# Conclusion #
The analysis of the sales dataset reveals key trends in customer behavior, product performance, and regional sales.
Top-performing products and sub-categories, high-value customers, and peak sales periods have been identified. 
These insights can help the business optimize inventory, plan marketing campaigns, improve customer retention, and make data-driven strategic decisions for revenue growth.

