# FEMA National Risk Index Visualization

This repository contains my work for HW2 and HW3 in EDS 240. The assignments explore the FEMA National Risk Index (NRI) dataset and the U.S. Census demographic data to understand climate hazard risk patterns across California.


## Repository Purpose
This repo houses:

- **HW2**: Comparing California's climate hazard risk to other U.S. states using FEMA NRI composite scores
- **HW3**: Analyzing how climate hazard exposure varies across ethnic groups within California by joining NRI and American Community Survey (ACS) data


These projects demonstrates data cleaning, risk analysis comparison, wrangling, joining, creating effective, accessible data visualizations using R and ggplot


## Repository Structure
```
├── data/
│   ├── National_Risk_Index_Counties.csv
│   └── ACS-1yr-2023-county-race-ethnicity.csv
├── hw2.qmd
├── hw2.pdf
├── hw3.qmd
├── hw3.pdf
└── README.md
```

## Data Access

The first dataset is the National Risk Index (NRI) Counties dataset from FEMA (2025).
- Accessed 1/25/2025
- It is not housed in this repo but can be access here: https://hazards.fema.gov/nri

The second dataset is this U.S. Census American Community Survey (ACS) 1-year estimates (2023): County-level race and ethnicity population data for California
- Accessed 2/9/2026
- It is not housed in this repo but can be access via api here: https://www.census.gov/programs-surveys/acs/about.html

### HW2: State-Level Risk Comparison
A boxplot showing the distribution of FEMA National Risk Index composite scores across U.S. states, with California highlighted to show its elevated risk profile.

### HW3: Ethnic Climate Exposure
A lollipop chart showing the percentage of each ethnic group living in high-risk counties in California, revealing around 20 point difference in climate hazard exposure compared to other groups.



## Authors
- Joshua Ferrer-Lozano

## References & Acknowledgements

- FEMA National Risk Index (2025): https://hazards.fema.gov/nri
- U.S. Census Bureau American Community Survey: https://www.census.gov/programs-surveys/acs
- MEDS Data Visualization course materials (EDS 240)
- tidyverse, ggridges, and janitor R packages