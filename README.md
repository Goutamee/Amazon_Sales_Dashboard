**Amazon Sales Dashboard**

1. Headline

Amazon.in Sales & Order Analytics Dashboard (2022)

2. Purpose

This dashboard provides an end-to-end analysis of Amazon India's sales operations, covering over 20,000 orders across apparel and lifestyle categories. It enables stakeholders to monitor order fulfillment performance, track revenue by product category and region, understand cancellation patterns, and compare fulfillment methods — empowering data-driven decisions for supply chain and sales strategy.

3. Key Technologies Used

- Microsoft Power BI Desktop — for building the interactive dashboard (`.pbix` file)
- Microsoft Excel / CSV — as the primary data source (`.xlsx` file with 20,000+ records)
- DAX (Data Analysis Expressions) — for calculated measures and KPIs within Power BI
- Power Query (M Language) — for data transformation and cleaning inside Power BI
- Excel / Openpyxl — underlying data format for structured tabular storage

4. Data Source

More info on where data come from and how it's structured, source: Kaggle.

- File: `Amazon_Sales_Report.xlsx`
- Sheet: `Amazon Sale Report`
- Records: ~20,000 orders
- Fields (19 columns):
  - Order details: `Order ID`, `Date`, `Status`, `Courier Status`
  - Product info: `Category` (T-shirt, Shirt, Blazzer, Trousers, Perfume, Socks, Shoes, Wallet), `Size`
  - Fulfillment: `Fulfilment` (Amazon / Merchant), `fulfilled-by` (Ekart / Easy Ship), `ship-service-level` (Standard / Expedited)
  - Geography: `ship-city`, `ship-state` (51 states/UTs), `ship-postal-code`, `ship-country` (India)
  - Financials: `Amount` (in INR), `Qty`, `currency`
  - Channel: `Sales Channel` (Amazon.in / Non-Amazon), `B2B` flag

5. Features of the Dashboard

- Sales KPIs — Total revenue (INR), total orders, average order value, and total quantity sold
- Order Status Breakdown — Visual split of Shipped, Delivered, Cancelled, Returned, Lost in Transit, and Out for Delivery orders
- Category-wise Performance — Revenue and volume comparison across T-shirts, Shirts, Blazers, Trousers, Perfume, Socks, Shoes, and Wallets
- Geo Analysis — State-level and city-level sales distribution across 51 Indian states/UTs
- Fulfillment Analysis — Amazon vs. Merchant fulfillment comparison; Ekart vs. Easy Ship courier breakdown
- B2B vs. B2C Segmentation — Separate view of business and consumer orders
- Service Level Insights — Standard vs. Expedited shipping trends
- Cancellation Analysis — Identifying high-cancellation categories, regions, or fulfillment types
- Time-Series Trends — Sales and order volume trends over the reporting period
- Interactive Filters/Slicers — Filter by category, state, fulfillment type, order status, and date range

6. Screenshot of the Dashboard

https://github.com/Goutamee/Amazon_Sales_Dashboard/blob/main/Amazon%20Sales%20Dashboard.png?raw=true
