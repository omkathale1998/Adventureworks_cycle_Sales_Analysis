# Adventureworks_cycle_Sales_Analysis

<img src="https://github.com/Sayali821/Adventure_Works/blob/000f9a695f4980fb4fb4e07dbd95a7bf2f0a3f72/AW__Banner.jpg" width="1000"/>

---
## 📌 Overview

The *Adventure Works Sales Dashboard* is designed to provide strategic insights into the performance of a fictional bicycle company over three years (2020–2022). It merges data from various sources to provide a comprehensive view of customer behavior, product performance, geographic distribution, and sales trends. The report enables data-driven decision-making through dynamic visualizations, KPIs, and trend analysis.

---

## 💡 Tools & Skills Demonstrated

- Power BI Data Modeling
- Data Cleaning and Relationships
- DAX Measures and Time Intelligence
- Dashboard Design and Theming
- Business KPIs and Storytelling

---

## 🧹 Data Cleaning & Modeling

### 🗓️ Calendar Table
Created a custom calendar table to support time intelligence features with:
- Month Name
- Day Name
- Quarter
- Start of Quarter
- Start of Month
- Start of Week

### 👥 Customer Lookup Table
Added the following enriched columns:
- Full Name (First + Last)
- Is_Parent (Flag for customers with children)
- Age Group
- Income Level: categorized as:
  - Lower Middle Class  
  - Middle Class  
  - Upper Middle Class

### 🚴 Product Lookup Table
- Added Gender Type to define if the product is for Men, Women, or Unisex.

### 🧾 Sales Final Table
Merged yearly sales data (2020, 2021, 2022) into one unified *Sales Final Table* for consolidated analysis.

### 📐 Measures Table
Created a centralized *Measure Table* with the following DAX measures:

- Total_Revenue
- Total_Cost
- Total_Orders
- Total_Quantity_Sold
- Total_Returned_Quantity
- Profit_Margin
- Profit_Margin_%
- Return_Rate_%

---


## 🚀 Key Features

- 📦 *Unified Sales Data*: Combined data from three years (2020–2022) into a single, clean dataset.
- 📊 *Interactive Dashboard*: Dynamic slicers, filters, and visualizations for exploring trends by product, region, and category.
- 🧠 *Smart Measures*: Custom DAX calculations for profit margin, return rate, total cost, quantity, and revenue.
- 🌍 *Geographical Insights*: Country- and continent-level breakdown of orders and revenue.
- 📆 *Time Intelligence*: Custom calendar table enables monthly, quarterly, and yearly trend analysis.
- 👥 *Customer Segmentation*: Demographic attributes such as income level, age group, and parental status used for enhanced analysis.
- 🧺 *Product Category Analysis*: Insights by Bikes, Accessories, and Clothing — including return behaviors and order patterns.
- 🎨 *Consistent Branding*: Custom color palette and branded visuals using Adventure Works' logo and theme.

---

## 📊 Dashboard

<img src="https://github.com/omkathale1998/Adventureworks_cycle_Sales_Analysis/blob/main/Dashborad.png" width="1000"/>

## ✨ Highlights

- 💰 *Total Revenue:* $24.91M
- 📦 *Total Orders:* 25K
- 💹 *Profit Margin:* $10.46M
- 🔁 *Return Rate:* 2.17%
- 🌍 *Top Region:* Europe
- 🚲 *Top Product:* Mountain-200 Black, 46

---


## 📚 Data Story

Adventure Works is a growing bicycle company that sells bikes, accessories, and clothing across different regions — Europe, North America, and the Pacific. To assess performance, the company collected sales data across three years. After consolidating the data and enriching it with demographic and product-level attributes, this report was created to understand:

- Where sales are growing
- Which products perform best
- Who the customers are
- How returns and margins impact profitability

This story unfolds through interactive dashboards that guide stakeholders from general performance KPIs to detailed country-level insights and product trends.

---

## 🔍 Top Insights

1. *Product Performance*
   - Mountain-200 series dominates revenue and orders across all regions.
   - Higher-margin products generally show *lower return rates*, especially in Europe.

2. *Regional Insights*
   - Europe shows strong sales and lower returns compared to other regions.
   - North America had a high quantity of sales in the Road-250 line but with slightly higher return rates.

3. *Category Breakdown*
   - *Accessories* accounted for the highest number of total orders.
   - Clothing, while smallest in volume, needs closer attention due to a *4.4% return rate*.

4. *Customer Analysis*
   - Segmenting customers by *Income Level* and *Age Group* enables targeted marketing opportunities.
   - Majority of high-revenue customers belong to the *Middle Class* and *Upper Middle Class* segments.

5. *Time Trends*
   - Seasonal spikes in orders and revenue observed around *early and late quarters*, indicating possible promotion periods.

---

## ✅ Recommendations

- 🏷️ *Double down on Europe*: Continue investing in marketing and distribution in Europe due to its superior revenue performance.
- 🚴‍♀️ *Expand Mountain Bike product line*: Introduce new models/variations in the Mountain-200 series.
- 👕 *Reduce Clothing return rate*: Re-evaluate sizing or product quality and optimize return policies.
- 🎯 *Target Middle and Upper Middle Class customers*: Based on consistent high-spending behavior.
- 📅 *Leverage Q1 & Q4 seasonality*: Launch promotional campaigns to maximize seasonal demand.


## 📌 Conclusion

This Power BI project effectively demonstrates how raw sales data can be transformed into meaningful business intelligence. By merging, cleaning, and modeling the data across multiple years, the dashboard offers:

- A full view of business health through KPIs
- Regional and product-wise performance comparisons
- Actionable insights based on customer behavior and sales trends

The report equips decision-makers with the information needed to optimize product lines, reduce returns, target profitable customer segments, and plan region-wise growth strategies. This project reflects strong capabilities in *data analysis, storytelling, and visualization using Power BI.*

---
