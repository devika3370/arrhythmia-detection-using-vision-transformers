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
Please find the processed data here: https://drive.google.com/drive/folders/1ezLJ8FAF142XAaxf3_vUIgCigu0NT21S?usp=sharing

## Trained Models
Please find the trained model weights here: https://drive.google.com/drive/folders/1ezLJ8FAF142XAaxf3_vUIgCigu0NT21S?usp=sharing

## Contributors
- Jessica Marshall (jm5679)
- Devika Gumaste (dg3370)

## Organization of the Directory
```
|   .gitignore
|   README.md
|   requirements.txt
|   
+---.ipynb_checkpoints
|       data-preprocess-checkpoint.ipynb
|       k-fold-split-checkpoint.ipynb
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

## Evidence of version control 
Please find the statistics of our version control here: https://github.com/ecbme6040/e6691-2024spring-project-DGJM-dg3370-jm5679/pulse

A snapshot for your reference:


<img width="680" alt="image" src="https://github.com/ecbme6040/e6691-2024spring-project-DGJM-dg3370-jm5679/assets/145230946/3386fd2c-f303-46f5-870c-b42d5ae98199">

