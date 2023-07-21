# Multiple-use protected areas: critical to equitable and effective conservation

This repository accompanies the peer-reviewed publication Adams et al. (2023) Multiple-use protected areas: critical to equitable and effective conservation published in One Earth.

The raw data to complete the analysis can be found at:

Once the raw data is saved within the directories raw_data folder, the three analysis can be completed by running the following scripts in the provided order.


## Hot moments


## Trends in human impact

### Marine impact trends

1. Download_stressor_impacts.Rmd

This script downloads the necessary abatable impact data from the KNB data repository

2. Abatable_cumulative_impact.Rmd

This script calculates the cumulative impact of abatable stressors each year from 2003-2013

3. Trend_within_PAs.Rmd

This script calculates the trend in marine human impact of abatable threats within all marine protected areas included in the an analysis.

4. Trend_within_PAs_IUCN

This script calculates the trend in marine human impact of abatable threats within marine protected areas by IUCN class (Strict, Not strict, Other) included in the an analysis.

### Terrestrial human impact trends

1. Trend_HFP.Rmd
2. Trend_within_PAs_IUCN_HFP.RmD
3. Trend_within_PAs_ISO3.Rmd

### Figures
5. CHI_timeseries_figures.Rmd
6. CHI_ISO3_figures.Rmd



## Climate velocity

1. clim_velocity.Rmd

This script downloads the necessary sea surface temperature data and calculates 1) climate velocity and 2) area protected within the global marine protected area estate

2. Marine_climate_velocity_bivariate_plot.R

This script recreates Figure 6 from the main text. Note that figure formatting was completed in powerpoint.

Figure 6. Climate velocity in marine protected areas. Size of MPA against speed of velocity is plotted for the centroid of all marine protected areas. Blue indicates larger area and slower velocity, red smaller area and faster velocity, purple indicates larger area and faster velocity, and mauve indicates smaller area and slower velocity.
