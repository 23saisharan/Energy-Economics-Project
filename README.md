# Fuel Poverty in England (2024) - Data Analytics/ Econometrics Study

# Fuel Poverty in England: A Regional Econometric Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Status](https://img.shields.io/badge/status-complete-green)

> Which parts of England are most affected by fuel poverty, and what drives it? An analysis of 233 local authorities using Python, pandas and OLS regression.

![Fuel poverty by region](figures/regional_fuel_poverty.png)

## Key Findings
- **Regional hotspot:** West Midlands has the highest household-weighted rate (11.92%), followed by Yorkshire and the Humber.
- **Local hotspot:** Birmingham has the highest local authority rate (13.78%).
- **Drivers:** Lower median household income and less energy-efficient housing are both statistically associated with higher fuel poverty (see regression table).
- **Spread:** Local authority rates average 9.74% (range 5.56%–17.33%, SD 1.73).

## Data
- Source: [name + link], year [YYYY]
- Coverage: 233 local authorities, [variables used]

## Method
1. Cleaned the data: fixed header rows, renamed columns, removed the national total row.
2. Descriptive statistics for local authorities.
3. Aggregated by region, comparing simple averages with household-weighted rates.
4. Ranked local authorities by fuel poverty rate.
5. OLS regression: fuel poverty % ~ [income] + [EPC/housing variable] + [controls].

## Regression Results
| Variable | Coefficient | p-value |
|---|---|---|
| Median income | [ ] | [ ] |
| Energy-inefficient housing | [ ] | [ ] |

R² = [ ]. Limitations: [cross-sectional, ecological fallacy, omitted variables].

## Policy Recommendations
1. Target home-heating upgrade funding at high-density urban areas in the West Midlands and North West.
2. Focus council grants on raising the minimum EPC rating above D.
3. Publish regional tracking dashboards (e.g. Power BI) from this dataset.

## How to Run
pip install -r requirements.txt
jupyter notebook notebooks/01_fuel_poverty_analysis.ipynb

## Repo Structure
data/ · notebooks/ · figures/ · reports/ · requirements.txt
