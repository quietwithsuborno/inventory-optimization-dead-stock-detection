## 🎯 Overview
This document presents the key business insights derived from the inventory optimization analyses conducted for RetailMart BD. Using inventory transactions, product performance, supplier data, and stock movement patterns, multiple analytical frameworks were applied to identify revenue drivers, inventory risks, replenishment opportunities, and operational inefficiencies.

The following sections summarize the major findings from each analysis and explain their significance from a business perspective.

---

## 📦 ABC Analysis

### 🔍 Key Findings

- Revenue is highly concentrated among a small group of products. Only **15 Category A products** account for approximately **69% of total revenue**, indicating that a limited number of SKUs drive the majority of business value.

- **Fresh Soybean Oil 2L** emerged as the highest revenue-generating product, contributing nearly **7.8% of total revenue** on its own. This highlights its importance in maintaining overall sales performance.

- Category B products represent the second tier of revenue contributors. While individually less impactful than Category A products, they collectively provide a meaningful share of total revenue and should be monitored to sustain business growth.

- Category C contains **11 products** with relatively low revenue contribution. However, a closer review revealed that not all Category C products are underperforming inventory. Several belong to active categories such as **Healthcare, Home Care, Food & Beverage, and Personal Care**, suggesting that low revenue alone does not indicate low demand.

### 💡 Business Implications

- Category A products should receive the highest priority for inventory planning, replenishment, and stock availability, as stock-outs in these items could significantly impact revenue.

- Category B products require balanced inventory management and periodic performance reviews to identify future growth opportunities.

- Category C products should be evaluated more carefully before making inventory decisions, as some may still be regularly purchased despite their lower revenue contribution.

### ⚠️ Limitation of ABC Analysis

ABC Analysis focuses exclusively on **revenue contribution** and does not consider **purchase frequency, demand consistency, or demand variability**.

As a result, products with similar revenue contributions can exhibit very different inventory behaviors:

- Some products may generate low revenue but sell consistently throughout the year.
- Others may generate low revenue because they experience very little customer demand.

ABC Analysis alone cannot distinguish between these scenarios.

### ➡️ Why We Proceeded to XYZ Analysis

To gain a more complete understanding of inventory performance, the next step was to perform **XYZ Analysis**, which evaluates demand patterns and sales variability.

By combining ABC and XYZ classifications, it becomes possible to distinguish between:

- **Low-revenue but stable-demand products**
- **Low-revenue and genuinely slow-moving products**

This provides a stronger foundation for inventory optimization, stock planning, and product-level decision-making than ABC Analysis alone.

---

## 📦 XYZ Analysis Findings

### 🔍 Key Findings

The XYZ Analysis classified 35 products based on demand variability and forecastability.

| Category | Product Count |
|-----------|-----------:|
| X (Stable Demand) | 16 |
| Y (Moderately Variable Demand) | 14 |
| Z (Highly Variable Demand) | 5 |

A strong positive signal is that **30 out of 35 products (86%) fall into the X or Y categories**, indicating that most products have predictable demand patterns and can be forecasted with reasonable confidence.

Products in the **X category** demonstrated stable demand throughout the 24-month period, making them easier to forecast and manage from an inventory perspective.

### ⚠️ Z Category Insight

The most important finding came from the **Z category**, which contains:

- Premium Candle Set
- Ceramic Mug Set
- Aromatherapy Diffuser
- Herbal Bath Salts
- Imported Olive Oil

Each of these products recorded **17 zero-sale months out of 24 months** and showed extremely high demand variability (CV > 160%).

This confirms that these products are not only low-revenue items but also exhibit highly intermittent demand patterns.

### 💡 Business Implications

An important insight from this analysis is:

> **Low Revenue ≠ Unstable Demand**

Products such as Antacid Tablets, Harpic, Vim, Savlon, and Sensodyne appeared in the **C category of the ABC Analysis** but were classified as **X category in the XYZ Analysis**, indicating low revenue contribution but stable demand.

In contrast, the five Z-category products showed both:

- 📉 Low revenue contribution
- 📦 Highly unpredictable demand

This makes them strong candidates for slow-moving inventory review and stock optimization initiatives.

### 🎯 Why This Analysis Matters

While **ABC Analysis** identifies products that drive revenue, **XYZ Analysis** measures demand predictability.

Together, they provide a more complete inventory management view by distinguishing between products that are merely low-revenue and those that are genuinely slow-moving or difficult to forecast. 🚀

## Limitations of XYZ Analysis

While XYZ Analysis effectively measures demand variability, it does not consider revenue contribution.

For example, two products may both belong to Category X, but one may generate significantly higher revenue than the other.

Therefore, XYZ Analysis should not be used in isolation for inventory decisions. It becomes significantly more valuable when combined with ABC Analysis to evaluate both revenue importance and demand predictability simultaneously.

---

## 🔗 ABC-XYZ Matrix Analysis Findings

### 🔍 Key Findings

The ABC-XYZ Matrix combined revenue contribution (ABC) and demand predictability (XYZ) to create a more actionable inventory segmentation model.

| Segment | Product Count | Revenue |
|----------|-----------:|-----------:|
| AX | 7 | 9.48M |
| AY | 8 | 8.93M |
| BX | 5 | 2.81M |
| BY | 4 | 2.52M |
| CX | 4 | 1.85M |
| CY | 2 | 0.85M |
| CZ | 5 | 0.23M |

A notable observation is that **all A-category products fall into either AX or AY segments**, meaning the company's highest revenue-generating products have either stable or moderately variable demand. No products were classified as AZ, indicating that none of the major revenue drivers suffer from highly unpredictable demand.

### 📈 Revenue Drivers

The **AX and AY segments together generated more than 18 million revenue**, accounting for the majority of total business revenue.

- 🟢 **AX Products** represent high-revenue products with stable demand, making them the most valuable and easiest products to forecast and manage.
- 🟡 **AY Products** also generate significant revenue but exhibit moderate demand variability, requiring closer forecasting and inventory monitoring.

These segments contain the products that deserve the highest inventory planning priority.

### 💡 Important Business Insight

One of the most valuable findings is the presence of **CX products**.

Products such as Antacid Tablets, Harpic, Vim, and Savlon were classified as:

- 📉 Low Revenue Contribution (C)
- 📦 Stable Demand (X)

This demonstrates an important inventory management principle:

> **Low Revenue ≠ Poor Product Performance**

Although these products contribute less revenue, they maintain consistent demand and therefore continue to play an operational role in the business.

### ⚠️ Slow-Moving Inventory Candidates

The **CZ segment** contains:

- Premium Candle Set
- Ceramic Mug Set
- Aromatherapy Diffuser
- Herbal Bath Salts
- Imported Olive Oil

These products contribute only **0.23M revenue** and exhibit extremely high demand variability (Average CV = 166%).

This confirms that they are not only low-revenue products but also highly intermittent-demand items, making them the strongest candidates for slow-moving inventory review and stock optimization initiatives.

### 🎯 Why This Analysis Matters

ABC Analysis identifies revenue importance, while XYZ Analysis measures demand predictability. By combining both perspectives, the ABC-XYZ Matrix enables more informed inventory decisions and helps distinguish between:

- 💰 High-value products that require tight inventory control
- 📦 Stable products that can be forecasted confidently
- ⚠️ Slow-moving products that may require special inventory strategies

The analysis ultimately provides a complete inventory prioritization framework by evaluating both business value and demand behavior simultaneously. 🚀

### ⚠️ Limitation of ABC-XYZ Matrix Analysis

While the ABC-XYZ Matrix provides valuable insights into revenue contribution and demand predictability, it does not consider how long inventory has remained in stock.

For example, a product may belong to the CZ segment due to low revenue and highly variable demand, but the analysis alone cannot determine whether the inventory has been sitting in the warehouse for 30 days or 300 days.

Therefore, ABC-XYZ Matrix should not be used as the final inventory assessment tool. To identify aging inventory, slow-moving stock, and potential dead-stock risks, a Stock Aging Analysis is required.

This leads to the next stage of the analysis, where inventory is evaluated based on how long products remain unsold in storage.


---

## 📦 Stock Aging Analysis Findings

### 🔍 Key Findings

The Stock Aging Analysis evaluated inventory health across all product-warehouse combinations by measuring the number of days since the last sale and the amount of capital currently tied up in stock.

| Aging Bucket | Product-Warehouse Count | Total Units | Tied-Up Capital |
|-------------|-----------------------:|------------:|----------------:|
| Active | 84 | 103,409 | 5.48M |
| Slow Moving | 6 | 9,190 | 0.53M |
| Dead Stock | 15 | 212 | 0.08M |

The results indicate that the overall inventory position is healthy, with the majority of stock actively moving across warehouses.

### ✅ Active Inventory Dominates the Business

A total of **84 out of 105 product-warehouse combinations** were classified as Active.

These products account for approximately **5.48 million of tied-up capital**, representing the overwhelming majority of inventory investment.

This suggests that most inventory is being replenished and sold regularly, reducing the risk of excess stock accumulation and improving working capital utilization.

### 💰 Slow-Moving Inventory Has Higher Financial Impact Than Dead Stock

Although only 6 product-warehouse combinations were classified as Slow Moving, they account for approximately **0.53 million of tied-up capital**.

This is significantly higher than the capital locked in Dead Stock.

This finding suggests that management attention should not focus solely on dead stock. Slow-moving inventory may represent a larger financial burden due to its higher inventory value.

### ⚠️ Dead Stock Exists but Financial Risk Remains Low

The analysis identified **15 dead-stock combinations**, but the total capital tied up in these items is only **0.08 million**.

This indicates that while dead stock exists within the network, its current financial impact is relatively limited.

As a result, dead stock does not appear to be a major working capital concern at this stage.

### 🏭 Importance of Warehouse-Level Analysis

This analysis was performed at the product-warehouse level rather than at the product level.

This approach enables the business to identify inventory ageing issues within specific warehouse locations, making inventory optimization efforts more targeted and actionable.

### 🎯 Why This Analysis Matters

While ABC Analysis identifies revenue importance and XYZ Analysis measures demand predictability, Stock Aging Analysis introduces the time dimension by revealing how long inventory has remained unsold.

Together, these analyses provide a more complete inventory management framework by helping the business understand:

- 💰 Which products generate the most value
- 📈 Which products have predictable demand
- 📦 Which inventory is actively moving
- ⚠️ Which inventory may require corrective action

### 🔄 Limitation & Next Step

Stock Aging Analysis identifies how long inventory has remained unsold, but it does not explain whether current stock levels are appropriate relative to expected demand.

For example, an item may be classified as Active while still carrying excess inventory, or it may have low stock despite strong sales activity.

To evaluate inventory sufficiency and replenishment effectiveness, the next stage of analysis should focus on stock coverage, inventory turnover, or inventory optimization metrics.

This will help determine not only how old inventory is, but also whether current inventory levels are aligned with business demand.

---

