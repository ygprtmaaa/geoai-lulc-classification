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

## Classification Output

### Random Forest Model

<p align="center">
  < <img width="1080" height="1080" alt="Desain tanpa judul (1)" src="https://github.com/user-attachments/assets/6dba54b9-e31d-47a5-97c9-de1312a9e6da" />
</p>

The Random Forest classifier produced the highest performance among all tested models. The classification utilized Sentinel-2 multispectral imagery and derived features including NDVI, NDWI, and BSI. The resulting map identifies major land cover classes such as settlements, rice fields, mixed farms, forests, fish ponds, and water bodies.

### Results

| Model | Overall Accuracy | Kappa |
|---------|---------|---------|
| Random Forest | 88.10% | 84.52% |
| XGBoost | 87.87% | 84.24% |
| CART | 82.84% | 77.72% |
| KNN | 78.03% | 71.28% |

Random Forest achieved the highest performance and produced the most reliable land cover classification results.


