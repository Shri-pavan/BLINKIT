# Blinkit Grocery Sales Analysis in Excel

## 🚀 Project Overview

This project presents a comprehensive analysis of sales data from the grocery delivery service, Blinkit, conducted entirely within Microsoft Excel. The core objective is to leverage Excel's powerful features to clean the data, perform in-depth analysis, and build a fully interactive dashboard to visualize key business insights as laid out in the project's design plan.

The repository contains the master Excel file which includes the raw data, data cleaning steps (using Power Query), a dynamic data model, and a multi-sheet dashboard.

## 📊 Excel Dashboard & Analysis

The entire analysis is self-contained within the Excel workbook. The interactive dashboard was built using PivotTables, Slicers, and Charts to address the key questions from the design document.

* **KPIs:** Key metrics including Total Sales, Average Rating, and Total Items Sold.
* **Interactive Slicers:** Dynamic filters for Date, Outlet Location Tier, Item Type, and more.
* **Charts & Visuals:**
    * A line chart showing **Sales Trends Over Time**.
    * A bar chart visualizing **Sales by Product Category**.
    * Breakdowns of sales by **Outlet Size**, **Location**, and **Type**.
    * Analysis of sales by **Item Fat Content**.

## 🛠️ Tools & Technologies

* **Primary Tool:** Microsoft Excel
* **Key Features Used:**
    * **Power Query:** For data cleaning, transformation, and handling missing values.
    * **PivotTables & PivotCharts:** For data aggregation and dynamic analysis.
    * **Slicers & Timelines:** For creating an interactive user experience.
    * **Excel Formulas:** For creating calculated fields and custom metrics.

## ⚙️ How to Use

1.  **Open the Excel File:**
    * Navigate to the project directory.
    * Open the `.xlsx` file in Microsoft Excel (version 2016 or newer is recommended for full functionality).
2.  **Interact with the Dashboard:**
    * Navigate to the "Dashboard" worksheet.
    * Use the slicers to filter the data and watch the charts update in real-time.

## 📈 Key Insights from the Analysis

* **Top Categories:** The analysis confirms that "Snacks & Munchies" and "Fruits and Vegetables" are the highest revenue-generating categories.
* **Location Impact:** Tier 3 city outlets contribute the most to total sales, indicating a strong market presence in those areas.
* **Data Quality:** A key challenge in the dataset was the ~17% missing `Item Weight` values, which were addressed using Power Query before analysis.
