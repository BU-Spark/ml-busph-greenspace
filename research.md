
# Research Document

## 1. Introduction

### 1.1 Background
Outdoor greenspace has become a focus of attention to improve the kindergarten through grade 12 (K-12) school environment and increase sustainability of school campuses. Greenspace provides benefits across a range of ecosystem services, but little is known about its impact on student learning in K-12 schools, due in part to the lack of interdisciplinary work necessary to study the full pathway from ecosystem mechanisms to learning outcomes benefits. Additionally, although scientists know there are racial and economic disparities in greenspace in environmental justice and communities impacted by historic racist practices (e.g. redlining), nothing is known about disparities in ES mechanisms. This project is part of several ongoing environmental health research studies at BUSPH, to study the impact of built environment and indoor environmental quality in K-12 schools on learning and health, with a sustainability and equity focus.

### 1.2 Objectives of the research
We surveyed various semantic image segmentation techniques for our preliminary research. Our project can be broken down to the following components: 1) identifying vegetation, 2) environmental factors and 3) structures such as parks and windows.


## 2. Literature Review

Resources
- https://link.springer.com/chapter/10.1007/978-3-030-39878-1_22
- https://www.researchgate.net/publication/360476663_Mapping_street_trees_using_Google_Street_View_and_Artificial_Intelligence
- https://partnet.cs.stanford.edu/
- https://github.com/sacmehta/EdgeNets
- https://www.mdpi.com/2072-4292/13/11/2031
- https://ieeexplore.ieee.org/document/8622536
- https://drive.google.com/viewerng/viewer?url=https://openaccess.thecvf.com/content_cvpr_2017/papers/Achanta_Superpixels_and_Polygons_CVPR_2017_paper.pdf

### A.
One of the challenges of this project is the granularity of structures to which our algorithm must be able to identify in the data which are aerial images. For example, the client identified windows as being an object of interest so we are challenged to ensure that we identify windows as being separate from buildings. Thus, we looked into instance segmentation which is a hybrid of both semantic segmentation and object detection. Instance segmentation algorithms have three main approaches: 1) segmentation first, classification next 2) classification first, segmentation next and 3) simultaneously performing classification and segmentation.

### B.
Mask R-CNN has demonstrated promising results for aerial imagery. It takes the third approach of simultaneously detecting objects and generating a mask for each instance. It generates three outputs for each target object: 1) class label, 2) a bounding box and 3) a mask. However, before we can implement it, we would need to label our data to some extent because it takes in class_names parameter that lists all of the class instances and the image background. A helpful open source tool we can use to automate labeling is Label Studio. Since the other instance segmentation techniques require some sort of “ground truth”, it makes sense for our next step to be to experiment with Label Studio on our available data.

### C.
This fifth research evaluates two deep learning model techniques for semantic segmentation of Urban Green Space(UGS) polygons with the use of different convolutional neural network encoders on the U-Net architecture and very high resolution (VHR) imagery to obtain updated information on UGS polygons at the metropolitan area level. 
Results demonstrate that this methodology is an accurate digital tool for extracting and updating geometrical UGS databases at the metropolitan level (Dice coefficient of 0.57, recall of 0.8, IoU of 0.75, and kappa coefficient of 0.94). 
This new cartography may improve making maps more accessible to urban residents and decision-makers.


## 3. Main Approach
Here is a diagram that shows some approach we plan to take for producing different variables of the resulting dataset 

Specific methods for techniques mentioned above:

### 3.1 Detect/Segment ‘windows’ from a image 


### 3.2 Object Detection Playground, Solar Panels

- Simple Linear Iterative Clustering (SLIC) superpixel segmentation.
	Simple Linear Iterative Clustering is the state of the art algorithm to segment superpixels which doesn’t require much computational power. In brief, the algorithm clusters pixels in the combined five-dimensional color and image plane space to efficiently generate compact, nearly uniform superpixels. This algorithm was developed at Image and Visual Representation Group (IVRG) at EPFL and here’s the published paper and official source code.
- 


### 3.3 Color Classcifier

- [Color-tags](https://huggingface.co/spaces/rrighart/color-tags)

### 3.4 Detect Pavement

