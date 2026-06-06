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

## Model Comparison Results

<p align="center">
  <img width="1080" height="1080" alt="MODEL K-NEAREST NEIGHBOR (1)" src="https://github.com/user-attachments/assets/0286f3fa-9eca-40b7-b314-4b7651d08d24" />
</p>

**Figure 1.** Comparison of Land Use Land Cover (LULC) classification outputs generated using four machine learning algorithms: Random Forest, K-Nearest Neighbor, CART, and XGBoost.

The model comparison shows different spatial classification patterns across the study area. Random Forest achieved the best performance with an Overall Accuracy of **88.10%** and Kappa Accuracy of **84.52%**.

| Model | Overall Accuracy (%) | Kappa Accuracy (%) |
|---|---:|---:|
| Random Forest | 88.10 | 84.52 |
| XGBoost | 87.87 | 84.24 |
| CART | 82.84 | 77.72 |
| K-Nearest Neighbor | 78.03 | 71.28 |


