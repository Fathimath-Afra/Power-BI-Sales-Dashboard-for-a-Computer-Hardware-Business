# 📊 Power BI Sales Insights Dashboard

## Overview

This project delivers an interactive **Power BI dashboard** designed for a **computer hardware business** operating in a dynamically changing market. The dashboard provides **real-time sales insights** to support strategic decision-making and replaces time-consuming manual reporting processes.

## Objective

To unlock hidden sales trends and deliver region-wise, customer-wise, and product-wise performance insights by using automated data pipelines and visualization through Power BI.

## Data Source & Tools Used

- **SQL**: Used for querying and transforming raw sales data from the company’s central database.
- **Power BI Desktop**: Used to build interactive visualizations and dashboards.
- **Data Sources**:
  - Sales transactions (revenue and quantity)
  - Customer master data
  - Product master data
  - Regional mapping (zones and markets)

## Key Insights Delivered

- 📍 **Top Markets**: Delhi NCR leads with ₹519.51M in revenue.
- 👥 **Top Customers**: Electricalsara Stores contributes ₹413.33M in sales.
- 📦 **Top Products**: Product `Prod040` alone generated nearly ₹470M.
- 🌍 **Regional Performance**:
  - North Zone: ₹680M revenue and 1.27M units sold.
  - Central & South Zones: Significantly lower contribution.
- 📈 **Revenue Trends**: Steady growth from 2018 to 2020, with seasonal peaks.
- 🧠 **Data-Driven Benefits**:
  - Real-time insights
  - Quick decision support
  - Reduced manual effort

## How It Works

1. **SQL Data Preparation**:
   - Cleaned and joined multiple tables (sales, customers, products, regions).
   - Aggregated data for KPIs like revenue, quantity, and trends.
   - Exported the transformed datasets to CSV or connected directly to Power BI.

2. **Power BI Visualization**:
   - Designed dashboards with filters for year, product, region, and customer.
   - Used slicers, bar charts, KPIs, and trend lines for interactive analysis.
   - Incorporated drill-down functionality for detailed exploration.

## Getting Started

1. Clone the repository.
2. Run SQL scripts to extract and clean data.
3. Load the processed data into Power BI or connect Power BI directly to your SQL source.
4. Open the `.pbix` file in Power BI Desktop to explore and customize the dashboard.

