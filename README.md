# Air Quality Analysis During COVID-19 Lockdowns

This repository contains the code and analysis for reproducing the graphs from the article "COVID-19 lockdowns cause global air pollution declines" published in the Proceedings of the National Academy of Sciences (PNAS). In attempting to reproduce the original findings using data released by the authors, two potential errors in the authors’ original analysis were found. These discrepencies were resolved through collaboration with the authors. This process changed the magnitude of the paper’s findings, but not the overall conclusions. The authors have since updated the paper and issued a correction detailing the changes.

## Overview

The COVID-19 pandemic led to unprecedented reductions in economic and transportation activities worldwide. This project aims to replicate the analysis from the mentioned article, which quantifies the impact of these lockdowns on global air pollution levels. The primary focus is on the changes in nitrogen dioxide (NO₂), particulate matter (PM₂.₅), and ozone (O₃) concentrations. 

## Data Sources

The analysis leverages satellite data and ground-level measurements from over 10,000 air quality stations across 34 countries. Key data sources include:

- Satellite observations of atmospheric pollutants
- Ground-level air quality measurements
- Meteorological data for adjusting pollution levels

## Files in This Repository

- `air_quality_Krigsman.Rmd`: The R Markdown file containing the code to replicate the analysis and produce the graphs as presented in the PNAS article.
- `COVID-19 lockdowns cause global air pollution declines _ PNAS.pdf`: The original article that forms the basis of this analysis.

## Analysis

The analysis involves the following steps:

1. **Data Preprocessing**: Preparing and cleaning the air quality and meteorological data.
2. **Statistical Modeling**: Adjusting pollutant levels for meteorological variations using regression models.
3. **Visualization**: Reproducing key graphs from the PNAS article to illustrate the impact of COVID-19 lockdowns on air pollution.

### Key Findings

- Significant reductions in ground-level NO₂ (60%) and PM₂.₅ (31%) were observed during lockdowns.
- Ozone levels showed mixed results, with some increases noted.
- Reductions in transportation emissions were a major contributor to the decline in NO₂ levels.

## References

- Venter, Z. S., Aunan, K., Chowdhury, S., & Lelieveld, J. (2020). COVID-19 lockdowns cause global air pollution declines. *Proceedings of the National Academy of Sciences*, 117(32), 18984-18990. [DOI:10.1073/pnas.2006853117](https://doi.org/10.1073/pnas.2006853117)
