# An Attention-Enhanced ResNet50 Framework for Multi-Class Outdoor Image Classification

## Overview
This project presents an attention-enhanced ResNet50 model for multi-class outdoor image classification.
The model improves classification performance by integrating spatial attention and dynamic class reweighting.

## Model Architecture
- Backbone: ResNet50 (ImageNet pretrained)
- Attention: Spatial attention applied to deep feature maps
- Optimization: Adam optimizer
- Explainability: Grad-CAM visualization

## Dataset
- Total images: 2,160
- Number of classes: 5
- Train / Validation split: 80% / 20%
> Dataset is not included in this repository.

## Results
- Validation Accuracy: **~89.8%**
- Improved performance compared to baseline ResNet50

