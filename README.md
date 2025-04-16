# Sales-Trend-Analysis-Using-Aggregations

Pizza Sales Analysis - MySQL Project

Overview
This project analyzes pizza sales data using MySQL queries to gain insights into revenue, popular pizza types, order patterns, and category distributions.

Key Insights
- **Total Revenue**: $817,860 from all pizza sales
- **Most Popular Size**: Large (L) pizzas with 18,526 orders
- **Top 5 Pizzas**: Classic Deluxe, Barbecue Chicken, Hawaiian, Pepperoni, and Thai Chicken
- **Busiest Hours**: Peak ordering occurs between 12 PM - 2 PM and 5 PM - 7 PM
- **Category Distribution**: Supreme and Veggie categories have the most varieties (9 each)

Technical Implementation
- Utilized SQL functions: `SUM()`, `COUNT()`, `AVG()`, `HOUR()`
- Applied SQL clauses: `GROUP BY`, `ORDER BY`, `JOIN`
- Implemented window functions with `RANK()` for category analysis
- Calculated metrics like average daily pizza orders (138.47 pizzas/day)

Usage
The queries demonstrate how to:
1. Calculate total sales revenue
2. Identify popular products and sizes
3. Analyze temporal ordering patterns
4. Examine category distributions
5. Rank products by revenue within categories

