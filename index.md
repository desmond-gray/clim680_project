# Precipitation Climatology of Virginia
 
### Desmond Gray
#### CLIM 680 - Fall 2022

## Introduction

My CLIM 680 project is comparing the difference between coarse GPCP precipitation data from stations and satellites with 
higher resolution ERA5 data that has been processed through a model. I will be comparing the grids to show how the points
differ when calculating climatology and anomalies.

## Data

The datasets used in my project are:

__GPCP Precipitation__
The [GPCP Precipitation](https://psl.noaa.gov/data/gridded/data.gpcp.html) is monthly global 
precipitation from Jan 1979 to Apr 2020. It is on a 2.5 deg longitude by 2.5 deg latitude gride.

__ERA5__
The [ERA5](https://www.ecmwf.int/en/forecasts/datasets/reanalysis-datasets/era5) provides hourly estimates of a large number 
of atmospheric, land, and oceanic climate variables from Jan 1959 to present.  It is on a 30km grid.

## Proposed Analysis
I plan to use the data sets above to conduct the following analysis:
* Calculate mean, climatology and anomalies of precipitation
* Compare geographical differences and how extremes differ between datasets

### Functions
I will create a set of functions for doing common tasks used throughout my analysis, including:
* Labelling plots
* calculating climatology and anomalies