# Data sources

## Nigeria Demographic and Health Surveys

Apply for the 2013, 2018 and 2024 Nigeria household recode files
and corresponding geographic datasets through
[The DHS Program](https://dhsprogram.com/data/).

## CHIRPS monthly rainfall

The analysis uses CHIRPS version 3.0 Africa monthly GeoTIFFs.

[CHIRPS monthly download directory](https://data.chc.ucsb.edu/products/CHIRPS/v3.0/monthly/africa/tifs/)

| Survey round | Required climate months |
|---|---|
| 2013 | November 2012–June 2013 |
| 2018 | May–November 2018 |
| 2024 | September 2023–April 2024 |

Files follow the naming pattern `chirps-v3.0.YYYY.MM.tif`.

The 2024 inputs include September, October and November 2023,
as well as December 2023–April 2024.

## ERA5-Land temperature

[Copernicus ERA5-Land monthly averaged data](https://cds.climate.copernicus.eu/datasets/reanalysis-era5-land-monthly-means)

Select monthly averaged reanalysis, 2 m temperature and NetCDF.
Use the climate months listed above.

The linkage notebooks check the time coordinates, units and
coverage of the supplied files. Follow each notebook's instructions
for grouping the downloads and naming the inputs.

## Exposure definition

For each household, the analysis uses the three complete calendar
months before the interview month. Rainfall is summed across those
months. Monthly temperature means are weighted by the number of days.

## File preparation

Retain the original input metadata and download selections in the
local analysis records. Follow the input prompts in each notebook.
