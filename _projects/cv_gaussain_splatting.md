---
layout: post
title: 3D Gaussian Splatting SAM
description: 
tags: python, pytorch
img: https://github.com/yi-cheng-liu/3d_gaussian_sam/raw/main/.assets/bulldozer.gif
importance: 1
category: Computer Vision
toc:
  sidebar: left
---


### 🚀 1. Motivation

The recent Neural Radiance Fields (NeRF) offers impressive results in building 3D objects given several surrounding images. However, it still has some drawbacks, such as its reliance on the Multi-Layer Perceptron (MLP) network, and the time-consuming training process. NVIDIA addresses the problem with [instant-ngp](https://github.com/NVlabs/instant-ngp), a solution that significantly accelerates NeRF's training, but still with some blurry effect on the object. Thus, to further enhance the fine details, 3D Gaussian splatting employs Gaussian-based representation. Even though, objects still have to be extracted, which Segment Anything Model (SAM) has great performance on such a task. Integrating SAM's robust segmentation capabilities with the intricate 3D Gaussian representation, we introduce a novel method aimed at delivering unparalleled quality on 3D objects given 2D images.

### 📊 2. Dataset

This project consists of two datasets, MipNeRF-360 and Food-360. MipNeRF-360 could be found in the official [website](https://jonbarron.info/mipnerf360/) of MipNeRF. Food-360 dataset could be found in [here](https://www.kaggle.com/datasets/liuyiche/food-360-dataset/). 

#### MipNeRF-360

```bash
cd datasets
# Dataset Pt.1
wget http://storage.googleapis.com/gresearch/refraw360/360_v2.zip

# Dataset Pt.2
wget https://storage.googleapis.com/gresearch/refraw360/360_extra_scenes.zip
```

#### Food-360

```bash
# Setup the kaggle api first
kaggle datasets download liuyiche/food-360-dataset/
```

The structure of the project will look like this

```bash
├── 3d_gaussian
├── bounding_box_sam.py
├── clip_sam.py
├── colmap
├── Dataset # unzip before use
│   ├── 360_extra_scenes.zip
│   ├── 360_v2.zip
│   ├── Food-360-dataset.zip
│   └── convert_video
├── nerfstudio
├── output
├── EADME.md
├── segment-anything
│   ├── ...
│   └── model_checkpoint
└── train.py
```
