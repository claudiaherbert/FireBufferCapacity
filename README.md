# Fire Buffer Capacity

This repository accompanies our "Golf courses reduce fire severity and limit fire spread in California" paper. 

The scripts in this repository allow you to generate our source datasets and run analysis for measuring changes in fire severity (part 1) and measure potential for limiting fire spread (part 2). 

## In this repository
To generate the source data and run the analysis, we used Google Earth Engine (JavaScript), Jupyter Notebooks (Python), and R studio (R). We also did work in ArcGIS Pro to set up the intersection between landscape features and fire perimeter for Part 2 of the analysis. This repository contains the underlying datasets and scripts to recreate our analysis. 

### Analysis 1: How does a landscape feature change fire severity, relative to similar landscapes? 
We have done our best to document this pre-analysis data organizing workflow in the first folder of this repository, "0_DataPrep_FireSev".

The propensity score matching and regression analysis, along with the accompanying figures, are available in the folder titled, "1_Analysis_FireSev". 

### Analysis 2: How does a landscape feature limit fire spread?
The limit fire spread analysis uses analysis primarily in R. We have included the script and datasets to reproduce our figures in the folder titled, "2_Analysis_LimitFire". 

Because some of this data prep work occurred outside of R and the datasets, we generated were based on queries from OpenStreetMap Turbo API, we have included the instructions for these queries for those interested in reproducing our underlying datasets or for investigating different landscape features. 

## Additional Datasets
This work also relied on queries from OpenSteetMap Turbo API, downloaded fire perimeters from CalFire, and downloaded raster stack from MTBS. Due to storage limits in this GitHub, we have not included some of these datasets, but have shared the data via Google Earth Engine that is needed for Analysis 1. If there is an issue accessing one of these datasets, please contact the corresponding author to update sharing privileges on GEE.
