## Sales & Property Analysis Dashboard
Power BI | Google BigQuery | SQL

###  Property Sales Analytics: Sales & Market Insights Dashboard

An interactive Power BI dashboard built to analyze property sales data using Google BigQuery as the data source, focusing on sales trends, pricing comparisons, regional performance, and key influencing factors in the real estate market.

### Purpose

This project is a Power BI–based sales analytics dashboard designed to analyze property purchase data from a seller’s perspective. It enables users to explore sales performance, pricing behavior, demand patterns, and regional insights using interactive visuals and KPIs.

### Tech Stack

The dashboard was built using the following tools and technologies:

• Power BI Desktop – Used to design interactive dashboards and visual reports.

• Google BigQuery – Cloud data warehouse used as the primary data source.

• SQL (BigQuery SQL) – Used for data understanding and transformation before analysis.

• Power Query – Data cleaning and preparation, including null handling and data type validation.

• DAX (Data Analysis Expressions) – Created measures for KPIs such as YoY sales growth, unit sales, and rolling 12-month sales.

• File Format – .pbix for report development.

## Data Source

Source: Property housing sales dataset uploaded to Google BigQuery

The dataset contains property purchase records related to housing sales, including:

Purchase price and offer price

Sales type and region

City and area information

Inflation rate, mortgage credit bond, and interest-related indicators

The data was loaded into Google BigQuery from CSV files and queried using SQL before connecting to Power BI.

### Features / Highlights
#### • Business Problem

Real estate developers, builders, and sellers need a clear understanding of:

Sales performance across regions

Price variations between offer and purchase values

Demand and pricing trends over time

Key factors influencing property purchases

Raw transactional data makes it difficult to identify actionable insights without proper visualization.

#### • Goal of the Dashboard

To build an interactive sales analytics dashboard that:

Analyzes property sales from a seller’s perspective

Tracks YoY sales growth and recent performance

Compares pricing metrics across regions and sales types

Identifies key influencers affecting property purchases

#### • Data Preparation & Transformation

Connected Google BigQuery to Power BI using Import mode

Performed data cleaning in Power Query:

Replaced null values in City with “Unknown”

Replaced null values in Inflation Rate and Mortgage Credit Bond with their most frequent values

Validated data types and ensured consistency for reporting

#### • Walkthrough of Key Visuals
#### Page 1: Sales Performance Overview

Line Chart: YoY Sales Growth by Sales Type

Scatter Plot: Offer Price vs Purchase Price

Bar Chart: Median Sales Price Change by Region

Cards:

Units Sold (Latest Year & Quarter)

Last 12 Months Sales

#### Page 2: Regional & Pricing Analysis

Bar Chart: Total Sales by Region

Table: Total YTD Sales with Purchase Price and Date

Donut Chart: Average Price per SQM by Region

Key Influencer Visual: Purchase analysis explained by Age

Bar Chart: Offer-to-SQM Ratio by Sales Type

#### Page 3: Comparative & Trend Analysis

Clustered Bar Chart: Average Offer Price vs Purchase Price by House Type

Clustered Bar Chart: Inflation Rate, Interest Rate, Mortgage Yield by House Type

Line & Stacked Column Chart:

Average SQM by House Type

Average SQM Price Trend

Slicers Added: Area, City, Sales Type, Region (with search functionality)

#### • Business Impact & Insights

Sales Strategy: Helps sellers understand which regions and house types perform best

Pricing Analysis: Identifies gaps between offer price and final purchase price

Market Trends: Tracks YoY sales growth and recent performance

Decision Support: Enables data-driven decisions for pricing, targeting, and sales planning

### Screenshots 

Add dashboard screenshots here

![Sales Dashboard Preview](https://github.com/DDakave/Sales-Market-Insights-Dashboard/blob/main/House%20Market%20Overview%20New.png,
https://github.com/DDakave/Sales-Market-Insights-Dashboard/blob/main/SALES%20PERFORMANCE.png,
https://github.com/DDakave/Sales-Market-Insights-Dashboard/blob/main/COMPARATIVE%20%26%20TREND%20ANALYSIS.png)
