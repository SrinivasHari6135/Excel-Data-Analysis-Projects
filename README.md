# Inventory Analysis

An Excel project analyzing inventory ordering data across multiple warehouses to understand stocking cost patterns by city and product category.

## What's Inside

- **Inventory Orders** — Raw order-level data: Order ID, Order Date, SKU, Warehouse (city), Units Ordered, Unit Cost, Product Name, Category, Reorder Level, and Total Cost.
- **Product Master** — A lookup table of all SKUs with their Product Name, Category, and Reorder Level (Apparel, Footwear, Accessories).
- **Analysis** — A Pivot Table summarizing **Sum of Total Cost by City × Category**, across 5 warehouse cities (Bengaluru, Chennai, Hyderabad, Mumbai, Pune) and 3 categories (Accessories, Apparel, Footwear).

## Key Insight

**Hyderabad** and **Bengaluru** carry the highest total inventory cost overall, with **Accessories** as the single largest cost category company-wide (~₹4.2L of the ~₹7.2L grand total) — useful for identifying where inventory spend is concentrated and where reorder policies matter most.

## Skills Demonstrated

- Pivot Tables (cross-tabulation by two dimensions)
- Lookup tables for enriching transactional data with product master info
- Cost aggregation and category-level analysis
- Multi-warehouse data organization

## Tools Used

Microsoft Excel
