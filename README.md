# Catalogue

A structured sketch of what to include in a catalogue of machine-learning models and datasets.

If you have suggestions for changes, please make a GitHub pull request.

---

## Who to contact regarding this model/dataset
Email:

---

## ML Task

- **Semantic segmentation**
- **Object detection**
- **Object semantic segmentation**
- **Point-cloud classification**

---

## Model Architecture

Examples of architectures included in the catalogue:

- ResNet-50  
- SegFormer  
- U-Net  
- EfficientNet  
- Point Transformer  
- (Add more as needed)
- Ensemble of these models (e.g., U-Net with EfficientNetV2-M backbone)

---

## Input Data Format

- **uint8 GeoTIFF images** (N channels)  
- Additional geospatial or sensor data formats (optional)

---

## Output Data Format

- **uint8 GeoTIFF images**  
- Segmentation masks  
- Bounding boxes  
- Point-cloud labels  
- Class labels (buildings, asphalt, road markings, people, balconies, windows, water, roads, gravel)  
(Depending on task)

---

## Benchmark Results

Results on **KDS-Change Detection** dataset:  
- Pixel accuracy: **98%**  
- Change detection precision: **0.5**  
- Change detection recall: **0.6**

---

## Project Links

Include references to relevant resources:

- GitHub repository  
- Hugging Face model page  
- Company project homepage  
- Additional documentation  

---
