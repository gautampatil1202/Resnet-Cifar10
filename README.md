# ResNet-CIFAR10: Enhanced Image Classification

This repository contains the implementation of a **modified ResNet** architecture for **CIFAR-10 image classification**. 

## Overview
- **Dataset**: CIFAR-10 (60,000 images, 10 classes)
- **Architecture**: Residual Networks (ResNet)
- **Enhancements**: Dropout, batch normalization, LR scheduling, and advanced data augmentation
- **Goal**: Achieve high classification accuracy with an efficient model

## Implementation Details
### Model Architecture
- **Residual Blocks**: Allow deep networks to train effectively
- **Dropout & Batch Normalization**: Reduce overfitting and stabilize training
- **Advanced Data Augmentation**: AutoAugment, horizontal flipping, padding, and random cropping
- **Learning Rate Scheduling**: Multi-step LR scheduler for better convergence

### Training Setup
- **Optimizer**: SGD with momentum (0.9) and weight decay (5e-4)
- **Loss Function**: Cross-Entropy with Label Smoothing
- **Batch Size**: 128
- **Epochs**: 150
- **Device**: CUDA (if available) / CPU



