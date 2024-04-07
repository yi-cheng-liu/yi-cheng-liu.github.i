---
layout: page
title: Computer Vision
description: 
img: /assets/img/cv_computer_vision/hw3_t6_huron_combined.jpg
importance: 2
category: Computer Vision
---

:computer: [Github repo](https://github.com/yi-cheng-liu/traditional-computer-vision)

## Assignment 1 - Data Visualization, Image Dithering

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <div class="center-justify"></div>
        Original
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_cosmos_orig.png" title="Cosmos Original" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_david_orig.png" title="David Original" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_vladimirka_orig.png" title="Vladimirka Original" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Quantize Naive
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_cosmos_quantizeNaive.png" title="Cosmos Quantize Naive" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_david_quantizeNaive.png" title="David Quantize Naive" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_vladimirka_quantizeNaive.png" title="Vladimirka Quantize Naive" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Quantize Floyd
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_cosmos_quantizeFloyd.png" title="Cosmos Quantize Floyd" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_david_quantizeFloyd.png" title="David Quantize Floyd" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_vladimirka_quantizeFloyd.png" title="Vladimirka Quantize Floyd" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Quantize Floyd with gamma correction
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_cosmos_quantizeFloydGamma.png" title="Cosmos Quantize Floyd with gamma correction" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_david_quantizeFloydGamma.png" title="David Quantize Floyd with gamma correction" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw1_vladimirka_quantizeFloydGamma.png" title="Vladimirka Quantize Floyd with gamma correction" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

## Assignment 2 - Image Filtering, Feature Extraction, Blob Detection

## Assignment 3 - Synthetic Views, Image Warping, Augmented Reality

### Synthetic Views

<!-- Synthetic Views -->
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        Original
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t5_palmer_original.jpg" title="Original Palmer" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t5_threebody_original.jpg" title="Original Threebody" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        After (Synthetic Views)
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t5_palmer_frontoparallel.jpg" title="Synthetic Views Palmer" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t5_threebody_frontoparallel.jpg" title="Synthetic Views Threebody" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Image Warping

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        Before img 1
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_eynsham_img1.jpg" title="Image Warping Eynsham Img1" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_florida_img1.jpg" title="Image Warping Florida Img1" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_huron_img1.jpg" title="Image Warping Huron Img1" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Before img 2
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_eynsham_img2.jpg" title="Image Warping Eynsham Img2" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_florida_img2.jpg" title="Image Warping Florida Img2" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_huron_img2.jpg" title="Image Warping Huron Img2" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        After
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_eynsham_combined.jpg" title="Image Warping Eynsham Combined" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_florida_combined.jpg" title="Image Warping Florida Combined" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t6_huron_combined.jpg" title="Image Warping Huron Combined" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

### Augmented Reality - low cost version

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        Scene
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_florence_scene.jpg" title="Florence Scene" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lacroix_scene.jpg" title="Lacroix Scene" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lego_scene.jpg" title="Lego Scene" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Template
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_florence_template.png" title="Florence Template" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lacroix_template.png" title="Lacroix Template" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lego_template.png" title="Lego Template" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Seals
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_michigan.png" title="Michigan Seals" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_monk.png" title="Monk Seals" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_toysrus.png" title="Toysrus Seals" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        Augmented Reality
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_florencemichigan_augmented.jpg" title="Florence Michigan Augmented" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lacroix_monk_augmented.jpg" title="Lacroix Monk Augmented" class="img-fluid rounded z-depth-1" %}
        {% include figure.liquid loading="eager" path="/assets/img/cv_computer_vision/hw3_t7_lego_toysrus_augmented.jpg" title="Lego Toysrus Augmented" class="img-fluid rounded z-depth-1" %}
    </div>
</div>