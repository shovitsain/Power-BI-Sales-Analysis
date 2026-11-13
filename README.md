# ClipKart – E-commerce Performance Dashboard

## Project Overview

**ClipKart** is an interactive e-commerce performance dashboard built with **Microsoft Power BI**. It presents key business metrics and visual summaries to help understand sales performance across products, categories, cities, prices, and order volume.

The report is designed as a single-page dashboard titled **Performance Report FY 2027**.

## Dashboard Highlights

The report includes the following KPI cards and visualizations:

- **Total Revenue** – Sum of the `Revenue` field.
- **Total Quantity** – Sum of the `Quantity` field.
- **Total Orders** – Count of non-empty `OrderID` values.
- **Average Order Value** – A measure named `Avg Order Value` in the data model.
- **Revenue by Category** – Column chart comparing revenue across product categories.
- **Revenue by City** – Bar chart showing the top three cities by revenue.
- **Top 5 Products by Revenue** – Table displaying products ranked by revenue.
- **Revenue by Price** – Line chart showing revenue against product price.
- **Category Revenue Share** – Donut chart showing each category's contribution to revenue.

## Tools and Technologies

- **Microsoft Power BI Desktop** – Dashboard development and data visualization.
- **Power BI Data Model** – Stores the imported e-commerce data and measures.

## Data Model

The report uses a table named `clipkart_ecommerce_data`.

Fields referenced by the report visuals include:

| Field / Measure | Purpose |
|---|---|
| `Revenue` | Revenue calculations and comparisons |
| `Quantity` | Total quantity KPI |
| `OrderID` | Order count KPI |
| `Product` | Product-level revenue analysis |
| `Category` | Category-level revenue analysis |
| `City` | City-level revenue analysis |
| `Price` | Price and revenue analysis |
| `Avg Order Value` | Average order value KPI measure |

> Note: The source file does not expose the complete data dictionary or the exact formula for `Avg Order Value` in the report definition. Confirm these details in Power BI before publishing business-critical figures.

## How to Open the Project

1. Install **Microsoft Power BI Desktop**.
2. Download or clone this repository.
3. Open `clipkart.pbix` in Power BI Desktop.
4. If Power BI asks for data-source credentials or a file path, update the source settings to match the location of your dataset.
5. Refresh the data if the source is available.
6. Explore the dashboard visuals and interact with the report.

## Repository Structure

```text
ClipKart/
├── clipkart.pbix
└── README.md
```

If you also publish the source dataset, add it to the repository (or provide a secure download location) and document its filename, format, and required refresh steps here.

## Notes

- The dashboard contains one report page.
- The report page is configured for a 1920 × 1080 canvas.
- KPI values depend on the data loaded into the Power BI model.
- The `.pbix` file is the editable Power BI project.

## Author

**Shovit Sain, 8967932626**

