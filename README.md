# Nigeria Health Accessibility Risk Analysis

## Overview

Health accessibility risk in Nigeria is not evenly distributed, and looking only at state-level averages can hide where the need is greatest. This project maps that risk across three administrative levels, from Ward up through Local Government Area (LGA) to State, using GRID3's ward-level health facility access risk scores as the base dataset. Ward scores are aggregated to LGA and State averages so the results can be compared across scales, with the full analysis presented through thematic maps and an interactive ArcGIS dashboard.

## Objectives

- Map how health accessibility risk varies across Nigerian wards.
- Classify risk into five categories at ward level, then aggregate to LGA and State averages using the same scale.
- Identify the highest-risk LGAs and States.
- Make the results explorable through an interactive dashboard, not just static maps.

## Data Source

Data comes from GRID3 (Geo-Referenced Infrastructure and Demographic Data for Development), specifically the ward-level health facility access risk score dataset

## Methodology

The analysis followed these main steps:

1. Prepared the GRID3 ward-level health accessibility risk data.
2. Classified ward-level risk scores into five categories.
3. Calculated average risk scores for each LGA.
4. Calculated average risk scores for each State.
5. Classified the LGA and State average scores using the same five risk categories.
6. Created ward, LGA, and State level spatial visualisations.
7. Developed an interactive ArcGIS Dashboard.

## Risk Classification

- Very Low Risk - 1.0 – <1.8 
- Low Risk - 1.8 – <2.6 
- Moderate Risk - 2.6 – <3.4 
- High Risk - 3.4 – <4.2
- Very High Risk - 4.2 – 5.0

## Key Findings

### Ward Level

The analysis covers 9,410 wards.

- Very Low Risk - 4,795 (51.87% )
- Low Risk - 1,102 (11.92%)
- Moderate Risk - 1,692 (18.30%)
- High Risk - 1,124 (12.16%)
- Very High Risk - 532 (5.75%)
- No Data - 165 (1.75%)

Overall, 17.91% of wards with available risk scores are classified as High or Very High Risk.

### LGA Level

The analysis covers 774 LGAs.

- Very Low Risk - 356 (45.99%)
- Low Risk -150 (19.38%)
- Moderate Risk - 168 (21.71%)
- High Risk - 76 (9.82%)
- Very High Risk - 24 (3.10%)

Therefore, 12.92% of LGAs are classified as High or Very High Risk.

### State Level

The analysis covers 37 State-level administrative units, including the FCT.

- Very Low Risk - 15 (40.54%)
- Low Risk - 10 (27.03%)
- Moderate Risk - 10 (27.03%)
- High Risk - 2 (5.41%)

Bayelsa recorded the highest average State-level risk score at 4.17, followed by Zamfara at 3.5.

No State-level average score falls within the Very High Risk category.

## Ward-Level Map

![Nigeria Health Accessibility Risk - Ward Level](maps/nga_health_accessibility_ward_level.png)

## LGA-Level Map

![Nigeria Health Accessibility Risk - LGA Level](maps/nga_health_accessibility_lga_level.png)

## State-Level Map

![Nigeria Health Accessibility Risk - State Level](maps/nga_health_accessibility_state_level.png)

## Interactive Dashboard

The interactive ArcGIS Dashboard allows users to explore health accessibility risk across Ward, LGA, and State levels.

![Dashboard](dashboard/nga_health_accessibility_dashboard.png)

[Dashboard Link](https://www.arcgis.com/apps/dashboards/fe3796338e3d48b091afd7fb38d6c1a2#)

## Tools

- QGIS
- ArcGIS Online
- ArcGIS Dashboards

## Acknowledgement

Data used in this project were obtained from GRID3 (Geo-Referenced Infrastructure and Demographic Data for Development).

The analysis, spatial processing, classification, mapping and dashboard development were carried out using QGIS and ArcGIS.

## Author

[Saheedat Akanbi](https://github.com/Holuwarkemmy)
