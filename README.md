# GPD-Influence-on-Coastline-Protection
### Author: Sofia Rodas

## Purpose
This repository investigates the hypothesis that nations with higher per capita GDP are more likely to protect their coastlines. 

## Data

**Coastal Protection Data:** The original data comes from the [Ocean+Habitats](https://habitats.oceanplus.org/) webpage which works to inform policy about the state of our oceans coastline focusing on metrics concerning ocean protection. This analysis focuses on the five ecosystems for which data is available. The five ecosystems are cold-water corals, mangroves, seagrasses, saltmarshes, and warm-water corals.

**GDP Data:** Per capita GDP data was acquired from the [International Monetary Fund](https://www.imf.org/external/datamapper/NGDPDPC@WEO/OEMDC/ADVEC/WEOWORLD).

## File structure:

.
├── beta-regression.qmd
├── data
│   ├── imf-dm-export-20251011.csv
│   ├── imf-dm-export-20251011.xls
│   └── Ocean+HabitatsDownload_Global
│       ├── coastline_coverage.csv
│       ├── coldwatercorals.csv
│       ├── global-stats.xlsx
│       ├── mangroves.csv
│       ├── saltmarshes.csv
│       ├── seagrasses.csv
│       └── warmwatercorals.csv
├── data-cleaning.qmd
├── gdp_coastal_ecosystem.csv
├── gdp-influence-on-coastline-protection.Rproj
├── practice
│  
└── README.md

Note: The original downloaded data is not in this git repository. It can be downloaded from its original sources.

## Repository Contents:
-**Beta Regression Quarto:** [beta-regression.qmd](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/beta-regression.qmd)

-**Data Cleaning Quarto:** [data-cleaning.qmd](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/data-cleaning.qmd)

-**Clean data:** [gdp_coastal_ecosystem.csv](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/gdp_coastal_ecosystem.csv)

## References 

IMF. 2023. World Economic Outlook, October 2023. Washington, DC: International Monetary Fund. ©IMF. https://doi.org/10.5089/9798400235801.081

UNEP-WCMC (2025). Ocean+ Habitats [On-line], [Downloaded: October 2025]. Available at: [habitats.oceanplus.org](habitats.oceanplus.org)

