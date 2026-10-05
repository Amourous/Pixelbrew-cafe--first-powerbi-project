# Pixelbrew Cafe - First PowerBI Project

This repository contains my first PowerBI project for Pixelbrew Cafe.

## Dashboard Overview

The `PixelBrew_Executive_Dashboard.pbix` file contains a multi-page interactive dashboard with the following sections:

1. **Page 1 (Executive Summary):** High-level business metrics and KPIs.
2. **Regional Map:** Geographical visualization of performance across different regions using Azure Maps.
3. **Customer Details:** In-depth view of customer demographics and purchasing behavior.
4. **What-if Simulator:** Interactive scenario modeling to forecast different business outcomes.

### Visualizations Used
The dashboard uses a variety of Power BI visuals to tell the data story, including:
- **KPI Cards** for at-a-glance metrics
- **Clustered Bar & Column Charts** for categorical comparisons
- **Line Charts** for trend analysis over time
- **Azure Maps** for spatial/geographical data
- **Tables** for detailed record viewing
- **Slicers and Action Buttons** for interactive filtering and navigation

## Files Included

- `PixelBrew_Executive_Dashboard.pbix`: The main PowerBI dashboard file containing the data model and all report pages.
- `Dim_Customers.csv`: Customer dimension data. Contains demographic and detail information about the cafe's customers.
- `Dim_MenuItems.csv`: Menu items dimension data. Contains the cafe's product catalog, including item names, categories, and prices.
- `Fact_Orders.csv`: Orders fact data. The core transactional table recording every order placed, which links to the customer and menu item tables.
