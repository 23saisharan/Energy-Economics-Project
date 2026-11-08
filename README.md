# Fuel Poverty in England: A Regional Econometric Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![pandas](https://img.shields.io/badge/pandas-data%20analysis-150458)
![statsmodels](https://img.shields.io/badge/statsmodels-OLS-orange)
![SQL](https://img.shields.io/badge/SQL-queries-lightgrey)
![Status](https://img.shields.io/badge/status-complete-brightgreen)

> **Research question:** Which parts of England are most affected by fuel poverty, and what drives the differences between areas?

This project analyses fuel poverty across **233 local authority districts in England** using Python, SQL and OLS regression. It identifies regional and local hotspots, tests the role of income and housing efficiency, and turns the results into policy recommendations.

![Fuel poverty by region](figures/regional_fuel_poverty.png)

---

## Table of Contents
- [Key Findings](#key-findings)
- [Data](#data)
- [Methodology](#methodology)
- [Results](#results)
- [Policy Recommendations](#policy-recommendations)
- [Limitations](#limitations)
- [How to Run](#how-to-run)
- [Repository Structure](#repository-structure)

---

## Key Findings

| Finding | Result |
|---|---|
| Highest-rate region | West Midlands (11.92%, household-weighted) |
| Second-highest region | Yorkshire and the Humber |
| Highest-rate local authority | Birmingham (13.78%) |
| Mean local authority rate | 9.74% (SD 1.73) |
| Range | 5.56% to 17.33% |
| Drivers | Lower median income and less energy-efficient housing are both statistically associated with higher fuel poverty |

---

## Data

- **Source:** [Dataset name, publisher and link]
- **Year:** [Data year]
- **Coverage:** 233 local authority districts in England
- **Key variables:** `Local_Authority_Code`, `Fuel_Poverty_Percentage`, `Number_of_Households`, [income variable], [EPC/housing variable]

---

## Methodology

1. **Setup:** Imported pandas, numpy, matplotlib, seaborn, statsmodels and plotly.
2. **Import and cleaning:** Loaded the Excel sheets and checked their shape. Promoted the true header row, renamed columns and dropped the national total row.
3. **Descriptive statistics:** Summarised the local authority distribution.
4. **Regional aggregation:** Compared the simple average of local authority rates with the household-weighted regional rate.
5. **Ranking:** Listed the local authorities with the highest rates.
6. **SQL analysis:** [One line on the queries run and why.]
7. **Regression:** OLS of fuel poverty percentage on [income] and [housing efficiency], with [controls].
8. **Visualisation:** Histogram, regional chart and [interactive map or Plotly chart].

---

## Results

### Distribution of Fuel Poverty

![Distribution of fuel poverty percentage](figures/fuel_poverty_distribution.png)

Rates are roughly bell-shaped around 10%, with a right-hand tail of high-burden areas. One local authority sits near 17%, well above the rest.

### Regional Comparison

![Regional fuel poverty](figures/regional_fuel_poverty.png)

[One or two sentences on the regional pattern, including why simple and household-weighted averages differ.]

### Regression Results

| Variable | Coefficient | Std. Error | p-value |
|---|---|---|---|
| Median household income | [ ] | [ ] | [ ] |
| Energy-inefficient housing | [ ] | [ ] | [ ] |
| Constant | [ ] | [ ] | [ ] |

**R²:** [ ]  |  **Observations:** 233

[One sentence interpreting the coefficients, e.g. "A £1,000 rise in median income is associated with a X percentage point fall in fuel poverty."]

---

## Policy Recommendations

1. **Targeted funding:** Direct national home-heating upgrade funding to high-density urban clusters in the West Midlands and North West.
2. **Energy efficiency:** Focus council grants on raising older housing stock above EPC band D.
3. **Monitoring:** Build a regional tracking dashboard (for example in Power BI) from this dataset to support local teams.

---

## Limitations

- Cross-sectional data shows association, not causation.
- Area-level results may not hold for individual households (ecological fallacy).
- Omitted variables, such as fuel prices and housing tenure, may affect the estimates.
- [Any data-quality caveats.]


---

## Author

**Saisharan Ravichandran** · BSc Economics, University of Bath  
[LinkedIn](www.linkedin.com/in/saisharan-ravichandran) · [GitHub](https://github.com/23saisharan)

