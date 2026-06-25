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

### Tools & Technologies
-	SQL (Google BigQuery) – Data extraction and transformation
-	Power BI - Data visualization and dashboard development
-	Excel - Data validation and exploratory analysis

   ## [Dataset](#dataset)
   ### Data Source
- Data Source:  E-commerce store 
- Time: 2019-2026 Records: 226,984 Transactions
     
   ### Preview of Bigquery Raw Data
![image alt](preview_bigquery_raw_data.png)
### Dataset Structure

#### ![Preview of Column Structure Click Here](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Folder/Table%20Structures%20and%20Relationship%20in%20Model.pdf)

**ERD Diagram**

![ERD](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Folder/ERD%20Diagram.png)

## [Data Cleaning & Transformation](#data-cleaning--transformation)
#### ![Biguery Data Cleaning Documentation Click Here](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Folder/Biguery%20data%20cleaning%20documentation..pdf)
#### ![Power Bi Transformation Click Here](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Folder/DATA%20TRANSFORMATION%20IN%20POWER%20BI.pdf)

# [Executive Summary](#Executive-Summary)

Our business continues to show **solid revenue growth**, stable **profitability**, and strong **operational throughput** across regions and channels. Revenue reached **$11M**, supported by **$6M profit** and a **52% margin**, showing that our core markets and product lines remain healthy. Operational activity is strong with **125K orders, 221 active products**, and **9 distribution centers**, although performance varies by center. On the marketing side, **Email and AdWords** remain our highest‑value traffic sources, driving most of the **$4.5M–$4.2M** revenue contribution. Customer engagement is balanced across gender and browsers, with **Chrome** dominating usage.

Overall, the business is performing well, but the dashboards highlight clear opportunities to improve distribution efficiency, reduce cancellations, and optimize marketing spend toward the highest‑return channels.

 
#  [Key Insights & Findings](#Key-Insights-&--Findings)
 ## Revenue & Profit Trajectory
Revenue reached **$11M**, with **$6M profit** and a **52% margin**. Over the last 12 months, revenue has held around **$4M**, while profit remains near **$2M**.

**Insight:**  
The business is stable but not accelerating. Year‑over‑year growth is flat, and month‑over‑month performance is declining. This means we are maintaining strong numbers, but momentum is slowing.

**Recommendation:**  
Focus on growth‑driving actions such as entering new markets, expanding product lines, and strengthening high-performing categories.

### Market Contribution
Top revenue contributors:

- **China:** $3.8M

- **USA:** $2.2M

- **Brazil:** $1.4M

- **Spain:** $0.7M

- **South Korea:** $0.6M

**Insight:**  
More than **55% of revenue comes from China and the USA**, creating dependency on two markets. This limits resilience if either market slows.

**Recommendation:**  
Develop a diversification plan targeting mid‑tier markets like Spain and South Korea to reduce concentration risk.

### Product Profitability
Top profit‑generating brands include **The North Face, Canada Goose, NIKE WOM, and Nobis Men’s**.

**Insight:**  
Premium outerwear is driving most of the profit, showing strong customer willingness to pay for high‑value brands.

**Recommendation:**  
Expand premium product offerings, introduce bundles, and explore cross‑selling opportunities.

### Department Performance

- **Men’s:** $5.8M

- **Women’s:** $5.0M

**Insight:**  
Both departments perform well, with men slightly ahead. This balance shows healthy demand across segments.

Recommendation:  
Deepen segmentation (age, region, category) to identify micro‑segments with the highest conversion potential.

## Operational Performance Findings
Distribution Center Throughput
- Centers **6** and **9** lead with **24** items each.

- Center **10** is lowest at **8** items.

**Insight:**  
There is a clear imbalance in workload. Underperformance at Center 10 may be causing delays, higher shipping costs, or stockouts.

**Recommendation:**  
Investigate Center 10’s bottlenecks (staffing, routing, inventory). Rebalance inventory and workload across centers.

### Product Movement & SKU Efficiency
Women’s apparel shows the highest movement:

- Skater Mini Skirt (2)

- American Eagle (1)

- Short Satin (1)

**Insight:**  
Women’s apparel has strong demand but a narrow SKU range. This limits assortment and potential revenue.

**Recommendation:**

- Expand high‑velocity women’s SKUs.

- Remove low‑movement SKUs to improve efficiency.

- Add return‑rate tracking per SKU to detect quality or fit issues.

### Monthly Order Flow
- **Completed orders:** 45,268

- **Shipped orders:** 54,158

**Insight:**  
The gap between shipped and completed orders suggests cancellations, returns, or pending confirmations. This affects revenue recognition and customer experience.

### Gender‑Based Revenue
- **Male:** $4.8M

- **Female:** $3.8M

**Insight:**  
Men generate more revenue, but women drive more SKU diversity. This should guide inventory planning.

**Recommendation:**  
Align stock levels and assortment with gender‑specific demand patterns.

## Marketing Performance Findings
**Traffic Source Revenue**

- **Email:** $4.5M

- **AdWords** $4.2M

- **Facebook:** $1.2M

- **YouTube:** $0.6M

- **Organic:** $0.3M

- **Insight:**  
Email and AdWords deliver the highest revenue and strongest ROI. Organic traffic is weak, showing limited SEO impact.

**Recommendation:**

- Strengthen email automation and segmentation.

- Optimize AdWords bidding for high‑value audiences.

- Invest in SEO to reduce reliance on paid channels.

### Engagement & Events
All major engagement metrics show **222** interactions.

**Insight:**  
Engagement is stable but not growing. This indicates a plateau in customer activity.

**Recommendation:**

- Run A/B tests on landing pages.

- Add a conversion‑funnel view to identify where users drop off.

### Browser Behavior
- **Chrome:** 2.2M users

- **Firefox:** 1.0M

- **Safari:** 0.8M

**Insight:**  
Chrome dominates usage. Safari users may be experiencing friction, especially on mobile.

**Recommendation:**  
Conduct cross‑browser testing and improve Safari performance to capture missed conversions.

### Geographic Engagement
- **USA** leads with **52** browser interactions, followed by China and Japan.

**Insight:**  
Engagement patterns match revenue patterns - strong in USA and China.

**Recommendation:**  
Localize campaigns for Japan and Brazil to unlock additional growth.

## Cross‑Dashboard Insights (Connecting the Story)
Marketing **«»** Executive
High‑revenue traffic sources (Email, AdWords) align with stable revenue trends.

Recommendation:  
Scale campaigns for top‑performing products identified in the Executive dashboard.

Operations **«»** Executive
Distribution center inefficiencies may be contributing to the month‑over‑month revenue decline.

Marketing **»«** Operations
Gender‑based traffic patterns should guide inventory planning.

**Recommendation:**  
Match SKU assortment with gender‑specific demand signals.


![marketing dashboard](https://github.com/bryan405/E-Commerce-Performance-Analysis-/blob/main/Marketing_Dashbaord.png)


## [Recommendations](#recommendations)

### Strengthen Revenue Growth & Reduce Momentum Loss
**Why:** Revenue and profit are stable but not accelerating; MoM performance is declining.

**Actions:**

- Launch targeted growth campaigns in months with historically low performance.

- Expand into mid‑tier markets (Spain, South Korea, Brazil) to reduce dependency on China and the USA.

- Introduce new premium product lines and bundles to leverage strong brand affinity.

- Use forecasting models to anticipate dips and activate promotions earlier.

### Reduce Market Concentration Risk
**Why:** 55%+ of revenue comes from China and the USA.

**Actions:**

- Build localized campaigns for Japan, Brazil, and Spain.

- Test product‑market fit for premium outerwear in emerging regions.

- Partner with regional distributors to accelerate entry into new markets.

### Improve Product Strategy & SKU Efficiency
**Why:** Profit is driven by a few premium brands; women’s apparel has high velocity but limited assortment.

**Actions:**

- Expand high‑performing SKUs in women’s apparel and premium outerwear.

- Conduct SKU rationalization to remove low‑movement items.

- Add return‑rate tracking per SKU to identify quality or sizing issues.

- Use customer segmentation to tailor product bundles by gender and region.

### Fix Distribution Center Imbalances
**Why**: Centers 6 and 9 are overloaded; Center 10 is underperforming.

**Actions:**

- Perform a root‑cause analysis on Center 10 (staffing, routing, inventory accuracy).

- Reallocate inventory and workload to balance throughput across all centers.

- Introduce operational KPIs (pick time, ship time, error rate) to monitor performance.

- Use demand forecasting to improve stock placement by region.

### Reduce Order Gaps & Reverse Logistics Issues
**Why:** Shipped orders exceed completed orders, indicating cancellations or returns.

**Actions:**

- Investigate reasons for cancellations (delivery delays, product mismatch, payment issues).

- Improve order confirmation workflows to reduce pending orders.

- Add a “reason for return” dashboard to identify recurring issues.

### Optimize Marketing Spend for Higher ROI
**Why:** Email and AdWords generate most revenue; organic traffic is weak.

**Actions:**

- Increase investment in Email automation and personalized campaigns.

- Optimize AdWords bidding for high‑value segments.

- Strengthen SEO content to reduce dependency on paid channels.

- Build a conversion‑funnel dashboard to identify drop‑off points.

### Improve Customer Experience Across Browsers
**Why:** Chrome dominates usage; Safari users may face friction.

**Actions:**

- Prioritize Chrome optimization for speed and mobile experience.

- Conduct cross‑browser testing to fix Safari and Firefox issues.

- Personalize landing pages based on browser behavior.

### Align Marketing & Operations for Better Inventory Planning
**Why:** Gender‑based traffic patterns and SKU movement are not fully aligned.

**Actions:**

- Use gender‑specific traffic data to guide inventory planning.

- Match high‑traffic segments with high‑velocity SKUs.

- Coordinate marketing campaigns with available stock to avoid stockouts.
  
By integrating insights from all three dashboards, the business now has a clear, actionable view of its performance across Sales, Operations, and Marketing.







     


