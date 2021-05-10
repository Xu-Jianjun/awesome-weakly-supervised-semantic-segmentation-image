# Awesome Weakly-supervised Image Segmentation

------

**<u>Contact me if any paper is missed!</u>**

------

[TOC]

### Semantic Segmentation

##### Weakly Supervised Semantic Segmentation performance on PASCAL VOC 2012 dataset

- **Sup.:** I-image-level class label, B-bounding box label, S-scribble label, P-point label.
- **Ext.:** Extra Data used for pre-training

|  Method   |   Pub.    | Backbone  | Sup. | Ext. | val  | test |
| :-------: | :-------: | :-------: | :--: | :--: | :--: | :--: |
|   WSSL    | ICCV2015  |  VGG-16   |  B   |  -   | 60.6 | 62.2 |
|   BBAM    | CVPR2021  | ResNet101 |  B   |  -   | 73.7 | 73.7 |
| NormalCut | CVPR2018  | ResNet101 |  S   |  -   | 74.5 |  -   |
| KernelCut | ECCV2018  | ResNet101 |  S   |  -   | 75.0 |  -   |
|    BPG    | IJCAI2019 | ResNet101 |  S   |  -   | 76.0 |  -   |
|           |           |           |  P   |  -   |      |      |
|           |           |           |  P   |  -   |      |      |
|           |           |           |      |      |      |      |
|           |           |           |      |      |      |      |
|           |           |           |      |      |      |      |

##### Semantic Segmentation supervised by image-level class (I)

- **Method:** "" 20
- **Method:** "" 20
- **Method:** "" 20
- **Method:** "" 20
- **Method:** "" 20
- **Method:** "" 20

##### Semantic Segmentation supervised by bounding box (B)

- **WSSL:** "Weakly-and semi-supervised learning of a deep convolutional network for semantic image segmentation" *ICCV2015*

- **BBAM:** "BBAM: Bounding Box Attribution Map for Weakly Supervised Semantic and Instance Segmentation" *CVPR2021*
- **Method:** "" 20

##### Semantic Segmentation supervised by scribble (S)

- **NormalCut :** "Normalized cut loss for weakly-supervised cnn segmentation" *CVPR2018*
- **KernelCut :** "On regularized losses for weakly-supervised cnn segmentation" *ECCV2018*
- **BPG:**  "Boundary Perception Guidance: A Scribble-Supervised Semantic Segmentation Approach" *IJCAI2019*

##### Semantic Segmentation supervised by point (P)



### Instance Segmentation

##### Todo

### Panoptic segmentation

##### Todo

### Dataset

##### PASCAL VOC 2012

##### MS COCO