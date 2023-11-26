# Fine-tuning ResNet on CUB-200-2011 Dataset

# Introduction

This repo contains codes for fine tuning ResNet on CUB_200_2011 datasets. It uses pre-trained models provided by torchvision.

## Datasets

#### CUB200-2011
CUB-200-2011 dataset has 11,788 images of 200 bird species. 

## How to Use

```
python train.py --net_choice ResNet --model_choice 50
```

## Results

Model: ResNet50
Learning Rate: 0.001
Batch Size - Training: 64
Batch Size - Testing: 32
Test Accuracy: 84.49%

## Original Code
git clone https://github.com/zhangyongshun/resnet_finetune_cub.git