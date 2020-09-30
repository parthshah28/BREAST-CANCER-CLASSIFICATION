# [BREAST-CANCER-CLASSIFICATION](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION)
Predicting if the cancer diagnosis is benign or malignant based on several observations/features

## Problem Statement
Predicting if the cancer diagnosis is benign or malignant based on several observations/features
30 features are used, examples:

  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry 
  - fractal dimension ("coastline approximation" - 1)
Datasets are linearly separable using all 30 input features

Number of Instances: 569
Class Distribution: 212 Malignant, 357 Benign
Target class:
   - Malignant
   - Benign
   
## Dataset
Download Dataest from Sci-kit Learn.

## EDA
![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download%20(1).png)

![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download.png)

![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download%20(2).png)

![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download%20(3).png)

## Model Building
I used SVC model.

### Confusion Matrix (before improving model)
![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download%20(5).png)

### Confusion Matrix (after improving model)
![](https://github.com/parthshah28/BREAST-CANCER-CLASSIFICATION/blob/master/images/download%20(4).png)

