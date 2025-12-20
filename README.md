# 🚗 Electric Vehicle Population Analysis (Tableau)

This project analyzes electric vehicle (EV) adoption trends using Tableau, based on publicly available electric vehicle population data. The objective is to explore how EV adoption varies by geography, vehicle type, manufacturer, and model year, and to communicate insights through interactive visualizations and storytelling

## Project Overview
The Tableau analysis focuses on:
- Growth trends in electric vehicle adoption over time
- Geographic distribution of EVs by state, county, and city
- Comparison of Battery Electric Vehicles (BEVs) vs Plug-in Hybrid Electric Vehicles (PHEVs)
- Popular manufacturers and vehicle models
- Electric range and eligibility for clean alternative fuel incentives

```
├── Electric_Vehicle_Population_Data_Electric_Vehicle_Population_Data.csv
├── HW_Assignment_Final.pptx
└── README.md
```

## Dataset
**Electric_Vehicle_Population_Data_Electric_Vehicle_Population_Data.csv**

This dataset contains detailed records of registered electric vehicles in the United States. Each row represents an individual electric vehicle registration.

| Column Name | Description |
|------------|-------------|
| **Base MSRP (bin)** | Binned/category version of Base MSRP (e.g., `0K`) used for grouping in visuals |
| **CAFV Eligibility** | Clean Alternative Fuel Vehicle eligibility category (e.g., `CAFV Unknown`) |
| **City** | City where the vehicle is registered |
| **County** | County where the vehicle is registered |
| **Electric Utility** | Utility provider(s) serving the registration area (sometimes multiple separated by `|`) |
| **EV Type** | Electric vehicle type (e.g., `BEV`, `PHEV`) |
| **Make** | Manufacturer (e.g., VOLKSWAGEN) |
| **Model** | Vehicle model (e.g., ID.4) |
| **Model Year** | Model year of the vehicle |
| **Postal Code** | ZIP code of registration |
| **State** | State of registration (e.g., WA) |
| **Vehicle Location** | Geographic point (longitude, latitude) in `POINT (lon lat)` format |
| **VIN (1-10)** | First 10 characters of the VIN (partial identifier) |
| **% of BEV Vehicles** | Share/proportion of BEV vehicles for the relevant grouping level used in Tableau |
| **% of PHEV Vehicles** | Share/proportion of PHEV vehicles for the relevant grouping level used in Tableau |
| **2020 Census Tract** | Census tract identifier (2020) for location-based analysis |
| **Avg Electric Range** | Average electric range metric used in Tableau (often aggregated by group) |
| **Base MSRP** | Base manufacturer suggested retail price (numeric) |
| **DOL Vehicle ID** | Department of Licensing vehicle identifier |
| **Electric Range** | Electric-only range value for the vehicle (miles) |
| **Legislative District** | Legislative district number associated with the registration location |
| **Range Comparision** | Derived comparison label (e.g., `Below Target`) used for categorizing range against a threshold |
| **Record Count** | Row count field (typically `1`) used for Tableau aggregations |
| **Total BEV Vehicles** | Derived/aggregated total BEV count for the grouping level used in Tableau |
| **Total PHEV Vehicles** | Derived/aggregated total PHEV count for the grouping level used in Tableau |
| **Total vehicles** | Derived/aggregated total vehicle count for the grouping level used in Tableau |

## Tableau Dashboard
The Tableau dashboard was built using the above dataset and includes multiple interactive views and filters to support exploratory analysis. The dashboard enables users to:
- Filter EV data by year, location, vehicle type, and manufacturer
- Analyze adoption trends over time
- Compare BEVs and PHEVs
- Explore geographic concentration of EV registrations

This presentation documents the Tableau analysis and includes:
- Dashboard screenshots
- Explanation of key visualizations
- Summary of analytical findings
- Interpretation of trends and insights related to EV adoption

The presentation serves as a walkthrough of the Tableau dashboard and the conclusions drawn from the data.

## Key Insights
-BEVs dominate EV adoption, with fully electric vehicles accounting for the majority of registrations compared to PHEVs.

-EV adoption is geographically concentrated, with higher registrations in urban areas, indicating the influence of infrastructure and policy support.

-Recent model years show rapid growth, reflecting increased consumer adoption and improved EV availability in recent years.

-Adoption is driven by a small set of manufacturers, showing market concentration despite overall growth.

