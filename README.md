# E-Commerce Sales Performance Dashboard

An end-to-end data analytics project covering data cleaning, exploratory analysis, and Power BI visualization on an E-Commerce sales dataset.

## 📌 Project Overview
This project analyses E-Commerce business performance data, progressing from raw data cleaning to a fully interactive Power BI dashboard. The project covers the complete data analytics workflow—cleaning, exploration, and storytelling through visualization.

## Key Metrics Uncovered:

| Metric | Value |
| --- | --- |
| **Total Revenue** | $10.67M |
| **Total Profit** | $1.84M |
| **Total Quantity** | 17K |
| **Profit Margin %** | 17.29% |
| **Total Order** | 3500 |

## 🛠️ Tools & Technologies

| Tool | Purpose |
| --- | --- |
| **Power BI** | Data Cleaning, EDA & Basic Statistics |
| **Power BI** | Data Visualization & Dashboard |

## 🧹 Data Cleaning & Preparation (Excel)
**Objective:** Prepare the raw `ecommerce_sales_data (1).csv` dataset for analysis by resolving data quality issues.

**Tasks Performed:**
* **Data Type Clarification:** Ensured all numerical and date fields were set to their correct data types to facilitate accurate calculations.
* **Precision Formatting:** Formatted all decimal values (specifically Profit) to two decimal places for professional reporting.
* **Missing Value Audit:** I checked for missing values in the dataset and confirmed that there weren't any missing values.
* **Feature Engineering:** Created dedicated "Month" and "Year" columns by extracting them from the existing "Order Date" column. This was essential for temporal analysis within the dashboard.
* **Data Preservation:** Ensured all original "Order Date" and "Year" columns remained unmodified to maintain the integrity of the time-series data.

## 📊 DAX Measures
To calculate the KPIs displayed on the dashboard, the following DAX measures were utilized:

* **Total Revenue:** SUM('ecommerce_sales_data (1)'[Sales])
* **Total Profit:** SUM('ecommerce_sales_data (1)'[Profit])
* **Total Quantity:** SUM('ecommerce_sales_data (1)'[Quantity])
* **Total Order:** COUNT('ecommerce_sales_data (1)'[Order Date])
* **Profit Margin %:** DIVIDE([Total Profit], [Total Revenue])

## 📈 Dashboard Insights
The dashboard, as seen in the file uploaded, provides a comprehensive view of business performance using a professional green/black color theme.

* **Sales Distribution:** Visualizes performance across different products to identify top contributors.
* **Revenue Contribution:** A donut chart showcasing the revenue share by product category.
* **Quarterly Trends:** Tracks profit trends across different quarters to ensure consistent profitability.
* **Regional Performance:** Highlights sales achievements across different geographical regions.

---
*This project was completed by **U.S. OKOLI** as part week 1 Syntecxhub data analytics internship.*
