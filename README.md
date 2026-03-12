# Amazon Sales Global Performance Dashboard
A sophisticated Power BI project focused on global e-commerce analytics. This dashboard provides a high-level executive summary of revenue, profitability, and customer satisfaction metrics across multiple international regions.

# Project Overview

The goal of this dashboard is to provide the "Amazon" management team with a 360-degree view of operational health. It tracks how different payment methods, discount strategies, and product categories contribute to the overall $8.11M Total Revenue

# Key Technical Features

 Dynamic Data Cleaning: Implemented a custom transformation to handle messy "Rating" decimals, grouping them into clean Integer Bins (1-5) for clear donut chart visualization.
Multi-Dimensional Filtering: Integrated cross-filtering by Year (2022-2023), Month, and Global Region (Asia, Europe, Middle East, North America).

Payment Gateway Analysis: A specialized donut chart visualizing the distribution of payment methods (Wallet, UPI, Debit, etc.), showing an almost even split in transaction volume.

Profitability Correlation: A custom line visual showing the inverse relationship between Discount Percentage and Total Profit, helping identify the "Sweet Spot" for promotions.

# Tech Stack

Power BI Desktop: Report authoring and UI/UX design.

DAX (Data Analysis Expressions): Used for calculating Profit Margin (0.05) and custom rating groups.

Theme: Custom Dark Mode with an "Amazon Orange" accent palette for a branded, professional feel.
