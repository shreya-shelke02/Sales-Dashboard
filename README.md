🛒 Madhav Ecommerce Sales Dashboard

An interactive Power BI dashboard analyzing sales, profit, and quantity performance for Madhav Ecommerce — built to help business stakeholders track revenue trends, top customers, category performance, and payment behavior at a glance.

<img width="1009" height="573" alt="image" src="https://github.com/user-attachments/assets/02bc00db-d096-4f2f-9d6a-d8b845a0e6ba" />


-------------------------------------------------------------------

📌 Project Overview

This project turns raw ecommerce transaction data into a single-page, interactive Power BI dashboard. It gives a real-time view of sales performance across states, categories, customers, and payment modes, with quarter-wise filtering for time-based analysis.

-------------------------------------------------------------------

🎯 Business Problem

Ecommerce businesses generate large volumes of order-level data (amount, quantity, profit, customer, category, payment mode) that's hard to interpret in raw form. This dashboard consolidates that data into a clear, filterable view so stakeholders can quickly answer:

- What are total sales, quantity, profit, and average order value (AOV)?
- Which states generate the highest revenue?
- Which payment modes are most preferred by customers?
- Which months are driving the most profit?
- Who are the top customers by revenue?
- Which product categories and sub-categories perform best?

-------------------------------------------------------------------

📊 Dashboard Preview

<img width="1009" height="573" alt="image" src="https://github.com/user-attachments/assets/ac3c5ec9-88ba-4606-ba29-b21c68903f3b" />


KPI Cards
- **Sum of Amount:** 161K
- **Sum of Quantity:** 2K
- **Sum of Profit:** 26K
- **Sum of AOV (Average Order Value):** 44,210

Visuals
- **Sum of Amount by State** — bar chart comparing revenue across Maharashtra, Madhya Pradesh, Delhi, and Uttar Pradesh
- **Sum of Quantity by Payment Mode** — donut chart showing order volume split across COD (44%), UPI (18%), Debit Card (16%), EMI (12%), and Credit Card (11%)
- **Sum of Profit by Month** — column chart tracking profit across January, February, and March
- **Sum of Amount by Customer Name** — bar chart highlighting top customers by revenue contribution
- **Sum of Quantity by Category** — donut chart comparing Clothing (63%), Electronics (19%), and Furniture (18%)
- **Sum of Profit by Sub-Category** — horizontal bar chart ranking Printers, Phones, Accessories, Bookcases, and Sarees by profit

Interactive Filters
- Quarter selector (Qtr 1–Qtr 4) at the top of the report
- Dropdown slicer (currently set to "All") for additional segmentation

----------------------------------------------------------------

💡 Key Insights

- COD remains the most-used payment mode at 44% of order volume, followed by UPI at 18%.
- Clothing dominates sales volume, accounting for 63% of quantity sold.
- Maharashtra is the top-performing state by revenue, nearly double the next closest state.
- Profit trended downward from January (9,684) through March (7,793) in Qtr 1.
- Printers and Phones are the highest profit-generating sub-categories.
- Harivansh is the top customer by revenue, contributing significantly more than other top customers.

----------------------------------------------------------------

🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query (data cleaning/transformation)
- DAX (Data Analysis Expressions)
- Microsoft Excel (data source)

----------------------------------------------------------------

📂 Repository Contents

| File | Description |
|------|-------------|
| `Madhav_Ecommerce_Sales_Dashboard.pbix` | Power BI project file (data model, DAX, dashboard) |
| `Sales Data Source.CSV` | Source sales dataset |
| `assets/` | Dashboard screenshot used in this README |

-------------------------------------------------------------

💼 Skills Demonstrated

Power BI Dashboard Development · Data Cleaning & Transformation · DAX Measures · KPI Design · Data Visualization · Sales & Profitability Analysis
