# Q1 Regional Sales Report

An Excel project that consolidates three months of regional sales data into a single formula-driven summary report using SUMIFS.

## What's Inside

- **January / February / March** — Monthly sales transaction sheets with Date, Product, Region, Sales Rep, Units Sold, Unit Price, and Total Sales.
- **Summary** — A rollup sheet built entirely with `SUMIFS` formulas that:
  - Aggregates **total sales by region** (North, South, East, West) for each month, pulling live from the January/February/March sheets
  - Calculates a **custom date-range total** (March 1–15) using a `SUMIFS` with `DATE()` bounds, demonstrating conditional aggregation beyond simple category matching

## Sample Formula

```excel
=SUMIFS(January!$G$2:$G$26, January!$C$2:$C$26, A2)
```
Sums Total Sales from the January sheet where Region matches the row label — repeated across all three months so the Summary sheet updates automatically as the monthly data changes.

## Skills Demonstrated

- `SUMIFS` for multi-month, multi-region aggregation
- Cross-sheet formula referencing
- Conditional date-range summing (`SUMIFS` + `DATE()`)
- Building a live, formula-driven summary report (no hardcoded totals)

## Tools Used

Microsoft Excel
