# Retail-Store-Sales-Performance-Dashboard
Sales dashboard providing analysis of sales performance across 10 retail stores, tracking key metrics like Total Sales, average daily sales, and the impact of promotions and holidays over a two-year period (2022-2023).

## 1. Overview and Purpose

This dashboard provides a comprehensive view of sales performance across **10 retail stores** over a two-year period (2022-2023). It is designed to help management and store operations teams:

* Track key performance indicators (**KPIs**) at an aggregate level using local currency (₹).

* Analyze the impact of **promotions and holidays** on sales revenue.

* Identify **top and bottom-performing stores** and periods.

* Inform strategic decisions regarding resource allocation, promotional planning, and inventory management.

## 2. Key Performance Indicators (KPIs)

The following metrics summarize the sales performance across the 10 stores (all figures in Indian Rupees - ₹):

* **Total Sales:** ₹1,667,572.37

* **Average Daily Sales:** ₹228.43

* **Maximum Daily Sales:** ₹340.73

* **Minimum Daily Sales:** ₹160.71

* **Store with Maximum Sales:** Store 9

* **Number of Promotional Days:** 1,476

* **Sales During Promotions:** ₹371,912.47

* **Number of Holidays:** 760

* **Sales on Holidays:** ₹200,274.07

* **Sales on Weekends:** ₹0 (This metric requires investigation as it suggests weekend data may be missing or unrecorded.)

## 3. Data Dictionary

The analysis is built upon the following key columns in the `store_sales.csv` dataset:

| Column Name | Description |
| :--- | :--- |
| **date** | The specific date of the sales record. |
| **store** | Unique identifier for each of the 10 stores. |
| **sales** | The total sales amount for the store on that date (in ₹). |
| **Promo yes/no** | Status if a promotion was active (`Promotion` or `NO Promotion`). |
| **promo** | Binary flag for promotion (1 = Yes, 0 = No). |
| **Holiday yes/no** | Status if the day was a holiday (`Holiday` or `NO Holiday`). |
| **holiday** | Binary flag for holiday (1 = Yes, 0 = No). |
| **day of week** | The specific day of the week (e.g., Monday, Sunday). |
| **month** | The month of the year. |
| **promo/holiday** | Categorized grouping for analysis (e.g., `Active Promotion`, `Holiday Sales Only`). |

## 4. Key Findings & Strategic Recommendations

Based on the dashboard's underlying data, the following strategic areas are recommended for focus:

### A. Focus on Store Performance and Replication

**Finding:** **Store 9** is the top-performing store, significantly influencing the ₹1.67 Million Total Sales.

**Recommendation:**

* **Best Practice Replication:** Conduct an in-depth operational and marketing review of **Store 9**. Document its successful strategies (e.g., visual merchandising, customer service, inventory mix) and create a standardized playbook for implementation across the lower-performing stores.

* **Targeted Support:** Develop a performance improvement plan for the bottom-performing stores, focusing resources on addressing localized issues (e.g., visibility, local competition, staffing).

### B. Optimize Promotional Strategy for ROI

**Finding:** Promotional days are frequent (1,476 days) and contribute significantly (₹371,912) but the true sales *lift* needs confirmation.

**Recommendation:**

* **Quantify Promotional Lift:** Compare the **Average Daily Sales on a Promotional Day** (₹371,912.47 / 1,476 days) against the **Average Daily Sales on a Regular Day** (Non-Promo/Non-Holiday). This comparison will quantify the ROI of promotions and identify which ones should be scaled back or eliminated.

* **Day-of-Week Focus:** Analyze sales lift by day-of-week during promotions. Reallocate promotional budgets to days that show the highest incremental sales increase to maximize efficiency.

### C. Maximize Holiday Opportunity

**Finding:** Holidays are important revenue drivers, contributing ₹200,274.07 in sales.

**Recommendation:**

* **Forecast Accuracy:** Use the detailed holiday sales data to refine seasonal inventory and staffing forecasts, particularly in the months that traditionally show the highest sales volumes. This prevents costly stockouts or markdowns.

* **Sustaining Momentum:** Analyze sales data for the 3 days *following* major holidays. If sales drop sharply, plan a smaller, targeted "post-holiday clearance" or "early access" promotion to stabilize revenue and manage inventory flow.
