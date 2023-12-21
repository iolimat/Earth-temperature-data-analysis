# Earth Temperature Data Analysis

This repository contains the code and documentation for a data analysis project based on the new high-resolution Berkeley Earth global temperature data set. The data set combines land-surface air temperatures with ocean sea surface water temperatures to provide a detailed summary of changes in Earth's global average surface temperature.

## Project Overview

### Dataset Description

The data set includes predictive structures based on historical weather patterns and has an increased resolution of 0.25° x 0.25° latitude-longitude. It merges land-surface air temperatures with ocean sea surface water temperatures, accounting for variations in sea ice coverage.

#### Data Sources

- GHCN-Monthly v4 ([Menne et al. 2018](https://doi.org/10.1175/JCLI-D-18-0094.1))
- Global Summary of the Day ([NOAA](https://www.ncei.noaa.gov/products/global-summary-day))
- MET-Reader ([Scientific Committee for Antarctic Research](https://legacy.bas.ac.uk/met/READER/))
- HADSST4 ([Kennedy et al. 2019](https://doi.org/10.1029/2018JD029867))
- HadISST2 ([Titcher and Rayner 2014](https://doi.org/10.1002/2013JD020316))
- Sea Ice Index ([NSIDC](https://nsidc.org/data/g02135/versions/3))
- ERA5 from the Copernicus Climate Change Service ([Hersbach et al. 2018](http://doi.org/10.24381/cds.adbb2d47))

## Results

The analysis provides insights into the global temperature anomalies for each month and includes moving averages centered around each month. Uncertainties are reported as 95% confidence intervals.

For more detailed information on the methodology, data sources, and analysis techniques, please refer to the documentation within the repository.

## Acknowledgments

- Berkeley Earth for providing the high-resolution global temperature data set.
- Contributors to the various datasets used in the analysis.

## [Dataset URL](https://www.kaggle.com/datasets/joebeachcapital/global-earth-temperatures)
