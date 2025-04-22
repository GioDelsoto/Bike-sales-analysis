# 🚴‍♂️ Exploratory Data Analysis: Bike Sales in Europe

This project is an exploratory analysis of **bike sales data across Europe**. The main goal is to uncover **trends and patterns related to customer demographics, product categories, geographic regions**, and key sales metrics such as **revenue, profit, and quantity sold**.

The dataset used in this analysis was obtained from [Kaggle](https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe/data) and contains detailed transaction-level information about **bike-related products**, **customer profiles**, and **sales performance**.

## This analysis was developed as part of a data science portfolio to demonstrate skills in data wrangling, visualization, and insight generation using Python and Jupyter Notebook.

## Folders

- `data/`: Contains the original dataset.
- `notebook/`: Contains the exploratory analysis in a Jupyter notebook.

---

## 📊 Visual Highlights

### Customer Demographics

![Age Distribution](../notebook/age_group.png)

### Sales and Order Trends Over Time

![Order Quantity](../notebook/orders_quantity.png)
![Sales Over Years](../notebook/sales_over_year.png)

### Profit Distribution by Product Categories

![Profit Sunburst](../notebook/sunburst_profit.png)

### Top Products by Performance

**Top 10 Products by Quantity Sold**
![Top 10 Quantity](../notebook/top10_quantity.png)

**Top 10 Products by Profit**
![Top 10 Profit](../notebook/top10_profit.png)

---

## Highlights & Insights

- **Seasonality detected:** There appears to be a recurring sales pattern every 2 years.
- **July shows the lowest average sales**, while December sees the highest. A general upward trend is visible throughout the year — except in July.
- **2014 and 2016 show similar behavior** and have missing data for the second half of the year. Worth investigating the cause.
- **2013 and 2015 started slow and picked up later** in the year. 2014 and 2016 seem to follow the same trend with slight variations.
- Despite fewer orders, **profits increased**, suggesting a shift towards higher-priced products.
- **Adults aged 25–64 dominate sales** in both order count and revenue. Young and senior audiences are underrepresented — potential growth markets.
- **The US maintained order volume while increasing profits per sale**, suggesting successful high-margin strategies.
- **Australia’s sales dropped in 2014 and 2016**. Further analysis is needed to understand this decline.
- **Accessories outsell other categories in volume** (4x more than clothing, 30x more than bikes), but bikes generate **over twice the profit** of accessories and **7x the profit of clothing**.
- **Profit margins increased from 32% to 39% starting in 2013**.
- **Top revenue-contributing products had mid-range margins (35–40%)** but higher price tags.
- **Bikes show a consistent growth trend**, unlike other subcategories that remained stable.

---

## Suggested Actions

- Offer **early-year discounts** to boost sales in low-performing months like July.
- Create **kits that bundle high-volume, low-profit items (e.g., tires, bottles)** with high-margin accessories (e.g., helmets, socks).
- Launch **targeted campaigns for younger and older customers** to expand market reach.
- **Replicate U.S. strategies** in other regions to improve profitability per sale.
- Investigate **data gaps in 2014 and 2016** to ensure data completeness and consistency.
- Explore **why Australia underperformed** in specific years and address possible operational or market issues.
- Promote **high-revenue items with average margins** alongside cheaper, lower-margin items to optimize overall margins.
- Use the **growth trend of bicycles** to upsell related accessories and services.
