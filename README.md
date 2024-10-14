# Project: Sales Analysis Dashboard using Power BI

Objective: To create an interactive and insightful Power BI dashboard to analyze the online sales performance of premium chocolates. This project focuses on critical aspects like shipment performance, sales, profit, and cost analysis, leveraging advanced DAX measures and visualization techniques.

# Data Cleaning and Preparation:
The project began with cleaning and transforming the raw sales data to prepare it for analysis:

# Data Cleaning:
* Addressed missing or inconsistent data, removed duplicates, and standardized key variables (e.g., product categories, shipment data) for uniformity.
* Ensured accuracy of financial data by cross-referencing shipment costs, sales, and profits.

# Data Manipulation:
* Created relationships between various tables, linking sales, product, region, and shipment data to ensure a holistic view.
* Applied Power BI’s Power Query Editor for filtering, merging, and enriching data.
* Created calculated columns and applied DAX (Data Analysis Expressions) for custom metrics, such as total costs, profit, and shipment volume.

# Key DAX Measures Developed:
A total of 19 DAX measures were developed to support more in-depth analysis and interactive dashboard features, such as:
* Total Costs, Profit, Sales, Shipments, Boxes: Created measures to calculate total costs, profits, number of shipments, sales volume, and boxes shipped, providing clear performance metrics.
* Low Box Shipment Count: Created a measure to flag when the number of boxes shipped was significantly lower than average, helping to track underperformance in shipments.
* Month-on-Month Changes: Developed DAX measures for Month-over-Month Changes in key metrics, such as cost, profit, shipments, sales, and boxes shipped, allowing the business to track growth or decline across months.
* Profit Target Indicator: Created a dynamic measure to indicate whether a certain profit target had been met or missed, providing real-time feedback on performance relative to business goals.
*Shipment Analysis (Bar Chart): Developed a specific measure to track shipment performance by region, using metrics such as total shipments, boxes shipped, and cost per shipment. This was then visualized in bar charts for clearer comparison.

# Dashboard Creation and Visualizations:
After preparing the data and creating the DAX measures, the cleaned data was uploaded into Power BI. The dashboard includes the following key elements:
* Slicers for Geographical and Product Filters: Slicers were integrated to filter data based on geographical regions and product categories, allowing users to drill down and examine specific areas of interest.
* Line Charts for Key Metrics: Utilized line charts to visualize monthly trends for Profit Percentage, Boxes Shipped, Costs, Sales, and Shipments. This allows users to track how these key metrics fluctuate over time, offering deeper insight into the health of the business.
* Bar Chart for Shipment Analysis: Developed bar charts to compare shipment performance across regions and products, showcasing low box shipment counts and allowing for easy identification of areas needing improvement.
* Tables for Product and Sales Team Analysis: Separate tables were designed for product performance and sales team metrics, helping to determine whether profit margins were influenced by either product offerings or the efforts of the sales team.

# Advanced Features:
* Custom DAX Measures and Visualizations: The DAX measures provided flexibility for users to toggle between metrics, such as total sales, cost breakdown, and profit margins.
* Profit Target Indicator: A dynamic target indicator was added to highlight whether the set profit goals were met, making it easy for stakeholders to assess overall performance.
* Interactive Filtering and Drilldowns: The dashboard allowed for deep customization, with slicers and filters enabling detailed views of regional performance and product profitability, as well as trends in shipment efficiency.

# Tools & Techniques Used:
* Data Cleaning & Preparation: Power Query in Power BI
* Advanced Analysis & Calculations: DAX (Data Analysis Expressions) for dynamic calculations
* Visualization: Power BI with custom slicers, charts, and tables

# Key Insights Derived:
* Profit and Cost Analysis: The month-over-month analysis revealed key trends, showing that periods of lower shipment volumes correlated with increased costs, which negatively impacted profitability.
* Regional Shipment Trends: Through the use of slicers, it became evident that specific regions were underperforming in terms of shipment efficiency, leading to increased costs and lower profit margins.
* Sales and Profit Trends: The line charts and dynamic profit indicator enabled real-time tracking of profit margins, costs, and sales volume, making it easier to adjust strategies to achieve profit targets.

