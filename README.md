# Coffee Shop Sales Analysis

#### Dashboard: https://public.tableau.com/views/CoffeeShopSalesDashboaord/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Introduction

This project performs a detailed exploratory data analysis (EDA) on a coffee shop's transaction records. The dataset includes item-level sales transactions containing information such as transaction date and time, product category, unit prices, and store locations. The goal is to derive actionable insights to support business strategy—especially regarding product performance, temporal sales patterns, and customer behavior.

## What I’m Trying to Find / Visualize and Why

The key goals of this project are:

- **Understand sales trends over time**: Identify high- and low-performing days and months.
- **Analyze customer behavior patterns**: When do customers buy the most? Which products are most popular?
- **Evaluate store performance**: Examine differences in performance across locations.
- **Product performance**: Determine which product types and categories generate the most revenue.
- **Uncover potential product associations**: Using association rule mining (Apriori) to detect items frequently bought together.

These insights can help optimize product placement, promotional campaigns, staffing, and inventory management.

## My Insights and Visualizations

Several visualizations were created, including:

1. **Daily Sales Trend**
   A line chart showing daily revenue to identify seasonal or weekly sales fluctuations.

2. **Sales by Day of the Week**
   A bar chart illustrating sales totals for each day, highlighting peak days (e.g., weekends or weekdays).

3. **Hourly Sales Distribution** _(implied from available features)_
   Identifies high-traffic hours for better workforce allocation.

4. **Top Products by Sales Volume and Revenue**
   Ranking of the most sold and highest grossing products.

5. **Store Location Performance**
   Revenue comparisons between different store locations.

6. **Market Basket Analysis** _(via Apriori algorithm)_
   Discovered common itemsets and generated association rules to explore cross-selling opportunities.

## What I Found

- **Peak days**: Sales tend to spike on weekends, with Friday and Saturday being the strongest performers.
- **Morning hours** are the busiest, especially for coffee products.
- **Gourmet brewed coffee and brewed chai tea** were among the most frequently purchased items.
- **Lower Manhattan store** showed the highest overall sales—likely due to high foot traffic.
- **Frequent itemsets** revealed associations like coffee being often purchased with pastries or specific teas, which can guide combo deals or store layout optimizations.

## Conclusion

This analysis uncovers key consumer habits and revenue drivers for the coffee shop. With clear patterns in product performance, time-based demand, and location-wise success, the business can make data-driven decisions to improve operations and marketing. Further analysis, including customer segmentation and time-series forecasting, could be beneficial for strategic planning.
