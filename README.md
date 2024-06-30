# Arrhythmia Detection Using Transformer Models and ECG Images

## Overview

This project aims to utilize Vision Transformers (ViTs) for detecting arrhythmias in electrocardiogram (ECG) images. By leveraging state-of-the-art transformer architectures such as BEiT, DEiT, Swin Tiny, and ViT, combined with knowledge distillation techniques, we aim to develop an accurate and efficient arrhythmia detection system.

## Goals

1. **Process the 12-Lead ECG Image Dataset into Separate Leads**:
   - Develop preprocessing techniques to separate the 12-lead ECG images into individual leads.
   - Ensure that the separation process preserves the integrity and accuracy of the ECG signal in each lead.

2. **Study and Implement Various Transformer Architectures**:
   - Research and study the following transformer architectures: BEiT (Vision Transformer with Bidirectional Encoder Representations from Transformers), DEiT (Data-efficient Image Transformer), Swin Transformer (Swin), and ViT (Vision Transformer).
   - Implement each transformer architecture and customize them for processing ECG images.

3. **Perform Knowledge Distillation from Transformer to CNN**:
   - Explore knowledge distillation techniques to transfer knowledge learned by the transformer models to convolutional neural network (CNN) architectures.
   - Design experiments to distill knowledge from the trained transformer model to a CNN architecture suitable for arrhythmia detection.


## Features
- ECG Image Data Processing
- Fine-tuning BEiT, ViT, DEiT, Swin Tiny
- Knowledge Distillation

## Dataset

The dataset consists of 12-lead ECG images collected from diverse sources, annotated with arrhythmia types by medical experts. Preprocessing techniques will be applied to segment the images into individual leads, ensuring accurate representation of the ECG signals.

Please find the dataset link here: https://data.mendeley.com/datasets/gwbz3fsgp8/2


## Organization of the Directory
```
|   .gitignore
|   README.md
|   requirements.txt
|       
+---analysis
|       analysis.ipynb
|       
+---data_processing
|       data-preprocess.ipynb
|       k-fold-split.ipynb
|       
+---knowledge_distillation
|       knowledge-distill.ipynb
|       test.ipynb
|       
\---training
        beit-train.ipynb
        deit-training.ipynb
        google-vit.ipynb
        swin-tiny.ipynb
```

