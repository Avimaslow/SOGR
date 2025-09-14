# State of Good Repair (SOGR) Dashboard

## Overview
The State of Good Repair (SOGR) Dashboard provides a centralized view of asset readiness across the organization.  
It is designed to help stakeholders monitor asset health, replacement cycles, and projected upgrade timelines with interactive visuals.  

This project consolidates data from multiple sources, aligns asset information with SOGR planning years, and presents clear drill-downs by location, device type, and model.  

---

## Page 1 – Asset Inventory & Install Status

![SOGR Assets Overview]([https://github.com/Avimaslow/SOGR/blob/main/Screenshots/SOGRMainPage.png](https://github.com/Avimaslow/SOGR/blob/main/Screenshots/SOGRMainPageBlackedOut.png))

### Key Metrics
- **SOGR Assets** – Total assets in scope (29,467 in this view)  
- **Assets With No Location Info** – Identifies records missing location data for correction  

### Install Status
- Tracks whether assets are installed, in stock, in repair, or pending installation  
- Provides total counts for operational readiness  

### Device Breakdown
- **Device Name** table highlights the most common hardware (OptiPlex, Latitude, etc.)  
- **SOGR by Year** bar chart shows replacement volumes over time (2026–2030)  

### Locations
- Detailed list of top sites with total asset counts  
- Interactive map visualizing geographic distribution of assets  

---

## Page 2 – Monitors & Asset Cost

![SOGR Monitors](https://github.com/Avimaslow/SOGR/blob/main/Screenshots/MonitorsSogrBlackedOut.png)

### Key Metrics
- **SOGR Monitors** – Total monitors in scope (21,226 in this view)  
- **Pending Disposal** – Monitors flagged for retirement  

### Device Details
- **Device Type** – LCD, Multimedia, Smartboard, TV  
- **Devices Table** – Model-level breakdown of monitors and counts  

### Substate & Lifecycle
- Tracks monitors by status: available, defective, pending install, pending disposal  
- Links to associated cost data for better financial planning  

### User Assignment
- Connects monitors to specific users  
- Shows employment status, total assigned monitors, and total cost contribution  

### Locations & Map
- Displays top monitor storage/usage locations  
- Interactive map showing deployment across depots and offices  

---

## Page 3 – SOGR Planning & Forecasting

![SOGR Forecasting]([https://github.com/Avimaslow/SOGR/blob/main/Screenshots/ScenarioPage.png](https://github.com/Avimaslow/SOGR/blob/main/Screenshots/ScenarioPageBlackedOut.png))

### Key Metrics
- **SOGR Assets** – Total asset base (29,467 in this view)  
- **Projected Finished Date** – Estimated completion of SOGR plan (6/30/2034 here)  
- **Months Needed** – Remaining duration to achieve completion (102 months in this view)  

### Yearly Targets
- Adjustable yearly sliders define planned replacement volumes  
- Updates projected finish dynamically  

### Locations
- Site-by-site breakdown of device counts included in the SOGR plan  

### Models & Forecast
- **Models Table** – Shows device families included in replacement (Surface Pro, HP ProBook, etc.)  
- **Devices by SOGR Year** stacked area chart – Projects replacement demand by model over time (2026–2030)  

---

## Features

- 📊 **Interactive Dashboards** – Drill down by location, device type, model, or user  
- 🗺️ **Geospatial Mapping** – Visualizes asset distribution across NYC and beyond  
- ⏱️ **Forecasting Tools** – Dynamic sliders and projections for long-term planning  
- 🔍 **Transparency** – Clear breakdowns of asset status, costs, and upcoming needs  

---

## How to Use
1. Navigate between pages to explore **Assets Overview**, **Monitors**, and **Forecasting**.  
2. Use slicers and filters to focus on specific locations, years, or device models.  
3. Leverage the map visuals to quickly identify high-density asset areas.  

---

## Roadmap
- Integration of additional asset classes beyond PCs and monitors  
- Alignment with financial reporting for cost forecasting  
- Automated data pipeline from SCCM, ServiceNow, and asset management tools  

---

## Screenshots
- `screenshots/sogr_assets.png` – Asset Inventory & Install Status  
- `screenshots/sogr_monitors.png` – Monitor Lifecycle & Costs  
- `screenshots/sogr_forecast.png` – Forecasting & Long-Term Planning  

---
