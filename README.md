# BoneNet: Bone Density Classification

This repository contains the implementation of a CBAM-enhanced EfficientNet-B0 model for bone density classification from knee X-ray images.

## Classes

- Normal
- Osteopenia
- Osteoporosis

## Model Architecture

- EfficientNet-B0 Backbone
- CBAM Attention Module
- Global Average Pooling
- Fully Connected Classification Layer

## Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## Dataset Structure

train/
├── Normal/
├── Osteopenia/
└── Osteoporosis/

## Training

Open the notebook:

BoneNet.ipynb

and run all cells in Google Colab.