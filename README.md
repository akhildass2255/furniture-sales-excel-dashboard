# furniture-sales-excel-dashboard
An Excel project that analyses a furniture retail sales dataset of 2,500 records across 15 columns. It uses pivot tables and charts to show which categories, brands, seasons and channels drive revenue.
# Furniture Sales Excel Dashboard

An Excel data-analysis project that explores a furniture retail sales dataset using pivot tables, charts and slicers. It shows which products, brands, seasons, channels and locations drive revenue.

## Overview

The workbook analyses **2,500 sales records** across **15 columns**, covering pricing, cost, units sold, profit margin, inventory, discounts, delivery time and product attributes. The goal is to turn raw sales data into clear, interactive insights that support business decisions.

## Tools Used

- Microsoft Excel
- Pivot Tables and Pivot Charts
- Slicers for interactive filtering
- GETPIVOTDATA formulas for KPI summaries

## Repository Contents

| File | Description |
|------|-------------|
| `PROJECT_EXXEL.xlsx` | Main workbook with raw data, pivot tables and charts |

### Workbook Sheets

| Sheet | Description |
|-------|-------------|
| `Furniture` | Raw dataset (2,500 rows x 15 columns) |
| `pivot` | Pivot tables, 5 charts and a KPI summary |
| `dashbord` | Dashboard sheet |

## Dataset Description

| Column | Type | Description |
|--------|------|-------------|
| `price` | Numeric | Selling price per unit |
| `cost` | Numeric | Cost per unit |
| `sales` | Numeric | Units sold |
| `profit_margin` | Numeric | Profit margin (%) |
| `inventory` | Numeric | Stock available |
| `discount_percentage` | Numeric | Discount applied (%) |
| `delivery_days` | Numeric | Delivery time in days |
| `revenue` | Numeric | Revenue generated |
| `category` | Categorical | Bed, Chair, Desk, Sofa, Table |
| `material` | Categorical | Plastic, Glass, Metal, Wood, Fabric |
| `color` | Categorical | Red, Blue, Black, Green, Brown, White |
| `location` | Categorical | Urban, Suburban, Rural |
| `season` | Categorical | Spring, Summer, Fall, Winter |
| `store_type` | Categorical | Online, Retail |
| `brand` | Categorical | BrandA, BrandB, BrandC, BrandD |

## Analysis Performed

- Revenue by product category
- Revenue by brand
- Seasonal revenue trends
- Sales volume by store type (Online vs Retail)
- Revenue by location (Urban, Suburban, Rural)
- KPI summary: total sales, revenue, cost and discount

## Key Insights

- **Top category:** Table generates the highest revenue, followed by Sofa.
- **Top brand:** BrandC leads in total revenue.
- **Best season:** Fall performs strongest; Summer is the weakest.
- **Channel:** Online sales slightly outperform Retail.
- **Location:** Rural areas contribute the most revenue, followed by Suburban and Urban.

## Data Quality Notes

- The dataset has no missing values or duplicate rows.
- About 19% of rows (482) show negative revenue, and revenue does not always equal price x units sold. The data appears to be synthetic, so results are best used for demonstrating analysis techniques.
- The pivot tables in the saved file are filtered to the **Suburban** location through a slicer. Clear the slicer to see totals for the full dataset.

## How to Use

1. Download `PROJECT_EXXEL.xlsx`.
2. Open it in **desktop Microsoft Excel** (slicers may not work in other tools).
3. Go to the `pivot` sheet to explore the charts and use the slicers to filter the data.

## Future Improvements

- Rebuild the dashboard sheet with all charts and slicers in one view
- Add profit analysis by category and brand
- Clean or flag negative-revenue records
- Add screenshots of the dashboard to this README

## Author

*Your Name* - [GitHub](https://github.com/your-username)
