A GeoAI framework for Land Use Land Cover classification using Sentinel-2 data, feature engineering, and machine learning models including Random Forest, XGBoost, CART, and KNN.

## Project Overview

This project develops a GeoAI-based Land Use Land Cover (LULC) classification workflow using Sentinel-2 satellite imagery and machine learning techniques. The workflow integrates remote sensing, feature engineering, and spatial analytics to generate accurate land cover maps for environmental monitoring and spatial planning.

The classification process utilizes spectral bands and vegetation indices derived from Sentinel-2 imagery, including NDVI, NDWI, and BSI. Several machine learning algorithms are evaluated and compared, including Random Forest, XGBoost, CART, and K-Nearest Neighbor (KNN).

### Objectives

- Classify land cover using Sentinel-2 imagery
- Compare machine learning model performance
- Evaluate classification accuracy using confusion matrix and kappa statistics
- Support spatial planning and environmental management

### Technologies

- Google Earth Engine
- Python
- ArcGIS Pro
- QGIS
- GeoAI
- Machine Learning

### Classification Classes

- Forest
- Settlement
- Rice Field
- Fish Pond
- Mixed Farm
- Water Body

### Results

| Model | Overall Accuracy | Kappa |
|---------|---------|---------|
| Random Forest | 88.10% | 84.52% |
| XGBoost | 87.87% | 84.24% |
| CART | 82.84% | 77.72% |
| KNN | 78.03% | 71.28% |

Random Forest achieved the highest performance and produced the most reliable land cover classification results.
<img width="2556" height="3408" alt="20260510_150456" src="https://github.com/user-attachments/assets/7b3ee755-988c-4d5a-a042-fb948a47f8c9" />

