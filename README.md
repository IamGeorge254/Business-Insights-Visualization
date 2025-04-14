# Problem Statement
In a competitive and rapidly changing market, businesses often struggle to gain real-time visibility into sales performance, customer value, and engagement patterns. The absence of actionable insights hinders effective decision-making and limits opportunities for targeted marketing, customer retention, and revenue optimization.
## KPIs
- Total Quantity by Category

Measure of the total number of units sold per anonymized category.

- Total Value by Category

Monetary worth of sales across each anonymized category.

- Top-Performing Products

Products with the highest total value or volume sold.

- Top-Performing Businesses

Businesses generating the highest revenue.

- Sales Trends Over Time

Monthly or time-series visualization of total sales value (and optionally quantity) to understand seasonal patterns.

- Customer Segmentation (RFM Analysis)

Recency: How recently a customer made a purchase.

Frequency: How often they make purchases.

Monetary: How much money they spend.
## Steps in Your Process
- Data Cleaning & Preprocessing (Python)

Handled missing values, duplicates, data types

- Exploratory Data Analysis (EDA)

Analyzed trends, patterns, distributions

Visualized correlations and relationships

Identified business-relevant features

- SMOTE for Balancing

Applied SMOTE to oversample minority class (for better predictive modeling)

- Time Series Forecasting

Used models like ARIMA, Prophet, or others to forecast sales or customer trends

- Dashboard Design (Power BI)

Visualized KPIs like Sales, Top Products, RFM Segments

Enabled interactive filtering and storytelling

# Findings 
## Overall Business Performance
Total Revenue: 774K

Total Quantity Sold: 2 Billion units

Observation: High volume of sales but relatively modest revenue, suggesting bulk items may be low-cost or discounted.

## Top Categories
Category-75 dominates both in terms of quantity and value, significantly outperforming all other categories.

There is a noticeable disparity between categories; some contribute heavily to quantity but not necessarily to value.

## Top Businesses
Business-978e and Business-fe7d lead in terms of revenue contribution, with 28M and 27M respectively.

These top 5 businesses collectively play a key role in total revenue, possibly due to larger purchase volumes or premium products.

## Top Products
Product-e805 is the top performer with 0.27bn in value — a strong standout.

Products 8f75 and 66e0 follow, but there’s a sharp drop in value after the top 2, suggesting a product value concentration at the top.

## Time-Series Performance (Monthly Trends)
Sales peaked in November 2024 at 185M, possibly due to holiday or end-of-year demand.

Lowest sales occurred in March 2024 at 118M, indicating a potential seasonal dip.

Overall trend shows fluctuations with strong months in May, July, and November.

## Recommendations:
Capitalize on High-Performing Products like Product-e805 through marketing, bundling, or inventory prioritization.

Investigate underperforming months (March & December) to identify improvement opportunities or campaign needs.

Focus on Business-978e and fe7d for potential partnerships or targeted promotions to boost revenue.

Consider repricing or promoting low-performing categories to improve profitability balance.

# RFM Dashboard Insights
## Recency Analysis
Businesses like Business-d7a8, 153f, and 28da show high recency, meaning they purchased recently and are still engaged.

These businesses should be nurtured and targeted for loyalty programs or early-access deals, as they’re actively engaging with your services.

## Monetary Value Analysis
Business-978e and fe7d are top spenders, contributing nearly 30M each in revenue.

These businesses are your most valuable clients; consider offering them exclusive support, premium packages, or strategic partnerships.

Other strong contributors include 6068, 07de, and 7a03, indicating a cluster of reliable high-value businesses.

## Frequency Analysis
Business-978e also leads in purchase frequency, making them both high-frequency and high-monetary — a model loyal customer.

Businesses like 0e5b, 6068, 4fee, and 63d9 also show high frequency, even if their monetary value isn’t the highest. These can be nurtured to increase spend per transaction.

## Revenue by Month and RFM Business Type
Revenue is consistently driven by high-value businesses (blue bars), which dominate every month.

Medium-value businesses (orange bars) contribute much less across the year, showing a potential area for growth via targeted promotions or upgrades.

Highest revenue months: January and July, followed by October and May — potential for aligning marketing or sales campaigns with these peaks.

December revenue dips, possibly due to end-of-year slowdowns — consider running holiday or end-of-year campaigns to boost activity.

## Recommendations
Reward high-frequency, high-monetary customers like Business-978e with loyalty or VIP programs.

Re-engage low-recency businesses (not shown in top recency list) with win-back campaigns.

Upsell to high-frequency but low-monetary clients to increase their individual transaction value.

Analyze peak months (Jan, Jul, Oct) to understand what drove success — replicate strategies.

Introduce incentives for medium-value clients to transition them into high-value brackets.
