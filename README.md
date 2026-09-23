# ☕ Coffee Sales Dashboard

An interactive Excel dashboard analyzing **149,000+ coffee shop transactions**, built with PivotTables, PivotCharts, slicers, and a timeline filter. The workbook breaks down sales by location, time, product, and category to surface trends in coffee shop performance.


## Overview

This project transforms raw point-of-sale data into an interactive, at-a-glance dashboard that answers key business questions:

- Which store locations generate the most revenue?
- What time of day, day of week, and month drive the highest sales?
- Which product categories and products are top sellers?
- How do sales trends shift across the year?

## Dataset Schema

The `Dataset` sheet contains the following fields:

| Column | Description |
|---|---|
| `transaction_id` | Unique ID for each transaction |
| `transaction_date` | Date of the transaction |
| `transaction_time` | Time of the transaction |
| `store_id` | Store identifier |
| `store_location` | Store location name |
| `product_id` | Product identifier |
| `transaction_qty` | Quantity of items sold in the transaction |
| `unit_price` | Price per unit |
| `product_category` | High-level category (Coffee, Tea, Bakery, etc.) |
| `product_type` | Product type/sub-category |
| `product_detail` | Specific product name |
| `Size` | Product size (e.g., Small, Regular, Large) |
| `Total_bill` | Total transaction value (`transaction_qty × unit_price`) |
| `Month Name` | Month extracted from transaction date |
| `Day Name` | Day of week extracted from transaction date |
| `Hour` | Hour extracted from transaction time |
| `Day of Week` | Numeric day-of-week value |
| `Month` | Numeric month value |

## Dashboard Features

- **14 PivotCharts** visualizing sales across location, time, product, and category dimensions
- **Slicers** for interactive filtering by store location, product category, and day name
- **Timeline control** for filtering by transaction date range
- **PivotTables** powering each chart, all connected to a shared pivot cache for consistent, fast filtering

## Tools Used

- Microsoft Excel — PivotTables, PivotCharts, Slicers, Timeline

## License

Feel free to use, modify, and share this dashboard for personal or educational purposes.
