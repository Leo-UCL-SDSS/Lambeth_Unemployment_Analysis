# Lambeth Unemployment Analysis

## Overview

This project analyses unemployment disparities across Lambeth using geospatial data and statistical methods. It explores how unemployment varies across neighbourhoods and its relationship with deprivation and education-related indicators.


## Key Findings

- Unemployment is spatially concentrated in specific neighbourhood clusters  
- Higher deprivation areas tend to exhibit higher unemployment rates  
- Spatial analysis reveals inequality that is not visible in borough-level averages  


## Methods

- Processed UK Census (2021) and IMD (2019) data  
- Performed spatial joins and OA → LSOA aggregation  
- Applied spatial statistics (Moran’s I, LISA)  
- Conducted regression analysis (GWR) to explore spatial relationships  
- Built reproducible workflows using R and R Markdown  


## Project Files

- `data_cleaning.R` — data loading and preprocessing  
- `analysis.R` — spatial analysis and modelling  
- `report.Rmd` — reproducible analysis report  
- `report.html` — rendered output  
- `report.pdf` — final report


## How to Run

1. Install required packages:

```r
install.packages(c(
  "sf", "spdep", "spgwr", "tmap",
  "dplyr", "ggplot2", "tidyverse"
))
```

2. Run data preparation:
source("data_cleaning.R")

3. Run analysis:
source("analysis.R")

4. Render report:
quarto render report.Rmd

5. Output
See:

* report.html for interactive version
* report.pdf for final report


For questions or feedback, please reach out:  
**Name:Leo Liao
**Email:** liaohaofan.gz@gmail.com
**GitHub:** https://github.com/Leo-UCL-SDSS

