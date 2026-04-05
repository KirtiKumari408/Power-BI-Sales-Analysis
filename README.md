📊 Superstore Sales Analysis Dashboard | Power BI
📝 Project Overview
This project is a comprehensive two-page Power BI Dashboard designed to analyze the sales performance of a global retail superstore. The goal of this analysis is to identify key performance indicators (KPIs), regional sales trends, and product-level profitability.

🚀 Live Features:
Executive Overview: High-level metrics for Sales, Profit (Estimated), and Quantity.

Trend Analysis: Interactive Line Chart showing sales growth over a multi-year period.

Regional Insights: Comparative analysis of Sales across different geographical regions.

Deep-Dive Analytics: Scatter plots for Sales vs. Target and Donut charts for Category distribution.

Interactive Filtering: Dynamic Slicers for Date, Segment, Region, and Category.

🛠️ Tech Stack & Tools
Tool: Power BI Desktop

Language: DAX (Data Analysis Expressions) for custom measures.

Data Source: Superstore train.csv (Retail Dataset).

📈 Dashboard Insights
Page 1: Sales Performance Dashboard
Total Sales: $2.26M

Key Finding: Sales show a significant upward trajectory starting from 2017, peaking in late 2018.

Regional Leader: The West Region consistently outperforms other regions in total revenue.

Page 2: Analytical Deep-Dive
Segment Analysis: The "Consumer" segment is the largest driver of volume.

Product Performance: Top 5 products by sales were identified using the Top N filtering technique.

Category Distribution: Technology and Office Supplies represent the bulk of the store's revenue.


💡 Technical Implementation Details
Data Cleaning: Handled missing values and formatted "Ship Date" for time-series analysis.

Custom Measures: Used DAX to calculate Profit margins and Total Order counts where original columns were missing.

UI/UX Design: Implemented a Dark Mode theme with a high-contrast purple palette for better readability and professional aesthetics.

Filtering Logic: Established a synchronized slicing system so that Page 2 filters carry over contextually.

📂 How to use this Repo
Download the Dashboard.pbix file.

Open it in Power BI Desktop.

Ensure the train.csv data source is linked correctly to view live interactions.
