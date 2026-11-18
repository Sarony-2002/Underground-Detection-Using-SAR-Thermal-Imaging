# Underground Detection Using SAR & Thermal Imaging

This repository features our team’s final course project for **ARTI 404** at the College of Computer Science and Information Technology, Imam Abdulrahman Bin Faisal University[cite: 60]. 

## Overview
This project delivers an end-to-end remote sensing pipeline designed to detect underground pipeline leaks and industrial pollution by fusing Sentinel-1 Synthetic Aperture Radar (SAR) and Landsat 8 thermal imagery[cite: 61]. The workflow emphasizes data preprocessing, Gaussian smoothing, Sobel edge detection, thermal thresholding, and rigorous cross-validation against historical industrial incidents in Deer Park, Texas (2014–2024)[cite: 61, 65, 82].

## Tech Stack
- **Language:** Python, Google Earth Engine (GEE) API[cite: 71, 82]
- **Data Processing & Analysis:** NumPy, Pandas, GDAL[cite: 72]
- **Image Processing & Computer Vision:** Gaussian filtering, Sobel edge operator, Otsu thresholding, cluster filtering[cite: 72, 73]
- **Satellite Data Sources:** Sentinel-1 GRD (SAR VV polarization), Landsat 8 TOA (Thermal Infrared Bands 10 & 11)[cite: 65, 66, 82]
- **Visualization:** Matplotlib, GeoTIFF map exports[cite: 82]
