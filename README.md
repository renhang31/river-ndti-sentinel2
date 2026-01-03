# river-ndti-sentinel2
# River Turbidity Estimation Using Sentinel-2 (NDTI)

This repository provides a reproducible framework for river turbidity
estimation using Sentinel-2 surface reflectance data and the
Normalized Difference Turbidity Index (NDTI).

## Features
- Sentinel-2 SR (Harmonized)
- Cloud Probability masking
- NDWI-based water extraction
- Monthly maximum NDTI composites
- Time-series analysis and export
- Google Earth Engine & Python (xarray/xee)

## Repository Structure
- `gee/` : Google Earth Engine (JavaScript) scripts  
- `python/` : Python & Google Colab workflows  
- `data/` : Example data structure (no large raw data)  
- `figures/` : Example outputs  

## NDTI Definition
\[
NDTI = (Red - Green) / (Red + Green)
\]

Sentinel-2 bands:
- Red: B4
- Green: B3

## Getting Started

### Google Earth Engine
1. Open GEE Code Editor  
2. Copy script from `gee/ndti_monthly.js`
3. Draw ROI and run

### Python / Colab
```bash
pip install geemap xee xarray
