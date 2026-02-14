Business Intelligence 360: Global Sales & Financial Analytics

🌟 Project Summary
AtliQ Hardware, a global leader in computer peripherals and networking equipment, reached a critical turning point where rapid expansion outpaced their traditional Excel-based tracking. After a significant financial setback in the North American market due to suboptimal data insights, the company initiated this Power BI project to transition into a truly data-driven organization.

This comprehensive BI solution provides a 360-degree view of the business, integrating massive datasets to empower stakeholders across Finance, Sales, Marketing, and Supply Chain with real-time, actionable insights.

💻 Technical Overview
Data Modeling: Star Schema & Snowflake Schema
Processing: SQL (MySQL) for data extraction
Visualization: Power BI Desktop
Analytics: Advanced DAX (Data Analysis Expressions)
Optimization: DAX Studio (for performance tuning)
Other Tools: Microsoft Excel

🏢 Business Context & Problem Statement
AtliQ Hardware operates via a diverse distribution network:

1. Retailers: Physical and online storefronts.
2. Direct Sales: AtliQ-owned platforms.
3. Distributors: Large-scale regional partners.

The Challenge: Reliance on static surveys and manual spreadsheets led to a failed expansion in the USA. This project was engineered to replace "gut feeling" with a robust analytics system capable of processing 1.5M+ rows of data to mitigate risk and maximize ROI.

📂 Data Overview
The intelligence engine is fueled by two primary databases: gdb041 (Operational Data) and gdb056 (Financial Metrics).

1. Database: gdb041
   
dim_customer: Detailed profiles of 75+ global customers (e.g., Amazon, Flipkart) across Brick & Mortar and E-commerce.
dim_market: Geographic hierarchy spanning 27 markets and 4 regions (APAC, EU, NAN, LATAM).
dim_product: Granular product data across 3 divisions P&A (Peripherals & Accessories), PC (Notebooks & Desktops), N&S (Networking & Storage) and 14 categories.
fact_sales_monthly & fact_forecast_monthly: The core transactional tables used to calculate Forecast Accuracy and inventory health.

2. Database: gdb056 (Financial & Logistics)
   
gross_price: Baseline pricing strategies.
manufacturing_cost: Tracking production expenses over time.
pre_invoice_deductions: Pre-set discounts at the customer level.
post_invoice_deductions: Variable deductions, claims, and promotions.
freight_cost: Logistics and shipping overheads per market.

📊 Dashboard Insights
💰 Finance View - Focuses on P&L statements, Net Sales, and Gross Margin percentages to track the financial heartbeat of the company.
<img width="1875" height="1060" alt="Finance View" src="https://github.com/user-attachments/assets/6c4b5546-6bf4-4afc-ab70-32611371b05c" />

📈 Sales & Marketing View
Identifies top-performing customers and products while analyzing market share and promotional effectiveness.
Sales View <img width="1871" height="1055" alt="Sales View" src="https://github.com/user-attachments/assets/facd5ed9-1f2f-4469-ab72-9a3d68783afd" />
Marketing View <img width="1877" height="1052" alt="Marketigng View" src="https://github.com/user-attachments/assets/fcef43dc-adf8-4505-9fd6-fa362f95116b" />

🚚 Supply Chain View
A critical view for inventory management, highlighting the gap between forecasted demand and actual sales to reduce stockouts and overstock.
<img width="1875" height="1053" alt="Supply Chain View" src="https://github.com/user-attachments/assets/7ed762e9-c23b-4a6c-832a-b998b959778c" />

👑 Executive View
A high-level summary for leadership, consolidating KPIs from all departments to provide a snapshot of global business health.
<img width="1875" height="1050" alt="Executive View" src="https://github.com/user-attachments/assets/05305c6c-ff74-4b42-a3a8-48760a6bc63f" />


🚀 Key Deliverables & Outcomes:

By implementing this BI 360 solution, AtliQ Hardware successfully achieved:
  Reduced Data Latency: Instant access to KPIs that previously took days to compile.
  Profitability Tracking: Ability to drill down into "Net Profit" by individual product and market.
  Improved Forecast Accuracy: A systematic way to identify and correct forecasting errors, saving millions in logistics and storage.
