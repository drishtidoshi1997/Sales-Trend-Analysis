# Sales-Trend-Analysis:
A comprehensive business intelligence solution analyzing retail sales performance across the United States

🎯 Project Overview
This project delivers actionable insights into Adidas sales performance across multiple retail channels, helping stakeholders make data-driven decisions on inventory management, regional expansion, and seasonal planning strategies.
Business Questions Addressed:

How do sales trends vary among retailers across different cities?
How do seasonal fluctuations impact retailers' business performance?

📈 Key Insights & Findings

🏆 Top Performer: Sports Direct ranked #1 with highest profit ratio (0.42) among 6 major retailers
🌆 Revenue Leader: New York City contributed 18% of total profits ($6.4M), outperforming all other cities
📉 Seasonal Impact: Q4 2020 showed 35% sales decline (COVID-19 impact); Q4 2021 recovered with 42% growth
👟 Product Winner: Men's Street Footwear showed highest YoY growth (68% increase from 2020 to 2021)
💰 Profitability: Strong positive correlation (R² = 0.87) between total sales and operating profit
🛍️ Sales Channel: Online sales method showed 23% higher profit margins compared to outlet sales

🗂️ Dataset Information
AttributeDetailsRecords9,649 transactionsTime PeriodJanuary 2020 - December 2021Geographic Scope500+ cities across 5 US regionsRetailers6 major retail chainsProducts6 categories (Men's/Women's Apparel, Athletic & Street Footwear)Revenue Range$0 - $825,000 per transaction
Data Source: Adidas Sales Dataset - Kaggle
🛠️ Technical Implementation
Tools & Technologies

Primary Tool: Tableau Desktop (Interactive Dashboard Development)
Secondary Tool: Power BI (Comparative Analysis)
Data Processing: Excel (Data Cleaning & Preprocessing)
Analysis Methods: Statistical Analysis, Trend Analysis, Correlation Analysis

Dashboard Features
✅ 7 Interactive Visualizations:

Text Table - Financial performance ranking with calculated fields (Profit Ratio & Rank)
Word Cloud - City-wise profit distribution with color encoding
Symbol Map - Geographic sales distribution across USA with bubble sizing
Dumbbell Chart - Year-over-year product performance comparison (2020 vs 2021)
Dual-Axis Chart - Quarterly sales trends with profit overlay
Scatter Plot - Sales vs. Profit correlation analysis with linear regression
Dynamic Filters - Retailer and Sales Method global filters for drill-down analysis

Calculated Metrics
tableauProfit Ratio = SUM([Operating Profit]) / SUM([Total Sales])
Retailer Rank = RANK([Profit Ratio], 'desc')
📊 Visualizations
Dashboard Overview
The dashboard employs a red-green color palette for intuitive profit/loss visualization and includes:

Interactive filters for retailer and sales method segmentation
Tooltips with detailed metrics (State, City, Sales, Profit, Units Sold)
URL actions for external reference links (Wikipedia for geographic context)
Responsive design optimized for standard screen resolutions

Key Visualizations Explained
1. Geographic Performance Map

Purpose: Identify high-performing cities and regional opportunities
Encoding:

Color intensity = Profit levels (Dark Green = Highest)
Bubble size = Units sold


Insight: New York dominates with largest bubble and darkest green

2. Seasonal Trend Analysis

Purpose: Track quarterly performance fluctuations
Design: Dual-axis (Bar for Sales, Line for Profit)
Insight: Clear COVID-19 impact in Q4 2020, strong recovery in 2021

3. Product Comparison (Dumbbell)

Purpose: Compare year-over-year product category growth
Design: Connected dots showing 2020 vs 2021 performance
Insight: Men's Street Footwear showed steepest growth trajectory

💡 Business Recommendations
Based on the analysis, key recommendations include:

Expand Operations in High-Performance Cities: Focus on New York, Charleston, and Miami for new store openings
Optimize Q4 Inventory: Increase stock levels for Men's Street Footwear during Oct-Dec period
Invest in Online Channels: Online sales show superior margins; consider digital marketing expansion
Regional Strategy Adjustment: South and West regions show untapped potential for market penetration
Product Portfolio: Prioritize Men's Athletic and Street Footwear lines based on consistent performance

