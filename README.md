# AgriSense-DIP-CCP
Overview

AgriSense is a Digital Image Processing and Remote Sensing project that leverages Sentinel-2 satellite imagery, machine learning, and deep learning techniques for agricultural monitoring in Punjab, Pakistan.

The project consists of six tasks covering:

Data acquisition and preprocessing
Image enhancement and restoration
Feature extraction and segmentation
Crop classification
Change detection
Sustainability and deployment analysis
**Study Area
**
Punjab, Pakistan

**Satellite Source:
**
Sentinel-2 Level-2A Imagery
Google Earth Engine
ESA Copernicus Program
**Project Objectives
**Monitor agricultural land cover
Classify crop types
Detect temporal land changes
Compare classical and deep learning approaches
Evaluate computational sustainability
Support precision agriculture applications
**Tasks
****Task 1: Data Acquisition and Preprocessing
**Sentinel-2 image acquisition
Atmospheric correction
Cloud masking
Band stacking
ROI extraction

**Outputs:
**
BOA composite imagery
Quality masks
Spectral indices


**Task 2: Image Enhancement
**
**Methods:
**
Histogram Equalization
CLAHE
Wavelet Denoising
Contrast Enhancement

**Evaluation:
**
PSNR
SSIM
Entropy

**Task 3: Segmentation
**
**Methods:
**
K-Means Clustering
Watershed Segmentation
Morphological Refinement

**Metrics:
**
IoU
Dice Score


**Task 4: Crop Classification
**
**Classical Machine Learning:
**
Random Forest
SVM (RBF)

**Deep Learning:
**
U-Net (ResNet34)
SegFormer-B2

**Metrics:
**
Overall Accuracy
Macro F1
Mean IoU
Dice Score
Carbon Footprint

**Key Result:
**
Random Forest achieved the highest classification accuracy.

**Task 5: Change Detection
**
**Methods:
**
NDVI Differencing
Log-Ratio
Change Vector Analysis (CVA)
Siamese CNN
Ensemble Fusion

**Metrics:
**
Kappa Coefficient
Overall Accuracy
Producer Accuracy
User Accuracy
False Alarm Rate
Missed Detection Rate

**Key Result:
**
CVA produced the most reliable change detection performance.

**Task 6: Sustainability and Deployment
**
**Analysis:
**
Carbon Footprint Assessment
Quantization
Edge Deployment
Resource Utilization

**Tools:
**
CodeCarbon
PyTorch Quantization
Technologies Used
Python
Google Earth Engine
PyTorch
Scikit-Learn
OpenCV
Rasterio
GeoPandas
SegFormer
U-Net
