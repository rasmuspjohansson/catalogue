# Catalogue

A structured sketch of what to include in a catalogue of machine-learning models and datasets.

If you have suggestions to changes , please make a git hub pull request

---
## wo to contact reagrding this model/dataset
  email 

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
- enamble of these models [unet with efficientnetv2-M backbone]

---

## Input Data format

- **uint8 GeoTIFF images** (N channels)  
- Additional geospatial or sensor data formats (optional)

---

## Output Data format

- **uint8 GeoTIFF images**  
- Segmentation masks  
- Bounding boxes  
- Point-cloud labels
- class labels (buildings, asfalt, road markings , people, balconys, windows , water, roads , gravel )
(Depending on task)

## Benchmark result
  rsult on KDS-change detection dataset : 98% pixel accuracy, change detection Precision score 0.5 , change detction recall score : 0.6 

---

## Project Links

Include references to relevant resources:

- GitHub repository  
- Hugging Face model page  
- Company project homepage  
- Additional documentation  

---
