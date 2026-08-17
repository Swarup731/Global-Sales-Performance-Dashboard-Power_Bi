# Global Sales Performance Dashboard

A Power BI dashboard providing an overview of global sales performance, including customer, order, and revenue metrics broken down by product line, deal size, geography, and time.

## Overview

This dashboard visualizes sales performance data to help stakeholders track revenue trends, understand product mix, and identify top-performing markets.

## Key Metrics (KPI Cards)

| Metric | Value |
|---|---|
| Total Customers | 92 |
| Total Sales | 10.03M |
| Average Order Value | 32.68K |
| Total Quantity | 99K |
| Total Orders | 307 |
| YoY Growth % | 0.22 |

## Visuals

### 1. Total Sales by Product Line (Bar Chart)
Shows total sales across product categories. **Classic Cars** is the top-performing line at 3.9M, followed by Vintage Cars (1.9M), Motorcycles (1.2M), Trucks and Buses (1.1M), Planes (1.0M), Ships (0.7M), and Trains (0.2M).

### 2. Total Sales by Order Date (Column Chart)
Displays sales volume over time (2004–2005), highlighting daily/periodic spikes in order value, with peak values such as 138K and 131K called out on the chart.

### 3. Total Sales and Previous Year Sales by Order Date (Line Chart)
Compares current year sales against the previous year across the same time period, enabling year-over-year trend comparison.

### 4. Total Sales by Deal Size (Donut Chart)
Breaks down sales by deal size classification:
- Medium: 6.09M (60.68%)
- Small: 2.64M (26.34%)
- Large: 1.3M (12.98%)

### 5. Total Sales by Deal Size and Product Line (Stacked Bar Chart)
Cross-tabulates deal size (Medium, Small, Large) against product line to show which products drive sales within each deal size segment.

### 6. Total Sales by Country (Map)
Geographic visualization (bubble map) showing the distribution of total sales across countries, with bubble size indicating relative sales volume. Sales are concentrated in North America and Europe.

## Data Fields Used

- **ORDERDATE** – Date of order (time-based analysis)
- **PRODUCTLINE** – Category of product sold (Classic Cars, Vintage Cars, Motorcycles, Trucks and Buses, Planes, Ships, Trains)
- **DEALSIZE** – Size classification of the deal (Small, Medium, Large)
- **COUNTRY** – Customer/order country for geographic analysis
- **Total Sales / Total Quantity / Total Orders / Total Customers** – Aggregated measures

## Tools & Technology

- **Power BI Desktop** – Report authoring and visualization
- **Microsoft Bing Maps** – Geographic (country-level) map visual

## How to Use

1. Open the `.pbix` file in Power BI Desktop.
2. Use the **Total Sales by ORDERDATE** chart to explore trends over time; hover for exact daily values.
3. Use the **Country map** to identify top-selling regions.
4. Cross-filter by clicking on any visual (e.g., a product line bar) to filter all other visuals accordingly.
5. Refer to the KPI cards at the top for a quick performance snapshot.

## Notes

- Data covers order activity primarily across 2004–2005.
- "Total Sales by Deal Size and Product Line" chart includes a scrollable legend (additional product lines available via the arrow control).
- Map attribution: © Microsoft Corporation / Microsoft Bing.
