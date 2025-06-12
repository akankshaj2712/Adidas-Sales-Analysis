
# Adidas Sales Analysis Dashboard using Tableau and SQL

# 📊 View the interactive Tableau dashboard:
[Open Dashboard](https://public.tableau.com/app/profile/akanksha.jondhale/viz/AdidasSalesAnalysis_17497079527430/Sales_Dashboard)

# 📌 Overview
This project delivers a comprehensive data-driven analysis of Adidas’s U.S. sales performance using Tableau, focusing on optimizing profitability, identifying high-performing retailers, and evaluating sales channels and product strategies. The dashboard consolidates insights to support business decisions regarding pricing, product lifecycle, and regional retail performance.

# 🛠️ Tools & Technologies
Tableau Desktop

Data Wrangling in Tableau (Calculated Fields, FIXED LOD, RANK, INDEX)

Geospatial Visualization

KPI Dashboard Design

# 📂 Dataset
The dataset contains Adidas retail sales records with columns such as:

Region, State, Product, Retailer, Sales Method

Units Sold, Price per Unit, Operating Profit, Operating Margin

Calculated fields: Total Sales, COGS, Profit Margin, Price Sensitivity

# ❓ Business Questions & Insights
🔹 Q1. How does price sensitivity vary among product categories, and what is its impact?
Created a scatter plot to compare Operating Margin vs. Price Sensitivity

Found that Men’s and Women’s Street Footwear drive high sales due to high sensitivity

Low sensitivity products require premium pricing or targeted positioning

🔹 Q2. What are the true costs (COGS) of selling Adidas products?
Built bar charts and maps for COGS vs. Total Sales

Found high COGS in West region possibly due to logistics/import duties

Identified categories like Women’s Athletic Footwear with better cost efficiency

🔹 Q3. How do product lifecycles impact sales strategy?
Used line charts and trend analysis by quarter

Identified lifecycle phases (Intro, Growth, Maturity, Decline) using sales volume and margin trends

Example: Men’s Street Footwear showed a decline trend with shrinking margins (from 50% to 30%)

🔹 Q4. How do sales vary over time by product category?
Built time series and area charts

Apparel shows strong seasonal peaks

Street Footwear maintains consistent year-round demand

Athletic Footwear surges during New Year (fitness trend)

🔹 Q5. What factors contribute to high total sales for retailers?
Scatter plot and ranking analysis revealed that:

Retailers like West Gear and Foot Locker efficiently convert sales into profit

Walmart and Kohl’s show high sales but weak profitability, indicating efficiency issues

Key factors: channel strategy, regional presence, margin control

🔹 Q6. Which sales methods are most effective across regions?
Created a filled map + stacked bar chart by Sales Method and Region

Found:

South excels online, but underperforms in-store

West shows balanced performance across all methods

Southeast lacks in-store strength, suggesting opportunity

# 📊 Dashboard Highlights
💡 Filled Maps: Show dominant Retailer + Sales Method by state

🧠 FIXED LOD and RANK logic: To dynamically label top performers per region

📈 Trend Lines & Seasonal Peaks: Track demand shifts during recovery phase

📌 Profitability Heatmaps: Visualize operating margins by region/product

📦 Lifecycle Analysis: Flagged early indicators of product decline

# ✅ Key Outcomes
Supported regional strategy decisions based on product and channel performance

Enabled cost optimization focus for West region (highest COGS)

Flagged declining product lines for strategic withdrawal or rebranding

Recommended expanding in-store presence in underperforming areas like the Southeast

