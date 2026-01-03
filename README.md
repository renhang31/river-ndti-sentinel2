
# River Turbidity Estimation Using Sentinel-2 (NDTI)

This repository provides a reproducible framework for river turbidity
estimation using Sentinel-2 surface reflectance data and the
Normalized Difference Turbidity Index (NDTI).
<img width="1707" height="590" alt="微信图片_20260102224231_317_47" src="https://github.com/user-attachments/assets/49b50147-7202-45fa-bd79-e30c67d58ac5" />
<img width="1180" height="736" alt="微信图片_20260102224234_318_47" src="https://github.com/user-attachments/assets/865409f9-08e6-4f59-9520-0d17556e9bc7" />
<img width="1021" height="547" alt="微信图片_20260102224237_319_47" src="https://github.com/user-attachments/assets/ccf465d6-1bd8-4314-8612-f3d6677ecb41" /># river-ndti-sentinel2
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
GEE：https://code.earthengine.google.com/1af52358e2df8a6d30f8099d0826579a
Python / Colab：https://colab.research.google.com/drive/1Sx8RD8GMEg28Tl2cyGc9nbo8AwjKqFPs?usp=sharing
