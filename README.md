# Superstore Business Intelligence Analysis — Week 3

## Project Overview

The project builds on the Superstore Business Intelligence dashboard developed in Week 2. The objective was to move beyond basic descriptive analysis and develop a more advanced, interactive dashboard focused on sales performance, profitability, regional performance, customer contribution, discounting, and business decision-making.

The analysis was developed using Microsoft Power BI, with DAX measures and interactive dashboard features used to transform the Superstore dataset into actionable business information.

## Business Objective

The analysis was designed to help answer key business questions such as:

* How is overall sales and profit performance changing?
* Which product categories and sub-categories are most and least profitable?
* Which products are contributing to weak profitability?
* Which regions perform most efficiently?
* Which regions generate higher-value orders?
* Which customer segments contribute most to profit?
* Which customers generate the highest sales and profit?
* How are discounts distributed across categories?
* Is higher discounting associated with weaker performance?
* Where should management focus improvement efforts?

## Dataset

The same dataset from Week 2 was retained to maintain continuity and allow the Week 3 analysis to build on the previous dashboard.

## Tools Used

* Microsoft Power BI — Dashboard development and data visualization
* Power Query — Data preparation and transformation
* DAX — Measures and business calculations
* Superstore Dataset — Source data

## Data Model and Date Analysis

A dedicated Date Table was created to support time-based analysis.

The Date Table was connected to the Superstore table through the Order Date. This relationship supported monthly trend analysis, yearly filtering, and time-based calculations. Interactive Year and Quarter slicers were also incorporated into the dashboard to allow users to analyse performance across different periods.

# Dashboard Structure

The final dashboard consists of four main sections:

* Sales & Profitability Dashboard
* Regional Performance Dashboard
* Customer & Discount Dashboard
* Business Problems, Insights and Recommendations

# 1. Sales & Profitability Dashboard

The Sales & Profitability section provides an overview of overall business performance and detailed analysis of product profitability.

### Key Performance Indicators

The dashboard contains six primary KPIs:

* Total Orders: 5K
* Sales Growth: 46.9%
* Total Sales: 2.3M
* Total Profit: 286.4K
* Total Customers: 793
* Profit Growth: 48.4%

These KPIs provide a quick snapshot of the company's overall performance.

### Monthly Sales vs Profit Trend

A combined monthly sales and profit trend was used to compare revenue performance with profitability over time.

The analysis shows that both sales and profit experienced strong overall growth, with sales growth of 46.9% and profit growth of 48.4%.

### Product and Sub-Category Profitability

The dashboard includes:

* Bottom 5 Products by Profit
* Top 5 Sub-Categories by Profit
* Bottom 5 Sub-Categories by Profit
* Furniture Sales vs Profit by Sub-Category
* Profit Margin by Category

These visuals were used to identify profitable areas as well as products and sub-categories requiring further investigation.

### Furniture Profitability Analysis

Furniture was investigated in greater detail because it generated relatively strong sales but had a significantly lower profit margin than the other major categories.

The Furniture sub-category analysis compares sales and profit across:

* Chairs
* Tables
* Bookcases
* Furnishings

This provides a more detailed view of the factors contributing to Furniture's weaker profitability.

# 2. Regional Performance Dashboard

The Regional Performance section examines how efficiently different regions generate sales and profit.

### Profit Margin by Region

Regional profit margins were compared to identify differences in profitability efficiency.

The results shown on the dashboard include:

* West: 14.94%
* East: 13.48%
* South: 11.93%
* Central: 7.92%

This shows a substantial difference between the strongest and weakest regional margins.

### Average Profit per Order

The average profit generated per order was compared across regions:

* West: 67
* East: 65
* South: 57
* Central: 34

The analysis indicates that the West generated the highest average profit per order, while Central recorded the lowest.

### Total Orders by Region

Order volume was also examined:

* West: 1,611
* East: 1,401
* Central: 1,175
* South: 823

This provides context when interpreting regional sales and profitability.

### Average Sales per Order

Average order value was compared across regions:

* East: 484
* South: 477
* West: 450
* Central: 427

This helps distinguish between regions generating performance through order volume and those generating higher-value individual transactions.

# 3. Customer & Discount Dashboard

The Customer & Discount section examines customer contribution, customer profitability, discount levels, and the relationship between discounting and performance.

### Profit by Customer Segment

Profit was compared across the three customer segments:

* Consumer: 134K
* Corporate: 92K
* Home Office: 60K

Consumer customers generated the highest overall profit among the three segments.

### Top 5 Customers by Sales

The dashboard identifies the five customers with the highest sales contribution.

The leading customers include:

* Tamara Chand
* Raymond Buch
* Adrian Barton
* Sanjit Chand
* Hunter Lopez

The visual allows high-sales customers to be identified and compared.

### Top 5 Customers by Profit

A separate ranking was created to identify the customers generating the highest profit.

This comparison is important because a customer generating high sales is not necessarily the same customer generating the highest profit.

### Average Discount by Category

Average discount was compared across the major categories:

* Furniture: 17.39%
* Office Supplies: 15.73%
* Technology: 13.23%

Furniture recorded the highest average discount among the three categories.

### Discount vs Sales by Sub-Category

A scatter plot was used to examine the relationship between discount levels and sales across sub-categories.

This provides an additional perspective for assessing whether increased discounting is associated with higher sales and whether the additional sales justify the discounting strategy.

# 4. Business Problems Identified

The dashboard highlights several business problems requiring attention.

### Furniture Profitability Gap

Furniture generated substantial sales but recorded only a 2.49% profit margin, making it significantly less profitable than Technology and Office Supplies.

The dashboard indicates that Furniture generated approximately $296.7K in sales but only about $7.17K in profit.

This suggests that pricing, discounts, costs, or product selection may be affecting profitability.

### Loss-Making Products

Several products and sub-categories recorded weak or negative profitability.

Tables, Bookcases, and Supplies were among the areas requiring attention.

These products should be reviewed to determine whether losses are associated with excessive discounts, high costs, pricing issues, or product-level performance.

### Central Regional Profitability Gap

Central recorded the lowest regional profit margin at 7.92% and the lowest average profit per order at approximately $34.

This indicates that the region requires further investigation despite having a relatively high number of orders.

# 5. Key Business Insights

### Strong Overall Growth

Sales increased by 46.9%, while profit increased by 48.4%, indicating positive overall business performance.

### Technology Leads Profitability

Technology recorded the highest category-level profit margin at approximately 17.40%, making it an important contributor to profitable growth.

### High Sales Do Not Guarantee High Profitability

The Furniture category demonstrates that strong sales performance does not necessarily translate into strong profitability.

### Furniture Requires Attention

Furniture recorded only a 2.49% profit margin, significantly below Technology and Office Supplies. The category therefore represents a major area for profitability improvement.

### Central Underperforms on Profitability

Central recorded the lowest profit margin and lowest average profit per order among the regions analysed.

### Consumer Segment Leads Profit Contribution

The Consumer segment generated approximately 134K in profit, making it the strongest contributor among the three customer segments.

# 6. Recommendations

### 1. Review Furniture and Tables

Management should review pricing, costs, discounts, and product mix within Furniture, particularly Tables and other weak-performing sub-categories.

### 2. Monitor Loss-Making Products

Loss-making products should be reviewed regularly to determine whether they should be repriced, have their costs reduced, receive lower discounts, or be reconsidered within the product portfolio.

### 3. Prioritise Technology

Technology should be considered for further growth investment because of its strong profit margin.

High-performing sub-categories such as Phones, Copiers, and Accessories can be prioritised where market demand supports expansion.

### 4. Investigate Central Region Performance

The Central region should be investigated to understand why its profit margin and average profit per order are significantly lower than other regions.

Management should review regional pricing, product mix, discounts, and operating costs.

### 5. Review Discount Strategy

Discount levels should be monitored alongside sales and profitability.

Discounts should be targeted toward products or customer groups where they generate sufficient additional sales without significantly reducing profit margins.

# 7. Key DAX Measures

The dashboard was supported by several DAX measures, including:

* Total Sales
* Total Profit
* Total Customers
* Total Orders
* Total Discount
* Sales Growth 
* Profit Growth 
* Average Sales per Order
* Average Profit per Order
* Profit Margin
* Loss-Making Orders
* Average Discount

These measures enabled the dashboard to move beyond basic aggregation into more meaningful business performance analysis.

# 8. Dashboard Design and Interactivity

The dashboard was designed with a focus on readability, consistency, and interactive exploration.

Key features include:

* KPI cards for high-level performance monitoring
* Bar and column charts for comparisons
* Line and column combination chart for time-based analysis
* Scatter plots for relationship analysis
* Year and Quarter slicers
* Consistent navigation between dashboard sections
* Structured page organisation
* Interactive filtering

The dashboard was also designed to avoid unnecessary duplication of Week 2 visuals. New visuals were selected where they provided a deeper or different perspective.

# 9. Project Outcome

The Week 3 Superstore analysis transformed the existing dashboard into a more advanced Business Intelligence solution.

The project moved from simply reporting sales and profit to investigating why performance differs across products, categories, regions, customers, and discount levels.

The analysis identified clear areas of strength, including:

* Strong overall sales and profit growth
* Technology profitability
* Consumer segment contribution
* Strong regional performance in the West

It also identified areas requiring attention, particularly:

* Furniture profitability
* Loss-making products
* Central regional performance
* Discounting strategy

The resulting dashboard provides stakeholders with a consolidated view of performance and highlights specific areas where further investigation and business action may be required.

## Conclusion

This Week 3 project strengthened my practical skills in Power BI, DAX, data modelling, time-based analysis, dashboard design, business intelligence, and data-driven decision-making.

The project demonstrated how a transactional dataset can be transformed into an interactive dashboard that not only reports what is happening but also helps identify where performance problems exist and where management attention should be focused.
