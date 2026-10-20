# Mobile Sales Performance Dashboard

## Overview

An interactive Power BI dashboard project designed to explore mobile sales performance across brands, mobile models, cities, payment methods, customer ratings, and time periods.

The report presents sales KPIs and visual summaries to help users investigate product performance and customer purchasing patterns.

## Dashboard Preview

![Mobile Sales Performance Dashboard](screenshots/dashboard-overview.png)

## Business Objectives

- Analyze sales performance across mobile brands and models.
- Explore city-level sales distribution.
- Examine monthly quantity trends.
- Understand customer rating distribution.
- Compare transaction distribution across payment methods.
- Enable interactive exploration through report filters.

## Dashboard Features

- KPI cards for key sales metrics.
- City-level sales map.
- Monthly quantity trend chart.
- Customer ratings visualization.
- Payment-method distribution chart.
- Brand and mobile-model comparisons.
- Filters for mobile model, payment method, brand, day name, and month.

## Dataset

The supplied Excel workbook contains 3,835 records and 14 columns.

The dataset includes mobile sales information such as brand, mobile model, city, payment method, customer rating, quantity, price, and date-related fields.

Dataset source: [Add the original source URL here]

> Include the dataset only if its license permits redistribution. Otherwise, provide the source link or a small, non-sensitive sample if permitted.

## Tools and Technologies

- Microsoft Power BI
- Microsoft Excel
- DAX and Power Query — include these after confirming their use in the report

## Getting Started

1. Download or clone this repository.
2. Install Microsoft Power BI Desktop.
3. Open `Mobile Sales Dashboard.pbix`.
4. If prompted, configure the data source path to the included Excel workbook.
5. Refresh the data and verify that the report visuals load correctly.

## Validation Notes

The source workbook was checked for missing values and duplicate transaction IDs. The weekday labels require standardization.

The Power BI report's calculations, slicer interactions, map accuracy, and refresh behavior should be validated before treating the dashboard as fully verified.

## Limitations

- The report is currently a single-page dashboard.
- Geographic accuracy depends on the map configuration and location resolution.
- Business conclusions depend on the definitions and correctness of the underlying metrics.

## Future Improvements

- Standardize weekday labels and add chronological sorting.
- Validate all KPI calculations against the source data.
- Improve tooltips and drill-through analysis.
- Add a documented date table and reusable measures where appropriate.
- Publish an accessible demo if supported by the report configuration and sharing permissions.

## Author

**Avinash Patel**

- GitHub: https://github.com/AvinashWorks-07
- LinkedIn: https://linkedin.com/in/avinash-patel-953b71303
