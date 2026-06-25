# E-Commerce-Performance-Analysis
### Prepared by: **Emeka Victor Agbo (Senior Data Analyst)**
### Audience: **Leadership, Operations, Marketing**
### Objective: **Provide a unified, insight driven view of company performance across Revenue, Operations, and Marketing**

## Table of Contents
   - [Introduction](#introduction)
   - [Project Request](#project-Request)
   - [Executive Summary](#Executive-Summary)
   - [Dataset](#dataset)
   - [Data Cleaning & Transformation](#data-cleaning--transformation)
   - [Key Insights & Findings](#Key-Insights-&--Findings)
   - [Dashboard](#dashboard)
   - [Recommendations](#recommendations)

     
## [Introduction](#introduction)
### Introduction
This project analyzes the performance of a fashion e-commerce business using transactional, customer, and web activity data.
The objective is to transform raw data into actionable insights that support decision-making across leadership, operations, and marketing teams.
The analysis covers the period 2019–2026, with over 181,000 transactions, providing a comprehensive view of business performance, customer behavior, and operational efficiency.

### Business Context
The business operates as an online fashion retailer, similar to companies like ASOS or Zalando, managing end-to-end e-commerce operations.
Its core activities include:
-	Product catalog management (categories, brands, departments)
-	Customer orders and transactions
-	Inventory and product cost tracking
-	Distribution center operations for order fulfillment
-	Website activity (traffic sources, sessions, user behavior)
As the business grows, it faces increasing complexity in understanding performance across multiple areas.
Key challenges include:
-	Limited visibility into revenue and profitability trends
-	Difficulty identifying top-performing vs underperforming products
-	Inefficiencies in distribution center operations
-	Lack of clarity on marketing effectiveness and customer acquisition channels
To remain competitive, the business requires a data-driven approach to monitor performance and identify opportunities for improvement

## [Project Request](#project-Request)
###  Project Overview
This project delivers a data analytics solution through the design of three interactive dashboards, each tailored to a specific business function:
-	Executive (Strategic View)
-	Operations (Performance & Efficiency)
-	Marketing (Customer & Channel Insights)
Using SQL (BigQuery) for data extraction and transformation, and Power BI for visualization, the project focuses on:
-	Analyzing revenue, profit, and growth trends
-	Evaluating product and distribution performance
-	Understanding customer behavior and traffic sources
-	Connecting marketing activity to revenue outcomes
The goal is to enable stakeholders to monitor performance, identify issues, and make informed decisions quickly.

### Business Objective
The primary objective is to provide clear, actionable insights through structured dashboards that support different teams across the organization.
These dashboards enable stakeholders to:
-	Monitor overall business performance
-	Improve operational efficiency
-	Evaluate marketing effectiveness
-	Support strategic and tactical decision-making

### Dashboard Breakdown
**Executive Dashboard**
Sales Performance Overview (Strategic Level)
Purpose:
Provides leadership with a high-level view of overall business performance to guide strategic decisions.
Key Business Questions:
-	How is revenue performing over time (monthly, yearly)?
-	Is the business profitable?
-	Are we experiencing growth or decline?
-	Which categories and distribution centers drive performance?
-	What are the main customer acquisition sources?
**Key Metrics:**
-	Total Revenue
-	Total Profit
-	Profit Margin (%)
-	Total Orders

 ### Operations Dashboard
Operational Performance & Efficiency
Purpose:
Enables the operations team to monitor product performance and optimize distribution efficiency.
Key Business Questions:
-	Which products generate the highest sales volume?
-	Which products have high return rates?
-	Which distribution centers are underperforming?
-	What customer segments (e.g., gender) drive product demand?
**Key Metrics:**
-	Total Units Sold
-	Total Orders
-	Total Customers
-	Orders by Status (Shipped, Delivered, Returned)
-	Distribution Center Performance
-	Active Products

###  Marketing Dashboard
Customer & Channel Performance
Purpose:
Analyzes how marketing efforts translate into traffic, conversions, and revenue.
Key Business Questions:
-	Where are customers coming from?
-	Which traffic sources generate the most revenue?
-	Which channels drive the highest conversions?
-	What customer segments are most valuable?
**Key Metrics:**
-	Total Website Sessions
-	Traffic by Source
-	Revenue by Traffic Source
-	Orders by Traffic Source
-	Customer Demographics (e.g., Gender)

###  Expected Outcome
By implementing these dashboards, the business will be able to:
-	Track revenue, profit, and growth trends effectively
-	Identify top-performing and underperforming products
-	Improve distribution and operational efficiency
-	Understand marketing performance and ROI
-	Make faster, data-driven decisions with confidence


# [Executive Summary](#Executive-Summary)

Our business continues to show **solid revenue growth**, stable **profitability**, and strong **operational throughput** across regions and channels. Revenue reached **$11M**, supported by **$6M profit** and a **52% margin**, showing that our core markets and product lines remain healthy. Operational activity is strong with **125K orders, 221 active products**, and **9 distribution centers**, although performance varies by center. On the marketing side, **Email and AdWords** remain our highest‑value traffic sources, driving most of the **$4.5M–$4.2M** revenue contribution. Customer engagement is balanced across gender and browsers, with **Chrome** dominating usage.

Overall, the business is performing well, but the dashboards highlight clear opportunities to improve distribution efficiency, reduce cancellations, and optimize marketing spend toward the highest‑return channels.

### Tools & Technologies
-	SQL (Google BigQuery) – Data extraction and transformation
-	Power BI – Data visualization and dashboard development
-	Excel – Data validation and exploratory analysis

   ## [Dataset](#dataset)
   ### Data Source
     - Data Source:  E-commerce store 
     - Time: 2019-2026 Records: 226,984 Transactions
     
   ### Preview of Bigquery Raw Data
![image alt](preview_bigquery_raw_data.png)

## [Data Cleaning & Transformation](#data-cleaning--transformation)
 

#  [Key Insights & Findings](#Key-Insights-&--Findings)
 ## Strategic Sales Performance Findings
### Revenue & Profit Trajectory  
Revenue reached **$11M**, with profit at **$6M** and a **52%** margin. Last **12‑month** revenue stabilizes around **$4M**, while profit holds near **$2M**.
Insight:  
The business is in a steady but not accelerating growth phase. The **YoY** and **MoM** indicators show flat **YoY** and declining **MoM**, signaling momentum loss despite strong absolute numbers.
Revenue & Profit Trends **(2019–2026)**  
**Recommendation:**
Prioritize growth‑driving initiatives (new markets, product expansion).
### Market Contribution  
China contributes **$3.8M, USA $2.2M, Brazil $1.4M, Spain $0.7M, South Korea $0.6M.**
Insight:  
The business is over‑dependent on China and the USA **(combined 55%+)**. This creates concentration risk and limits resilience.
**Recommendation:**
Build market diversification strategy targeting mid‑tier markets (Spain, Korea).

### Product Profitability  
Top profit drivers: The **North Face, Canada Goose, NIKE WOM, Nobis Men’s**.
Insight:  
Profit is heavily driven by premium outerwear, indicating strong brand affinity and pricing power.
Dashboard Page: Executive → Profit by Product  
**Recommendation:**
Expand premium product lines and bundle offers.
### Department Performance 
**Men: $5.8M, Women: $5.0M** - nearly balanced.
Insight:  
Both segments are strong, but men slightly outperform.
**Recommendation:**
Deepen segmentation (age, region, product category).
Identify micro‑segments with highest conversion potential.
![marketing dashboard](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Executive_DashBoard.png)

## Performance & Efficiency Findings
2.1 Distribution Center Throughput
Finding:  
Centers 6 and 9 lead with 24 items each; Center 10 is lowest at 8 items.
Insight:  
There is a capacity imbalance across the network. Underperformance at Center 10 may cause delays, higher shipping costs, or stockouts.  
Recommendation:
Conduct root‑cause analysis on Center 10 (staffing, inventory, routing).
Reallocate inventory and workload to balance throughput.
### Product Movement & SKU Efficiency
Finding:  
Women’s apparel dominates movement:

Skater Mini Skirt (2)

American Eagle (1)

Short Satin (1)
Insight:  
Women’s apparel drives high SKU velocity, but SKU count is low — indicating narrow assortment.
Dashboard Page: Operations → Items by Product  
Recommendation:

Expand high‑velocity women’s SKUs.

Introduce SKU rationalization to remove low‑movement items.

Add return rate per SKU to detect quality issues.

### Monthly Order Flow
Finding:  
Monthly orders:

Complete: 45,268

Shipped: 54,158

Processing: fluctuates
Insight:  
There is a gap between shipped and completed orders, suggesting reverse logistics, cancellations, or pending confirmations. 
### Gender‑Based Revenue
Finding:  
Male: $4.8M, Female: $3.8M.
Insight:  
Men generate more revenue, but women drive higher SKU diversity.
Dashboard Page: Operations → Revenue by Gender  
Recommendation:
Tailor inventory planning by gender.
identify gender‑specific traffic sources.
![operation](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/operations_DashBoard.png)

## Customer & Channel Insights
### Traffic Source Revenue
Finding:

- Email: $4.5M

- AdWords: $4.2M

- Facebook: $1.2M

- YouTube: $0.6M

- Organic: $0.3M  
Insight:  
Email and AdWords dominate revenue, showing high ROI and strong customer retention. Organic traffic is underperforming, signaling weak SEO.
Recommendation:
- Increase email automation and segmentation.

- Optimize AdWords bidding for high‑value segments.

- Invest in SEO content to reduce paid dependency.

### Engagement & Events
Finding:  
All top metrics show 222 (events, traffic, browser count).
Insight:  
This indicates stable but flat engagement - no growth signals.
Marketing - Engagement Metrics  
Recommendation:
- Introduce A/B testing for landing pages.

- Add conversion funnel visualization to identify drop‑off points.

### Browser Behavior
Finding:  
Chrome dominates with 2.2M users, followed by Firefox and Safari.
Insight:  
Chrome optimization should be prioritized; Safari users may face UX issues.
 Marketing - User by Browser  
Recommendation:
Conduct cross‑browser performance testing.
Improve Safari mobile experience to capture lost conversions.

### Geographic Engagement
Finding:  
USA leads with 52 browser interactions, followed by China and Japan.
Insight:  
Marketing engagement aligns with Executive revenue patterns — strong in USA and China.  
Recommendation:
Localize campaigns for Japan and Brazil to unlock growth.

### Cross‑Dashboard Insights (Where the Story Connects)
Marketing - Executive
Traffic sources with highest revenue (Email, AdWords) align with stable revenue trends.
Recommendation:  
Scale campaigns for top‑performing products identified in Executive dashboard.

### Operations - Executive
Distribution center inefficiencies may be contributing to MoM revenue decline.

### Marketing - Operations
Gender traffic patterns should inform inventory planning.
Recommendation:  
Align SKU assortment with gender‑specific demand signals.
![marketing dashboard](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Marketing_Dashbaord.png)


## [Recommendations](#recommendations)

### Strategic Recommendations 
1. Accelerate Growth in High Performing Markets
-	Expand localized campaigns in China and the U.S.
-	Introduce region specific product bundles and promotions.
2. Improve Operational Efficiency
-	Re-balance workload across distribution centers.
-	Investigate root causes of high return rates.
-	Enhance forecasting for women’s apparel.
3. Optimize Marketing Spend
-	Increase investment in Email and AdWords.
-	Reduce low performing social spending.
-	Improve attribution modeling to better track channel ROI.
4. Strengthen Customer Experience
-	Improve product detail accuracy to reduce returns.
-	Enhance mobile and Chrome browser performance.
-	Personalize user journeys based on traffic sources.
## Final Outcome
By integrating insights from all three dashboards, the business now has a clear, actionable view of its performance across Sales, Operations, and Marketing.







     


