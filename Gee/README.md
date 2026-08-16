## Shenzhen NDBI Urban Development Analysis
Overview

This Google Earth Engine (GEE) workflow uses Landsat satellite imagery and the Normalized Difference Built-up Index (NDBI) to assess urban development and changes in built-up areas across Shenzhen, China.

The analysis goes beyond visualizing NDBI by quantifying changes in built-up areas and identifying spatial hotspots of urban development.

## Objectives
Calculate NDBI from Landsat satellite imagery.
Map the spatial distribution of built-up areas.
Compare built-up conditions between different years.
Quantify the area of built-up development and change.
Identify locations experiencing concentrated urban development.
Analyze the spatial pattern of urban expansion.
Data

Satellite: Landsat

Index: Normalized Difference Built-up Index (NDBI)

Study Area: Shenzhen, Guangdong Province, China

Platform: Google Earth Engine

## Methodology

The workflow follows these major steps:

Define the Shenzhen study area.
Load and filter Landsat imagery.
Apply appropriate image preprocessing.
Calculate NDBI using the appropriate Landsat spectral bands.
Classify built-up areas based on NDBI values.
Compare NDBI-derived built-up areas across selected years.
Calculate the spatial extent of built-up areas.
Quantify areas that experienced changes in built-up conditions.
Identify spatial concentrations or hotspots of development.
Export the resulting datasets for further analysis and visualization in QGIS.
Key Outputs

The script produces quantitative and spatial outputs including:

Total developed/built-up area.
Area of newly developed land.
Magnitude of built-up area change.
Spatial distribution of development.
Development hotspots.
Year-to-year NDBI comparisons.
Maps suitable for further cartographic analysis in QGIS.
## Interpretation

Areas showing strong positive changes in NDBI may indicate increasing built-up intensity or conversion toward developed surfaces.

Concentrated areas of positive change can therefore be interpreted as urban development hotspots.

However, NDBI alone does not directly measure population growth or migration. Population or migration patterns would require additional demographic datasets to establish those relationships.

## Applications

This workflow can support:

Urban expansion monitoring
Land-use change analysis
Remote sensing
GIS-based urban planning
Environmental change assessment
Infrastructure development assessment
Geospatial analysis of rapidly developing areas
Tools
Google Earth Engine
JavaScript
Landsat
Remote Sensing
NDBI
GIS
QGIS
Repository Contents
gee/
shenzhen_ndbi.js

The JavaScript file contains the complete Google Earth Engine workflow used for the analysis.

## Limitations

NDBI is sensitive to built-up surfaces but may also respond to bare soil and other surfaces with similar spectral characteristics. Consequently, NDBI-derived development estimates should be interpreted alongside other land-cover or demographic datasets where available.

Built-up change should not be interpreted as direct evidence of population migration without independent population or migration data.

## Author

Mitchel Chidera

## Data Source

USGS Landsat Collection 2

Processing Platform

Google Earth Engine

Cartographic Visualization

QGIS
