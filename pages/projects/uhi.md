# Urban Heat Island Analysis

## Overview

This project analyzes the Urban Heat Island (UHI) effect by identifying temperature variations across urban environments using satellite imagery and machine learning.

## Problem Statement

Rapid urbanization increases surface temperatures due to reduced vegetation and increased built-up surfaces. This creates heat stress, energy inefficiency, and health risks.

## Objectives

* Derive Land Surface Temperature (LST)
* Predict heat hotspots using ML
* Support climate resilience planning

## Data Sources

* Landsat Satellite Imagery
* ESA WorldCover
* Google Earth Engine
* Environmental variables

## Methodology

### Data Processing

* Cloud masking
* Raster preprocessing
* Feature extraction

### Feature Engineering

Derived:

* NDVI
* Fractional Vegetation
* Emissivity
* Land Surface Temperature

### Machine Learning

Models used:

* Random Forest 

## Results

The model successfully identified heat hotspots concentrated in densely built urban regions with limited vegetation cover.

## Impact

This project demonstrates how AI and geospatial analytics can support urban planning and climate adaptation.

## Tools Used

* Python
* Google Earth Engine
* GIS
* Scikit-learn
