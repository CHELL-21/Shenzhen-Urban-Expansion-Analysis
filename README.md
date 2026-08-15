# Shenzhen-Urban-Expansion-Analysis
Landsat based analysis of urban expansion and built up area changes in Shenzhen, China using NDBI, Google Earth Engine and QGIS

## Overview

This project investigates the spatial and temporal distribution of built-up areas in Shenzhen, China using the Normalized Difference Built-up Index (NDBI) derived from Landsat satellite imagery.

The analysis uses Google Earth Engine for satellite image processing and QGIS for spatial analysis and cartographic visualization.

## Study Area

Shenzhen, Guangdong Province, China.

## Objectives

- Analyze the spatial distribution of built-up areas.
- Compare NDBI values across different years.
- Identify areas of increasing and decreasing built-up intensity.
- Examine the spatial pattern of urban expansion.

## Data

- Landsat satellite imagery
- Shenzhen study-area boundary
- NDBI-derived raster datasets

## Tools

- Google Earth Engine
- JavaScript
- QGIS
- Landsat
- Remote Sensing
- Raster Analysis
- Change Detection

## Methodology

Landsat imagery was filtered to the study area and selected time periods before calculating the Normalized Difference Built-up Index (NDBI).

The resulting NDBI layers were classified and compared between the selected years to identify spatial changes in built-up intensity.

### Workflow

Landsat Imagery  
↓  
Image Filtering & Preprocessing  
↓  
NDBI Calculation  
↓  
Classification  
↓  
Multi-Year Comparison  
↓  
Change Detection  
↓  
QGIS Cartographic Visualization

## Results

### 2015 True Color Composite

![2015 True Color Composite](maps/shenzhen_true_color_2015.png)

### 2015 NDBI

![2015 NDBI](maps/shenzhen_ndbi_2015.png)

### 2025 NDBI

![2025 NDBI](maps/shenzhen_ndbi_2025.png)

### NDBI Change Detection

![NDBI Change Detection](maps/shenzhen_ndbi_change_2015_2025.png)

## Key Findings

The NDBI analysis indicates changes in the spatial distribution and intensity of built-up areas across Shenzhen during the study period.

The results show areas of increased built-up intensity, particularly within developed portions of the city, while relatively lower built-up intensity remains in areas with less urban development and open or vegetated land.

## Limitations

NDBI represents the spectral characteristics associated with built-up surfaces and should not be interpreted directly as a measure of population, real-estate activity, or economic growth.

Additional demographic, land-use, and socioeconomic datasets would be required to investigate those relationships.

## Author

Mitchel Chidera

## Data Source

USGS Landsat Collection 2

## Processing

Google Earth Engine

## Cartography

QGIS
