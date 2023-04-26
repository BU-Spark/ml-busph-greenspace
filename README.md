# BU School of Public Health - Greenspace Ecosystem Services in K-12 schools
The goal of this specific machine learning project is to characterize ecosystem services (ES) disparities in K-12 schools in the US using satellite and street view imagery and ML image understanding techniques. 

# Structure
```
├── .github               
├── models # Mask-RCNN, UNet-Resnet
├── notebooks 
├── results 
├── Collaborators
├── LICENSE
├── Project Outline.md # start here for an overview
└── README.md
```

# Getting Started 
## notebooks
- [00-eda.ipynb](notebooks/00-eda.ipynb) - visualizes aerial images
- [01-mask_rcnn.ipynb](notebooks/01-mask_rcnn.ipynb) - visualizes annotated data and demonstrates how to train Mask-RCNN on 50m school aerial images
- [02-unet_resnet.ipynb](notebooks/...) - inference results of InceptionResNetV2-UNet on 500m school aerial images. Demonstrates complete workflow of aerial images to a queryable dataset

# To Do
* Fine tune the current models by either training on higher quality data or annotating the current aerial images 
* Explre other enviornmental factors that can influence quality of learning such as cooling, air pollution, physical activity
* Determine if there is a correlation between availibilty of ecosystem services and school location




