# Audio Product Sales Analytics Dashboard

## 1. Short Description / Purpose

A comprehensive Power BI dashboard for analyzing sales, revenue, and discount performance of professional audio products across multiple countries and customer segments. The dashboard helps business stakeholders quickly identify trends, regional performance, and discount strategies using data integration and dynamic visualizations.

## 2. Tech Stack

- **Power BI** (dashboard creation and visualization)
- **Excel (CSV files)** (raw data storage and initial formatting)
- **PostgreSQL** (for data cleaning, transformation, and extraction)
- **Power Query** – Data transformation and cleaning layer for reshaping and preparing the data.
• **DAX (Data Analysis Expressions)** – Used for calculated measures, dynamic visuals, and conditional logic.
- **Data Modeling** – Relationships established among tables (resorts, snow, and data_dictionary) to enable cross-filtering and aggregation.

## 3. Data Source

The data originates from several structured **CSV files**:
- **product_data.csv:** Audio product catalog including specifications and descriptions.
- **product_sales.csv:** Detailed transactional sales records, including date, product, units sold, customer type, country, and applied discount bands.
- **discount_data.csv:** Monthly breakdown of discount bands and their respective discount rates.

Data was imported into **PostgreSQL** for cleaning, normalization, and enrichment before being fed into Power BI for dynamic reporting. The datasets are tabular, relational, and suitable for time-series, categorical, and geographical analysis.

## 4. Features / Highlights

- **Business Problem:**  
  Audio equipment companies struggle to monitor live-market sales performance, regional revenue, and how discount strategies affect sales across multiple distribution and customer channels.

- **Goal of the Dashboard:**  
  To provide actionable insights on sales performance, highlight the effectiveness of different discount bands, and enable data-driven decisions regarding product strategy, pricing, and regional focus.

- **Walkthrough of Key Visuals:**  
  - **Revenue by Country:**  
    Identifies top contributing countries (e.g., Canada, USA, France) to overall revenue, supporting regional sales strategy adjustments.
  - **Revenue by Date and Year:**  
    Compares monthly revenue trends over 2022 and 2023, highlighting seasonal patterns and year-over-year growth.
  - **Table Breakdown (by Customer Type):**  
    Dissects revenue by customer segments such as Education, Enterprise, and Creator, showing segment priorities.
  - **Discount Band Breakdown:**  
    Displays the proportion of sales in None, Low, Medium, and High discount bands via a donut chart, offering an at-a-glance understanding of discount utilization and potential margin impacts.
  - **Product Focus Panels:**  
    Dedicated insights into specific product lines (e.g., Arctis 7P+) with contextual information and sales breakdowns.

- **Business Impact & Insights:**  
  - Identifies top-performing products and markets for prioritization.
  - Tracks YoY profit and unit sold growth (e.g., +7% Profit YoY, +8% Units Sold YoY).
  - Measures the profitability and risks of discount strategies.
  - Influences inventory planning, marketing budgets, and promotional targeting based on actual sales data.
  - Equips management and sales teams with rapid access to critical metrics, promoting data-driven decision-making.

 ## 5. Screenshot
![Dashboard Screenshot](https://github.com/mannnrathod28/Integrated-Data-Visualization-Project-Power-BI-PostgreSQL-Excel-/blob/main/Snapshot%20of%20Dashboard.png?raw=true)


