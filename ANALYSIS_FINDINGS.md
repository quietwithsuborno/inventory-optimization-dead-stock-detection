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
