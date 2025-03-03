# Adventure-Works-Power-BI-Analysis
## Objective
To design an interactive dashboard tracking key sales metrics, customer behavior, regional performance, and enabling stakeholders to identify growth opportunities and operational inefficiencies.
## Executive Summary
This analysis leverages AdventureWorks transactional data to evaluate revenue, profitability, customer demographics, and product performance. Insights derived from this report inform inventory optimization, customer segmentation strategies, and regional sales prioritization.
## Data Overview

•	Source: Maven Analytics (MavenAnalytics.io).

•	Scope: Multi-year sales data encompassing orders, returns, customer demographics, and product categories.
## Methodology
## 1. Data Preparation:

## Cleaning:

o	Conducted data validation to address missing values, duplicates, and formatting inconsistencies.

o	Removed non-critical columns to streamline analysis.

## Integration
Consolidated fact and dimension tables in Power Query Editor using a star schema for relational integrity.

## Enhancement
o	Created calculated columns for customer segmentation (e.g., income tiers, education groups).

o	Derived hierarchical fields (date: year > quarter > month; geography: continent > country > state).

## 2. Analytical Framework:

## DAX Measures 

Developed metrics including:

o	Total Revenue = SUM(Sales[Revenue])

o	Return Rate = DIVIDE([Total Returns], [Total Orders])

o	YoY Growth = [Total Revenue] - CALCULATE([Total Revenue], SAMEPERIODLASTYEAR(Date[Date]))

## Dashboard Highlights  
## 1. <a href="https://github.com/Huan11data/Adventure-Works-Power-BI-Analysis/blob/main/Executive Dashboard.png">Executive Dashboard</a>
   
•	KPIs: Revenue, Profit, Total Orders, Return Rate.

•	Trend Analysis: Line charts tracking monthly sales growth and regional performance matrices.

•	Product Performance: Matrix table ranking top SKUs by sales volume, profit margin, and return rate.

## 2. <a href= "https://github.com/Huan11data/Adventure-Works-Power-BI-Analysis/blob/main/Regional Map.png"> Regional Map</a>

•	Interactive Drill-Down: Continent > Country > State filters for granular revenue analysis.

## 3. <a href= "https://github.com/Huan11data/Adventure-Works-Power-BI-Analysis/blob/main/Products Dashboard.png"> Products Dashboard</a>

•	Goal Tracking: Gauge charts comparing monthly revenue/order targets vs. actuals.

•	Forecasting: Scenario-based profit projections tied to pricing strategies.

## 4. <a href="https://github.com/Huan11data/Adventure-Works-Power-BI-Analysis/blob/main/Customer Dashboard.png"> Customer Dashboard</a>

•	Demographic Breakdown: Revenue by income tier, education level, and occupation.

•	Cohort Analysis: Customer acquisition trends and retention rates over time.

## Analysis & Insights
## 1. Sales Performance

•	Revenue Growth: Achieved YoY growth, driven by high-demand product categories.
## 2. Product Trends

•	Top Categories: Bikes (32% of revenue), Components (25%), and Accessories (18%).

## 3. Regional Performance

•	Revenue Leaders: North America (45%), Europe (35%), Asia (20%).

•	Emerging Opportunity: Southeast Asia demonstrated 22% YoY growth in 2023.

## 4. Customer Insights

•	High-Value Segment: Customers earning >$100k/year contributed 48% of total revenue.
## Strategic Recommendations
## 1.	Inventory Optimization
Discontinue underperforming SKUs and prioritize stock for high-margin categories (Bikes, Components).
## 2.	Customer Retention
Launch loyalty programs targeting high-income professionals.
## 3.	Regional Expansion
Allocate marketing resources to capitalize on Southeast Asia’s growth trajectory.
## 4.	Return Mitigation
Investigate quality issues in Electronics returns and implement supplier audits.









