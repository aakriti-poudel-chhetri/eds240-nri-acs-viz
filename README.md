# Visualizing FEMA NRI x ACS Data

This repository contains the details of the Assignment 2 & 3 for the course EDS 240 - Data Visualization & Communication for the Master of Environmental Data Science (MEDS) program.

## Background

**Federal Emergency Management Agency (FEMA) National Risk Index**

The Federal Emergency Management Agency (FEMA) is a U.S. government agency whose mission is to help people prepare for, respond to, and recover from disasters. In 2021, FEMA launched the National Risk Index (NRI), a nationwide dataset designed to help communities understand and compare their risk from natural hazards.

The NRI provides risk information for 18 different natural hazards at the census tract and county levels. It offers a standardized baseline measure of risk by combining three core components: Expected Annual Loss, Social Vulnerability, and Community Resilience. Together, these components capture both the physical impacts of hazards and the social conditions that influence a community’s ability to prepare for and recover from disasters.

The NRI reports both hazard-specific risk scores and a composite risk score, which aggregates risk across all 18 hazard types. Each community’s score is expressed as a percentile ranking relative to other communities at the same geographic level. In addition, communities are assigned a qualitative risk rating ranging from very low to very high, to facilitate interpretation and comparison.

In December 2025, FEMA integrated the National Risk Index into the Resilience Analysis and Planning Tool (RAPT), expanding access to NRI data and supporting its use in resilience planning, policy analysis, and community-level decision-making.

![](image/fema-nri-cali.png)

**US Census Bureau's American Community Survey (ACS)**

The American Community Survey (ACS) is a nationwide, continuous survey conducted by the U.S. Census Bureau to provide detailed demographic, social, economic, and housing data for communities across the United States. Unlike the Decennial Census, which counts every person once per decade for congressional apportionment, the ACS surveys approximately 3.5 million households annually to capture more current and detailed information about the American population.

The ACS releases data in two formats: 1-year estimates (covering areas with populations of 65,000 or more) and 5-year estimates (covering all geographic areas). The 1-year estimates provide the most current snapshot of demographic characteristics, while the 5-year estimates offer greater statistical reliability for smaller geographic areas and populations. This makes the ACS an essential tool for understanding how different communities experience social, economic, and environmental conditions.



## Objective

The objective of this assignment is to explore FEMA’s National Risk Index (NRI) data and identify visualization approaches that are most appropriate for both the data and intended audience. The assignment focuses on preparing and wrangling the data to ensure it is properly structured for visualization, and on building effective, responsible, accessible, and aesthetically pleasing visualizations using the R programming language with `{ggplot2}` and related extension packages.

## Repository Structure

```
eds240-nri-acs-viz
└─── .gitignore
      └─── data
            └─── ACS-1yr-2023-county-race-ethnicity.csv
            └─── National_Risk_Index_Counties_807384124455672111.csv
└─── README.md
└─── eds240-nri-acs-viz.Rproj
└─── HW2.pdf
└─── HW2.qmd
└─── HW3.pdf
└─── HW3.qmd
└─── image
     └─── fema-nri-cali.png
     └─── nri-acs-ethnicity.png
     
```

## Data

This assignment uses data from FEMA’s National Risk Index (NRI), an interactive dataset that provides risk information for 18 natural hazards across U.S. communities. The NRI includes county and census tracts level measures of expected annual loss, social vulnerability, community resilience, and overall Risk Index scores that describe relative natural hazard risk. (FEMA Hazards)

The full data set and interactive tools are available [here](https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/).

This assignment also uses data from the U.S. Census Bureau's American Community Survey (ACS), a nationwide, continuous survey designed to provide communities with reliable and timely social, economic, housing, and demographic data every year. The ACS collects detailed information from a small subset of the population (~3.5 million households) at 1- and 5-year intervals. For this analysis, we use the ACS 1-Year Estimates (2023) to obtain county-level race and ethnicity data for California. Learn more about the [differences between 1- and 5-year ACS estimates](https://www.census.gov/programs-surveys/acs/guidance/estimates.html).

## References
Federal Emergency Management Agency. (2021). *National Risk Index for natural hazards.* https://experience.arcgis.com/experience/0a317e8998534c30a9b2d3861c814d42/

U.S. Census Bureau. (2023). *American Community Survey 1-Year Estimates.* https://www.census.gov/programs-surveys/acs

### Course Information

- **Course Title:** [EDS 240 - Data Visualization & Communication](https://eds-240-data-viz.github.io/)
- **Term:** Winter 2026
- **Program:** [UCSB Masters in Environmental Data Science](https://bren.ucsb.edu/masters-programs/master-environmental-data-science).

Teaching Team:

- **Instructor:** [Sam Shanny-Csik](https://samanthacsik.github.io/)
- **Co-Instructor:** [Annie Adams](https://github.com/annieradams) 

Complete description for this assignment can be found on [Assignment 2](https://eds-240-data-viz.github.io/course-materials/assignments/HW2.html) & [Assignment 3](https://eds-240-data-viz.github.io/course-materials/assignments/HW3.html)
