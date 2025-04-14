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

Removed outliers (possibly using Z-score or IQR)

Scaled/normalized variables as needed

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

