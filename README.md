# CACD2000-Aging

<div><img src=./images/dataset_samples.jpg></div>

## Overview
CACD-Aging is a Dataset of human faces designed for benchmarking age transformation algorithms as well as many other possible vision tasks.

This dataset is an extention of the [CACD2000 dataset](http://bcsiriuschen.github.io/CARC/), on top of the 160,000 original CACD2000 images, it also contains the following information for each image:
1. Gender information (male/female with confidence score)
2. Age group information (5 classes with confidence score)
3. Head pose (pitch, roll & yaw)
4. Glasses type (none, normal or dark)
5. Eye occlusion score (0-100, different score for each eye)
6. Face Quality(0-100)
8. Full semantic map (16 classes)

## Dataset Statistics
The following histogram shows the age class distribution per gender.

<div><img src=./images/age_distribution.png></div>

Gender labels & confidence, age class labels & confidence score, head pose, glasses type and left & right eye occlusion scores for each individual image are stored in **FacePlusPlusLabel.csv**.

## Detailed Description

**Female.csv**:This file contains the labels of all women in CACD2000-aging.

**Male.csv**:This file contains the labels of all man in CACD2000-aging.

**Semantic segmentation**:This folder stores the segmented images parsed by Huawei.
