# File Title: Zomato

This was my Final project for the TripleTen Business Intelligence Analytics Program. It was an independent project designed to showcase what I have learned throughout the TripleTen Program. The purpose was to complete the Zomato onboarding project to showcase analytical skills to the mock company.

### Table of Contents for Repository Artifacts
| File Number | Title | Description |
| :-----------: | ----------- |----------- |
| 1 | [Final Project Report Plan](https://github.com/jacobirsan/README.md/blob/cf25a553eee662cdd60b5d561baaa57958140394/Zomato/TripleTen%20Final%20Project%20Plan-%20Jacob%20Irsan.pdf) | A .pdf file with the written report for this project. |
| 2 | [Final.pdf](https://github.com/jacobirsan/README.md/blob/cf25a553eee662cdd60b5d561baaa57958140394/Zomato/Final%20Project%20Report%20-%20Jacob%20Irsan.pdf) | A .pdf file with the written report for this project. |
| 3 | README.md | This current page with all relevant information about the project, just past the Table of contents. |
| 4 | [View Dashboard on Tableau](https://public.tableau.com/app/profile/jacob.irsan/viz/Book1_17272607929740/ZomatoSalesAnalysisDashboard?publish=yes) | A view of full dashboard that presented for this project. |


#### Description:
- This was a Sales Analysis.
- 2 pages in Power BI.
- Includes KPI cards, line charts, map charts, bar charts, and trend analysis.

#### Assumptions:
- The provided test datasets are accurate, complete, and consistent.
- Missing values or inconsistencies are minimal and will not significantly impact the analysis.
- The column descriptions accurately reflect the content of each table.
- The provided tables (orders and restaurants) contain all the necessary information for the chosen analysis.
- Zomato's business context and industry trends are considered while interpreting the data.

#### Process:
I first learned of the problem presented in its entirety and its requirements for approval.
Then, I chose software and created my first submission, the "Decomposition Plan".
After, I analyzed the data and created visualizations and dashboards for a second submission.
Lastly, I presented my findings in a report as my 3rd and final submission piece.

#### Findings:
- Overall Sales: Zomato has shown strong overall sales so far around $986,565,016 but is facing a concerning downward trend towards the end of the analyzed period.
- Regional Performance: Tirupati is a key region for sales, and there are opportunities to grow in other regions.
- Top Restaurants: Brands like Domino's are clear leaders in sales, but there's an opportunity to lift sales for smaller restaurants.
- AOV Decline: The decrease in AOV over time suggests that Zomato should focus on strategies to encourage customers to spend more per order.

#### Recommendations:
1. Focus on High-Performing Regions:Apply successful tactics from Tirupati (e.g., popular restaurant promotions, delivery efficiency) to underperforming cities.
2. Target Under performing Regions:Launch region-specific campaigns to improve sales in lower-performing regions.
3. Increase Average Order Value:Implement cross-selling, upselling, and bundle deals to encourage larger orders and reverse the AOV decline.
4. Support Smaller Restaurants:Provide more visibility or targeted promotions to help smaller restaurants increase their sales.
5. Analyze Pandemic Effects: Further investigate the sales dip in 2020, possibly related to external factors like the COVID-19 pandemic, and develop strategies to recover lost sales

#### Additional Information:
## Data Log Summary:
1. KPIs Setup:
- Average Order Value (AOV): I created a calculated field to measure the average revenue generated per order. This helps in understanding customer spending behavior.
- Total Sales: I set up a calculated field to sum the total sales across all orders. This provides an overall picture of revenue.
- Number of Orders: A simple count of all completed orders, giving us a clear idea of the total order volume. 2. DataConnections:
- I connected orders.csv with restaurant.csv using the R Id on orders.csv and Id on restaurants.csv. Before doing this, I converted the R Id in the orders file from text to integer format for consistency.
- The join used was a Left Join, ensuring that all restaurant data was included, even if they had no matching orders.
