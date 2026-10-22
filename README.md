📊 Project Overview
This project analyzes the Sample Superstore dataset to evaluate sales performance, profitability, customer contribution, regional performance, product sub-category performance, and the relationship between discounting and profit margin.
The analysis was built in Microsoft Excel, combining data preparation, calculated fields, formulas, PivotTables, interactive slicers, and dashboard visualizations to transform raw transactional data into actionable business insights.
The objective was to move beyond simply reporting numbers and identify where revenue and profit are being generated, where profitability is under pressure, and which areas deserve further investigation.
📈 Interactive Sales & Profitability Dashboard
The final analysis was consolidated into an interactive Excel dashboard containing five visualizations and three interactive slicers.
<img width="1529" height="556" alt="dashboard png" src="https://github.com/user-attachments/assets/a97fbf72-98ba-49d9-968b-050d8d1d4e20" />

Dashboard Components
Sales & Profit by Region
Monthly Sales Trend
Profit Margin by Discount
Profit by Sub-Category
Top 10 Customers
Region slicer
Sub-Category slicer
Year slicer
The dashboard provides an interactive overview of business performance and allows users to filter the analysis by region, sub-category, and year.
🎯 Business Questions
This analysis was designed to answer the following questions:
Which regions generate the most sales and profit?
How does sales performance change over time?
Which product sub-categories are the most and least profitable?
Which customers contribute the most sales?
How does discounting relate to profit margin?
Which areas of the business require closer attention?
What actions could potentially improve sales and profitability?
🗂️ Dataset
The project uses the Sample Superstore transactional dataset.
The dataset contains information including:
Order and shipping dates
Customer information
Customer segment
Geographic information
Region
Product category and sub-category
Product names
Sales
Quantity
Discount
Profit
A calculated Profit Margin field was also used:
Profit Margin = Profit ÷ Sales
The overall average profit margin in the analysis was 12.56%.
🛠️ Tools & Skills
Microsoft Excel
The project demonstrates the use of:
Data preparation and validation
Calculated columns
Excel formulas
SUM
SUMIF
SUMIFS
COUNTIF
AVERAGEIF
COUNTA
UNIQUE
Lookup functions
PivotTables
PivotTable grouping
Interactive slicers
KPI calculations
Data visualization
Dashboard development
Business insight generation
🔍 Analysis Performed
1. Regional Sales & Profitability
Regional performance was analyzed across Central, East, South, and West using a PivotTable.
<img width="333" height="152" alt="regional_analysis png" src="https://github.com/user-attachments/assets/05082546-1c0b-4ae5-91cc-55a436fb82ea" />

Key Findings
Total Sales: $2,326,534.35
Total Profit: $292,296.81
West recorded the strongest sales performance.
South recorded the lowest sales performance among the four regions.
The regional analysis provides a basis for investigating differences in demand, product mix, pricing, discounting, and profitability across markets.
3. Monthly Sales Performance
Sales were grouped by year and month to examine changes in performance over time.
<img width="231" height="650" alt="monthly_trend png" src="https://github.com/user-attachments/assets/6dceea7a-12af-4665-bb11-72b23145dc95" />

Annual Sales
Year
Sales
2023
$494,040.21
2024
$472,993.03
The monthly analysis provides visibility into periods of stronger and weaker sales performance and creates an opportunity to investigate seasonality and changes in demand.
4. Product Sub-Category Profitability
Profit was analyzed across product sub-categories to identify areas contributing positively and negatively to the bottom line.
<img width="273" height="482" alt="sub_category png" src="https://github.com/user-attachments/assets/9a0bbafc-c92a-4c77-a0a3-859a726741fb" />

Key Findings
Sub-Category
Profit
Copiers
$56,093.94
Accessories
$41,936.64
Tables
-$17,753.21
Bookcases
-$3,632.07
Copiers generated the highest profit among the highlighted sub-categories, while Tables recorded the largest loss.
This demonstrates why sales volume alone is insufficient for evaluating product performance.
5. Customer Sales Analysis
Customer-level sales were analyzed to identify the highest-value customers.
<img width="274" height="314" alt="top_customers png" src="https://github.com/user-attachments/assets/aa8fab6c-0551-4001-8fb4-31f2d4adc861" />

Key Findings
Sean Miller: $25,043.05
Top 10 customers combined: $153,811.17
This analysis helps identify valuable customers whose purchasing behavior can be monitored as part of customer retention and account management strategies.
6. Discount & Profit Margin Analysis
Average profit margin was analyzed across different discount levels.
<img width="361" height="373" alt="discount_margin png" src="https://github.com/user-attachments/assets/3a88ca50-c07f-48c0-9309-478d60ab1c85" />

Key Finding
Overall Average Profit Margin: 12.56%
The analysis provides a basis for investigating how different discount levels are associated with profitability.
Rather than assuming that discounting directly causes changes in profitability, the analysis highlights patterns that warrant further investigation.
🧮 Key Metrics & Formula-Based Analysis
The workbook also includes a dedicated Calculator sheet containing formula-based business metrics.
<img width="939" height="315" alt="calculator png" src="https://github.com/user-attachments/assets/12e113c8-2720-4c80-af5d-417dcc6e60ee" />

The calculations demonstrate the use of Excel functions to extract specific business insights directly from the underlying dataset, including metrics relating to:
Total sales
Regional sales
Discounted orders
Category profitability
Highest-value customers
Regional/category profitability
Unique customers
This demonstrates the use of both formula-driven analysis and PivotTable-based analysis within the same project.
💡 Key Business Insights
1. Regional performance varies
The West region recorded the strongest sales performance, while the South recorded the lowest. This suggests that regional performance should be evaluated separately rather than treating the business as one uniform market.
2. Strong sales do not necessarily mean strong profitability
The product analysis shows why sales should be evaluated alongside profit. Some sub-categories generated losses despite contributing to overall sales.
3. Tables require attention
Tables recorded a loss of $17,753.21, making them the largest loss-making sub-category identified in the analysis.
Potential areas for further investigation include pricing, discounting, costs, and individual product performance.
4. High-value customers contribute significantly to sales
The top 10 customers generated $153,811.17 in sales, highlighting the importance of monitoring and retaining high-value customers.
5. Discounting should be evaluated alongside margin
The discount analysis provides a way to monitor profitability across different discount levels rather than evaluating promotions solely by their effect on sales.
6. Sales performance changes over time
The monthly analysis provides visibility into changes in demand and creates opportunities for further investigation into seasonality and periods of unusually strong or weak performance.
📌 Business Recommendations
Based on the findings, management could:
Investigate the causes of losses within Tables and Bookcases.
Review pricing, costs, and discount strategies for loss-making products.
Monitor discount levels alongside profit margins.
Study the practices and product mix behind high-performing regions.
Develop retention strategies for high-value customers.
Monitor monthly sales trends to improve forecasting and planning.
Use the interactive dashboard to regularly track regional, product, and customer performance.
📚 Project Skills Demonstrated
This project demonstrates my ability to:
Work with raw transactional data
Prepare and structure data for analysis
Create calculated fields and business metrics
Use Excel formulas to answer business questions
Build and analyze PivotTables
Analyze sales, profit, customers, products, and regions
Investigate profitability and discounting
Build interactive dashboards
Communicate analytical findings through data visualization
Translate data findings into business recommendations
⚠️ Project Limitations
This analysis is based on the information available within the Sample Superstore dataset. It does not include external factors such as competitor pricing, marketing expenditure, inventory costs, customer acquisition costs, or broader economic conditions.
Therefore, the findings identify patterns and areas for investigation rather than proving that a particular factor directly caused a business outcome.
📁 Project Files
Excel Workbook: Superstore_Analysis.xlsx
The workbook contains the raw dataset, calculations, PivotTables, analysis sheets, formula-based metrics, and interactive dashboard used throughout this project.
🏁 Conclusion
This project demonstrates how Microsoft Excel can be used as an end-to-end data analysis and business intelligence tool.
Starting with raw transactional data, I transformed the dataset into structured analyses, calculated business metrics, interactive visualizations, and an executive-style dashboard.
The analysis identified meaningful differences in regional performance, product profitability, customer contribution, sales trends, and discount-related margins.
The project demonstrates my ability to move beyond spreadsheet manipulation and use data to identify business problems, communicate insights, and support data-driven decision-making.
