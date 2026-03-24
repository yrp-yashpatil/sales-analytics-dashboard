# sales-analytics-dashboard


---

🚀 Project Overview
- This project demonstrates a dual-platform approach to retail analytics. I transformed raw transactional data into an interactive intelligence tool available in both Excel (for advanced offline processing) and Google Sheets (for cloud-based stakeholder collaboration).
- The dashboard tracks sales performance across four coffee types, three international markets, and multiple customer segments.

---

# Technical Implementation
## Data Engineering & Transformation

- Dynamic Lookups: Used XLOOKUP and INDEX(MATCH) to join three disparate datasets (Orders, Customers, and Products) into a master relational table.

- Logic Layer: Implemented nested IF statements to standardize product naming conventions and handle missing data points.

- Data Cleaning: Applied custom number formatting and data validation to ensure consistency across kilograms (kg) and currency (USD).

## Analytics & Visualization

- Pivot Table Architecture: Engineered multi-dimensional tables to calculate:

- Temporal Trends: Total sales over time segmented by coffee type.

- Geographic Performance: Market share analysis for the US, UK, and Ireland.

- Customer Profiling: Identifying the "Top 5 Customers" by revenue.

- Interactive UI/UX: * Linked Slicers (Roast, Size, Loyalty Status) and Timelines to multiple visuals via Report Connections.

- Designed a "Clean-View" interface by removing gridlines and headers to mimic a standalone BI application.

---

# Business Insights Delivered

- Market Dominance: Identified which specific coffee bean sizes drive the highest volume in the US vs. European markets.

- Retention Analysis: Quantified the revenue impact of the Loyalty Card program across different roast preferences.

- Product Strategy: Visualized sales spikes to correlate with potential seasonal marketing efforts.

---
