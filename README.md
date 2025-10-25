# WideWorldImporters_PurchasingAnalysisDashboard
Power BI dashboard analyzing Wide World Importers' purchasing data, tracking supplier performance, purchase trends, and cost optimization insights.
1) Project Overview
This Power BI project analyzes purchasing operations for Wide World Importers (WWI), a company specializing in importing and distributing consumer goods, souvenirs, toys, and specialty food items across the San Francisco Bay Area.
The goal is to provide a comprehensive view of purchasing performance, supplier efficiency, and category-level profitability to support data-driven decision-making in procurement.

2) Dataset
Data originates from the WideWorldImportersDW database, which includes purchasing, supplier, and product information.
Key tables include:
Fact.Purchase
Dim.Supplier
Dim.StockItem
Dim.Date
Data Dictionary: https://dataedo.com/samples/html/WideWorldImportersDW/doc/WideWorldImportersDW_6/home.html

3) Dashboard Pages
Purchasing Overview
Total purchasing cost: $2.17B, quantity: 140M units, overall profit margin: 49.77%.
Highlights major suppliers (Fabrikam Inc., Litware Inc.) and category profitability.
Displays supplier cost dependency and contribution to overall performance.

Ordering Trends
Tracks monthly and yearly purchasing activity (2013–2016).
Purchase orders increased by 14.02% YoY with an average order size of 5K units.
Includes cost-per-unit and cost-per-outer analyses for trend monitoring and cost optimization.

Supplier Performance
Evaluates purchasing cost and unit price by supplier.
Monitors fulfillment ratio (1.00) and profit margin across suppliers.
Fabrikam Inc. leads in purchasing cost ($1.64B), while Litware Inc. delivers steady profitability and moderate unit costs.

Category & Item Insights
Breaks down purchasing quantity, cost, and profit margin by category.
Lists top 10 items by average purchase quantity.
Identifies high-margin categories such as Packaging and Novelty Goods.

4) Key Insights
Supplier Concentration:
Over 75% of total purchasing cost is tied to Fabrikam Inc., indicating potential overreliance on a single supplier.
Category Profitability:
Packaging and Novelty Goods categories show the highest margins (60%+), while Clothing has lower profitability but large volume.
Purchasing Growth:
Purchasing activity shows a steady upward trend with consistent order growth across years.
Cost Optimization:
Unit purchase prices range widely ($9–$107); opportunities exist to negotiate bulk pricing and improve procurement timing.
High-Demand Items:
Items such as tape dispensers and XML tag t-shirts consistently drive high purchasing quantities, reflecting stable demand.

5) Recommendations
Diversify Suppliers:
Expand orders to additional suppliers to reduce dependency and improve negotiation leverage.
Focus on High-Margin Categories:
Increase purchasing in Packaging and Novelty Goods categories to enhance overall profitability.
Monitor Unit Costs:
Set up Power BI alerts for price fluctuations and purchasing inefficiencies.
Forecast Demand:
Use historical trends to anticipate high-demand periods and align purchasing volume accordingly.
Supplier Performance Review:
Track delivery times, cost efficiency, and profit contribution regularly to optimize supplier relationships.

6) Tools & Technologies
Power BI Desktop
Power Query & DAX
Microsoft SQL Server (WideWorldImportersDW)
Data Visualization and Dashboard Design
