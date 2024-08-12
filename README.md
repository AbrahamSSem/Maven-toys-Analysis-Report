# Maven-toys-Analysis-Report
This report analyzes Maven Toys' sales from Jan 2022 to Sep 2023 to uncover key insights on top profit-driving products, seasonal sales trends, inventory management, and the impact of out-of-stock items. It uses Power Query and DAX for actionable insights to enhance profitability and efficiency.

# Project Objective & Scenario
As a newly hired Data Analyst at Maven Toys – a fictitious chain of toy stores in Mexico – I was tasked with creating a comprehensive analysis report that addresses the following key questions:

## Which product categories drive the biggest profits? Is this the same across store locations?
Can you identify any seasonal trends or patterns in the sales data?
Are sales being lost due to out-of-stock products at certain locations?
How much money is tied up in inventory at the toy stores? How long will it last?
This analysis aims to help upper management enhance profitability, improve operational efficiency, and better meet customer needs.

Data Overview
The analysis is based on transactional sales data from January 2022 to September 2023, along with product, inventory, and store data. Four CSV files were loaded into Power Query, cleaned, and then modeled in Power Pivot for in-depth analysis.

# Key Insights
### 1. Profit Drivers by Product Category and Location
Overall Profit Leaders: Toys and Electronics are the biggest profit drivers, accounting for 51.83% of total profits from January 2022 to September 2023. Within Toys, Action Figures and Lego Bricks are particularly strong, with profit margins of 32.21% and 27.67% respectively.
2023 Trends: In 2023, Arts and Crafts lead with $480,405 in profits, slightly ahead of Toys at $470,503.
Location-Specific Insights: Electronics dominate at Airport and Commercial locations, while Toys lead in Downtown and Residential areas.

### 2. Seasonal Sales Trends
Yearly Trends: Sales in 2023 consistently outperformed 2022, with peaks in May and December, likely due to holiday or promotional events.
Seasonal Dips and Opportunities: Sales tend to dip between June and September, coinciding with summer and back-to-school periods in Mexico. This suggests an opportunity for targeted campaigns during these months.

### 3. Impact of Out-of-Stock Products on Sales
Inventory Gaps: 24 stores carry fewer than the full set of 35 products, mostly in Downtown areas.
Low Impact on Revenue: The missing products in these stores are not top earners, collectively accounting for less than 0.5% of total revenue from January 2022 to September 2023.
Optimization Opportunity: The top-performing stores don't necessarily carry full inventory, indicating a need to optimize product mix rather than ensuring all products are stocked in every store.

### 4. Inventory Value and Turnover
Current Stock Levels: The total Stock on Hand (SOH) is 29,742 units across all locations, valued at $300,210.
Inventory Turnover Period (ITP): The ITP is 13 days, meaning it would take just 13 days to sell through current inventory, signaling efficient inventory management.
Stock Cover (SC): The SC is 17 days, suggesting some discrepancies in stock levels across locations.

# Recommendations and Suggestions
- Focus on Electronics: Despite a decline in sales, Electronics remains a high-margin category. Investigating and addressing the causes of this decline could improve overall profitability.
- Seasonal Marketing: Consider running campaigns during the June-September period to capitalize on summer and back-to-school events.
- Optimize Inventory Mix: Rather than stocking all products in every store, focus on optimizing the product mix based on local demand to enhance sales performance.




