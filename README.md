# Geospatial Data Analysis Using Machine Learning

## Overview

This repository contains code for analyzing Earth Observation data using various machine learning techniques. It contains code for the creation of a Land Use Land Cover (LULC) model. Also two applied cases for an integrated assessment using the LULC model for change detection  and Normalised Vegetation Index (NDVI) calculation for vegetation health assessment. 

## Files in the Repository

- **LULC_model_development**: Contains the code for the development of 12 Land Use and Land Cover (LULC) models, along with their performance metrics and visualization maps of the test data.
- **Assessment_Glasgow**: Contains the integrated LULC and NDVI assessment for the city of Glasgow.
- **Assessment_Newton_Mearns**: Contains the integrated LULC and NDVI assessment for the suburban town of Newton Mearns.

**Note**: The code has been pre-ran, so all the necessary outputs have been generated. However, the LULC classification and NDVI visualization maps may not be visible directly in the notebook because these visualizations require the Google Earth Engine (GEE) API. To properly view these maps, it is recommended to run the code again with access to the GEE API.

## How to Run the Code

To run the code and view the LULC classification and NDVI maps:

1. Open the notebook in Google Colab.
2. Press the `Run All` button to execute all cells.
3. When prompted, grant all necessary permissions, including access to your Google account, to connect to the Google Earth Engine API.
