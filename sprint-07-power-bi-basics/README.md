# Sprint 07 - Power BI Basics

Guided Power BI dashboard exercise based on online sales transaction data.

## Objective

The goal of this sprint was to build Power BI report pages that answer specific business questions using clear visualizations, KPI cards, DAX measures, slicers, and a well-defined data model.

The coursework required one report page per level, progressing from basic KPIs and sales summaries to customer, product, and geographic analysis.

## Dataset And Model

The report uses transaction data from an online sales company, with related information about users, companies, credit cards, products, dates, and transaction-product relationships.

Main model elements include:

- `transactions` as the central transaction table
- `users`, `companies`, `credit_cards`, and `products` as related descriptive tables
- `Calendar` for date-based analysis
- `transactions_products` as a bridge table between transactions and products
- `Tabla de Medidas` as a dedicated measures table

## Report Focus

The dashboard explores:

- annual and monthly sales revenue
- yearly and monthly business targets
- average transaction amounts
- companies by country
- customer transaction summaries
- Germany-specific sales analysis
- sales by age group
- product price metrics
- product purchase quantities
- geographic distribution of users

## Skills Practiced

- Loading and modelling data in Power BI
- Creating KPI cards and gauge visuals
- Building DAX measures for sales totals, averages, targets, and filtered calculations
- Creating and using a calendar table
- Designing readable report pages
- Using maps and slicers for exploratory analysis
- Presenting multiple business questions in a single dashboard page

## Further Improvements

- Validate the product-level metrics used for cheapest and most expensive products.
- Improve map visuals with clearer legends and stronger geographic interpretation.
- Add or refine data labels where they improve readability.
- Review axis ranges to avoid exaggerating differences between values.
- Expand slicer usage to make the report more interactive.

## Notes

The original historical file was named `Sprint 7 bis.pbix`; it is renamed here as `sprint-07-power-bi-basics.pbix` for portfolio clarity.