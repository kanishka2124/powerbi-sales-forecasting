# 📱 Power BI Sales Forecasting & Customer Analytics

## 📌 Project Overview

This project analyzes mobile phone sales data in Power BI to identify sales trends, customer behavior patterns, product performance, and revenue drivers.

The solution combines data modeling, DAX measures, time-series forecasting, customer segmentation, product ranking, and what-if simulation to support business decision-making.

## 🎯 Objectives

- Analyze sales and revenue trends over time
- Build a structured Power BI data model using a star schema
- Create reusable DAX measures for KPIs and time intelligence
- Segment customers by demographic and behavioral attributes
- Compare brand and product performance
- Forecast future revenue and unit sales
- Evaluate pricing and demand scenarios using what-if parameters

## 🛠️ Tools & Techniques

- Microsoft Power BI
- Power Query
- DAX
- Star Schema Data Modeling
- Time Intelligence
- Customer Segmentation
- Sales Forecasting
- Top-N Analysis
- What-If Parameters
- Data Visualization

## 🗂️ Data Model

The Power BI model follows a star schema with:

- FactSales
- Date dimension
- Product dimension
- Customer dimension
- Location dimension
- Payment dimension

The Date table was configured to support time-intelligence calculations such as YTD, YoY growth, and seasonality analysis.

## 📊 Key Measures & Calculations

The dashboard includes measures for:

- Total Revenue
- Total Units Sold
- Average Price per Unit
- Revenue YTD
- Revenue YoY %
- Units Seasonality Ratio
- Customer and payment-method shares
- Brand and product rankings
- Dynamic Top-N analysis

## 🔮 Forecasting

Power BI’s built-in forecasting tool was applied to monthly revenue and unit-sales data.

The forecasting approach used:

- Monthly aggregated sales data
- Exponential smoothing
- Automatic seasonality detection
- Short-term forecast horizons
- Confidence intervals

## 👥 Customer Segmentation

Customer behavior was analyzed by:

- Age group
- Gender
- Payment method
- Geography

The analysis identified high-value customer segments and helped compare purchasing behavior across groups.

## 📱 Product & Brand Analysis

Product analysis compared:

- Revenue by brand
- Units sold
- Average price
- Product rankings
- Pricing vs revenue relationships

A dynamic Top-N parameter was used to allow flexible comparison of top-performing products and brands.

## 🧪 What-If Simulation

Interactive parameters were created to simulate changes in:

- Product prices
- Units sold

The model estimated the resulting impact on revenue to support scenario analysis and business planning.

## 🔍 Key Insights

- Sales showed recurring seasonal and weekly patterns.
- Certain age groups contributed a larger share of total revenue.
- High unit sales did not always correspond to the highest revenue.
- Digital payment methods were among the most frequently used.
- The what-if analysis suggested that changes in sales volume could have a stronger proportional impact on revenue than equivalent price changes.

## 💡 Business Value

The dashboard provides a consolidated view of sales performance, customer behavior, product trends, and future sales expectations.

It can support decisions related to:

- Inventory planning
- Marketing strategy
- Customer targeting
- Product positioning
- Pricing decisions
- Revenue forecasting

## 👤 Author

**Kanishka Skandaraj**  
Master of Data Analytics Candidate  
University of Niagara Falls Canada
