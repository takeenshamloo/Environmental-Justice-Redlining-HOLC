# Environmental Justice Analysis of HOLC Redlining in Los Angeles

## Overview
This repository contains analyses for exploring the legacy of redlining in 
Los Angeles, focusing on its impacts on present day environmental justice and 
biodiversity observations. The project leverages spatial and environmental data 
to examine the relationships between historical HOLC grading and 
modern environmental/biodiversity indicators. This analysis contributes to 
understanding how historical systemic discrimination continues to shape 
ecological and societal outcomes today.

### Repository Purpose
This repository highlights my ability to:
- Create aesthetically pleasing and accessible maps.
- Manipulate vector and raster data for multi-layered spatial analyses.
- Conduct reproducible environmental justice analyses using R and Quarto.

---

## Contents
The repository is organized as follows:

Environmental-Justice-Redlining-HOLC/
│   README.md         # This file
│   Environmental_Justice.qmd           # Quarto document for the analysis
│   Environmental_Justice.html          # Rendered Quarto output

The `data/` folder is not included in this repository but contained:
- `ejscreen/` (Environmental Justice Screening data from the US EPA)
- `gbif-birds-LA/` (Biodiversity data from GBIF)
- `mapping-inequality/` (HOLC grading data from the Mapping Inequality project)

To access these data sources, refer to the "Data Sources" section below.

---

## Data Sources
### 1. EJScreen
- **File**: `ejscreen/EJSCREEN_2023_BG_StatePct_with_AS_CNMI_GU_VI.gdb`
- **Source**: Environmental Justice Screening and Mapping Tool by the US EPA
- **Description**: Provides environmental and demographic data at the Census block group level.
- **Details**: See `ejscreen-tech-doc-version-2-2.pdf` and `EJSCREEN_2023_BG_Columns.xlsx` for technical documentation and column descriptions.

### 2. HOLC Redlining
- **File**: `mapping-inequality/mapping-inequality-los-angeles.json`
- **Source**: Mapping Inequality Project by the Digital Scholarship Lab, University of Richmond
- **Description**: Digitized HOLC maps of Los Angeles, including historical grade designations (A, B, C, D).

### 3. Biodiversity Observations
- **File**: `gbif-birds-LA.shp`
- **Source**: Global Biodiversity Information Facility (GBIF)
- **Description**: Bird observations in Los Angeles from 2021 onward.

---

## Analysis Highlights
### Part 1: Environmental Justice
- A map of Los Angeles neighborhoods color-coded by HOLC grade.
- Summaries of current environmental indicators from EJScreen data within HOLC-graded areas:
  - Percent low-income populations.
  - PM2.5 percentiles.
  - Percentiles for low life expectancy.
- A brief reflection on the relationship between historical redlining and environmental justice.

### Part 2: Biodiversity Observations
- A figure summarizing bird observation percentages within redlined neighborhoods (2022).
- Reflection on how these results compare with findings from Ellis-Soto et al. (2023).

---

## Skills Demonstrated
This project showcases the following skills:
- Spatial data manipulation and analysis using R.
- Creation of professional, accessible, and aesthetically pleasing maps using `tmap`.
- Integration of multiple data sources with different coordinate reference systems.
- Reproducible workflows using Quarto.
- Application of environmental justice concepts to spatial data science.

---

## Author
- **Takeen Shamloo** – Developer and analyst for this repository.

---

## References
1. Gee, G. C. (2008). A multilevel analysis of the relationship between institutional and individual racial discrimination and health status. *American Journal of Public Health, 98*(Supplement_1), S48-S56.
2. Nardone, A., Rudolph, K. E., Morello-Frosch, R., & Casey, J. A. (2021). Redlines and greenspace: the relationship between historical redlining and 2010 greenspace across the United States. *Environmental Health Perspectives, 129*(1), 017006.
3. Hoffman, J. S., Shandas, V., & Pendleton, N. (2020). The effects of historical housing policies on resident exposure to intra-urban heat: a study of 108 US urban areas. *Climate, 8*(1), 12.
4. Ellis-Soto, D., Chapman, M., & Locke, D. H. (2023). Historical redlining is associated with increasing geographical disparities in bird biodiversity sampling in the United States. *Nature Human Behaviour*, 1-9.
5. Nelson, R. K., et al. (2023). *Mapping Inequality*. American Panorama.

---

## Acknowledgements
This project was originally developed as part of the Master of Environmental Data Science (MEDS) program at UC Santa Barbara. Data sources and methodologies were informed by the course curriculum and supported by the referenced literature.
