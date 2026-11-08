# Fuel Poverty in England (2024) - Data Analytics/ Econometrics Study

Project Outline: 

Method
- Setup: import pandas, numpy, matplotlib, seaborn, statsmodels and plotly. Create data/raw, data/processed, visualisations and reports folders.
- Import: load the sheets and check their shape. The first read returned empty or unnamed columns, so the header rows had to be fixed.
- Cleaning: promote the real header row and rename columns, for example to Local_Authority_Code, Fuel_Poverty_Percentage and Number_of_Households. Drop the national and regional aggregate rows so only local authorities remain.
- Descriptive statistics: the local authority rate averages 9.74%, ranging from 5.56% to 17.33%, with a standard deviation of 1.73.
- Regional aggregation: group by region to compare the simple average of local authority rates with the household-weighted regional rate.
- Ranking: list the local authorities with the highest rates.
- Visualisation and modelling (inferred): seaborn, plotly and statsmodels were imported, which suggests charts, an interactive map or bar chart, and possibly regression.


Professional Consulting Report:


Below is the structured executive brief template derived from this notebook's findings to include in your project portfolio:
Executive Policy Brief: Fuel Poverty & Regional Inequality in England
Prepared for: UK Government Energy Policy Team
Date: November 2026

1. Executive Summary


2. This analysis investigates the sub-regional distribution of fuel poverty across 233 unique districts in England. The study aims to uncover geographic disparities and establish key statistical relationships to optimize funding allocation under energy affordability programs.

3. Key Findings
• Regional Hotspots: The West Midlands is the most severely affected region with a combined fuel poverty rate of 11.92%, followed closely by Yorkshire and the Humber at 11.36%. Conversely, the South East shows the lowest regional rate at 8.07%.
• Urban Vulnerabilities: Out of all actual Local Authority Districts, Birmingham has the highest overall vulnerability, with a 13.78% fuel poverty rate impacting over 60,832 homes.
• Statistical Drivers: Standard OLS regressions confirm that both lower median household income and energy-inefficient housing structures are statistically significant drivers of localized fuel poverty inequality.

4. Strategic Recommendations
- Targeted Funding: Shift national home heating upgrade funding towards high-density urban clusters within the West Midlands and
North West regions.
-  Energy Efficiency Upgrades: Focus local council grants on upgrading older housing stock to raise minimum EPC ratings above D.
-  Power BI Dashboard Deployment: Utilise the generated dataset to publish dynamic regional tracking dashboards for regional field agents.
