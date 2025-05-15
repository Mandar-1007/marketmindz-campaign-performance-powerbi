# MarketMindz – Marketing Campaign and Consumer Behavior Dashboard

This project presents an interactive Power BI dashboard developed to analyze customer behavior and marketing campaign effectiveness for a fictional retail brand. The dashboard enables users to explore customer demographics, purchase patterns, and campaign response behavior across multiple dimensions.

---

## Tools Used
- Microsoft Power BI Desktop
- Power Query Editor
- Microsoft Excel (CSV format)

---

## Dashboard Visuals & Business Insights

### 1. Campaign Performance Overview
📊 **Visuals**: Column charts, bar charts, clustered comparisons  
📌 **Insights**:
- Displays acceptance trends across six marketing campaigns
- Highlights product performance by sales contribution
- Compares platform preferences (Store, Web, Catalog, Deal) per campaign

**Business Question Answered**:
> Which campaigns generated the most engagement and revenue?

---

### 2. Buyer Composition Analysis
📊 **Visuals**: Donut charts, bar graphs, segmented visuals  
📌 **Insights**:
- Segments customers by age group, marital status, education, and income
- Tracks purchasing habits by demographic group
- Highlights how age and household structure influence buying behavior

**Business Question Answered**:
> Which types of customers respond more positively to marketing and what products do they prefer?

---

### 3. Purchase Drivers (Key Influencer Visual)
📊 **Visuals**: AI-powered Key Influencers chart  
📌 **Insights**:
- Identifies key factors influencing campaign acceptance and higher spending
- Highlights the role of income, household size, and platform use

**Business Question Answered**:
> What factors most strongly influence whether a customer accepts a campaign or contributes high revenue?

---

## 🖼️ Dashboard Previews

### 1. Campaign Performance Dashboard

![Campaign performance](https://github.com/user-attachments/assets/e3146c18-e98f-4d8f-b969-151861dde1e9)


### 2. Buyer Composition Dashboard

![Buyer Composition](https://github.com/user-attachments/assets/4a81cdf4-8437-41db-b065-03b5622a6896)


### 3. Purchase Drivers (Key Influencer)

![Purchase Drivers](https://github.com/user-attachments/assets/77ae75e6-1f15-4289-a4cc-6a756282380d)


---

## 🔍 Key Business Insights

- **Campaign 6** had the highest customer acceptance, showing strong engagement toward recent marketing efforts.
- **Campaign 5**, although less accepted, generated the highest total revenue — indicating higher spend per customer.
- **Wine** emerged as the most purchased and highest-earning product, particularly among older customer segments.
- **Store** platform dominated all others, accounting for over 13,000 purchases across all campaigns.
- Customers with **higher income**, **no kids/teens at home**, and **fewer web visits per month** showed greater likelihood of campaign acceptance and higher sales contribution.

---

## Summary KPIs
The report includes dynamic tiles that summarize key metrics such as:
- Total Campaign Acceptance Count
- Average Income of Campaign Responders
- Most Frequently Used Purchase Platform

These help decision-makers instantly spot key trends in customer engagement and campaign reach.

---

## Data Model
The dataset includes 2,240 customers with the following fields:
- **Demographics**: Year of birth, marital status, education, income
- **Household Info**: Number of kids and teens at home
- **Behavioral Metrics**: Recency, number of deals used, platform activity
- **Product Purchases**: Spending on wine, meat, fruits, etc.
- **Campaign Responses**: Binary flags for Campaigns 1–5 and a final “Response” field for Campaign 6

A star schema was created using related dimension tables for products, campaigns, platforms, and image URLs.

---

## Interactive Features
- **Slicers** to filter by age group, platform, and campaign
- **Interactive tooltips** for precise insights
- **Key Influencers AI Visual** for automated insights into driving factors

---

## Why This Matters
The dashboard answers key business questions such as:
- Which products are preferred by which age groups?
- What customer profiles are more likely to accept marketing campaigns?
- Which platform performs best for different campaigns?

Together, these insights enable marketing teams to:
- Tailor campaign strategies
- Segment audiences more effectively
- Increase ROI through data-driven targeting

---

## Conclusion
This Power BI dashboard provides a powerful visual framework for understanding marketing performance, customer segmentation, and purchasing behavior. Built without DAX, it focuses on strong data modeling and Power Query transformations to tell a complete customer engagement story. Ideal for showcasing analytical thinking, dashboard design, and business storytelling in a marketing context.
