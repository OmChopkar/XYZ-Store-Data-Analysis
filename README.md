# XYZ Store - Annual Sales Data Analysis

## 📌 Project Overview
This project explores the annual sales data for XYZ Store to uncover trends in customer behavior, channel performance, and regional sales distribution. The objective was to take raw e-commerce data, clean it, and build an interactive dashboard to provide actionable business insights. 

## 🛠️ Tools & Technologies
*   **Microsoft Excel:** Data Cleaning, Feature Engineering, Pivot Tables, and Interactive Dashboarding.

## 🧹 Data Preprocessing
The raw dataset (`Raw - Original_XYZ_StoreDataAnalysis.xlsx`) contained inconsistencies. The following data wrangling steps were performed to create the analysis-ready dataset (`Cleaned - Original_XYZ_StoreDataAnalysis.xlsx`):
*   **Data Type Standardization:** Corrected string/numeric inconsistencies in the `Qty` column.
*   **Feature Engineering:** Extracted `Month` from the continuous `Date` column; grouped continuous `Age` data into a categorical `Age Group` tier.
*   **Data Cleaning:** Expanded 'W' and 'M' in the Gender column to 'Women' and 'Men'. 
*   **Geographic Standardization:** Standardized casing in the `ship-state` column.
*   **Dimensionality Reduction:** Dropped zero-variance columns (`currency`, `ship-country`) and redundant index columns.

## 📊 Dashboard & Visualizations
An interactive dashboard was built using Excel Pivot Charts, controlled by a left-aligned navigation panel with slicers for **Month, Channel, Gender, and Status**. 
    
*(Insert Dashboard Screenshot Here: `<img width="1280" height="835" alt="XYZSalesDashboard" src="https://github.com/user-attachments/assets/fed2e3b8-50c5-4cee-8d39-0a30d2466e97" />
![Dashboard](name-of-your-screenshot-file.png)`)*

## 🎯 Business Questions Answered (Project Targets)
**1. Compare the sales and orders using a single chart:** 
Sales revenue directly correlates with order volume throughout the year, with peaks and valleys perfectly mirroring each other.

**2. Which month shows the highest sales and orders?** 
**March** is the peak performing month, generating **1,928,066** in sales from **2,819** orders.

**3. Who purchased more - men or women in 2025?** 
**Women** purchased significantly more, accounting for **21,553** orders compared to men's **9,494**.

**4. What are different order statuses in 2025?** 
The vast majority of orders were successful: Delivered (28,641), Returned (1,045), Cancelled (844), and Refunded (517).

**5. List top 5 states contributing to the sales?** 
The highest revenue-generating regions are **Maharashtra**, **Karnataka**, **Uttar Pradesh**, **Tamil Nadu**, and **Telangana**.

**6. Relation between Age and Gender based on number of orders:** 
**Adult Women** are the most dominant consumer group.

**7. Which channel is contributing to maximum sales?** 
**Amazon** is the top-performing channel, contributing **7,519,933** in total sales revenue.

**8. Which is the highest selling category?** 
The **Set** category is the highest seller, followed closely by the Kurta category.
