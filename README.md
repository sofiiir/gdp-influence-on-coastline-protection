# Per Capita GDP Influence on the Protection of Coastal Ecosystems
### Author: Sofia Rodas

<img width="897" height="452" alt="DAG" src="https://github.com/user-attachments/assets/1b8caa4a-9bfc-4a2b-bc74-f3e66dd91f3a" />


## Purpose
This repository investigates the hypothesis that nations with higher per capita GDP are more likely to protect their coastlines. 

## Data

**Coastal Protection Data:** The original data comes from the [Ocean+Habitats](https://habitats.oceanplus.org/) webpage which works to inform policy about the state of our oceans coastline focusing on metrics concerning ocean protection. This analysis focuses on the five ecosystems for which data is available. The five ecosystems are cold-water corals, mangroves, seagrasses, saltmarshes, and warm-water corals.

**GDP Data:** Per capita GDP data was acquired from the [International Monetary Fund](https://www.imf.org/external/datamapper/NGDPDPC@WEO/OEMDC/ADVEC/WEOWORLD).

## File structure:

<img width="348" height="240" alt="Screenshot 2025-12-05 at 12 14 32 AM" src="https://github.com/user-attachments/assets/29f86cf6-a248-4088-b1be-9da08539d553" />

Note: The original downloaded data is not in this git repository. It can be downloaded from its original sources.

## Repository Contents:
-**Beta Regression Quarto:** [beta-regression.qmd](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/beta-regression.qmd)

-**Data Cleaning Quarto:** [data-cleaning.qmd](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/data-cleaning.qmd)

-**Clean data:** [gdp_coastal_ecosystem.csv](https://github.com/sofiiir/gdp-influence-on-coastline-protection/blob/main/gdp_coastal_ecosystem.csv)

## References 

Brooks, M., Kristensen K., Maechler M., Magnusson A., McGillycuddy M., Skaug H., Nielsen A., Berg C., van Bentham K., Sadat N., Lüdecke D., Lenth R., O'Brien J., Geyer C.J., Jagan M., Wiernik B., Stouffer D.B., Agronah M., Akdur H.T.K., Bové D.S., and Krieger N. Package ‘glmmTMB’ (CRAN). (Oct. 9, 2025). Available at: [https://cran.r-project.org/web/packages/glmmTMB/glmmTMB.pdf](https://cran.r-project.org/web/packages/glmmTMB/glmmTMB.pdf)

Czapanskiy, M. and Grimes N. EDS 222: Statistics for Environmental Data Science. Available at: [https://eds-222-stats-f25.github.io/](https://eds-222-stats-f25.github.io/)

IMF. (2023). World Economic Outlook, October 2023. Washington, DC: International Monetary Fund. ©IMF. Available at: https://doi.org/10.5089/9798400235801.081

UNEP-WCMC. (2025). Ocean+ Habitats [On-line], [Downloaded: October 2025]. Available at: [habitats.oceanplus.org](habitats.oceanplus.org)

