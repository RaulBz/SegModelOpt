# SegModelOpt
## Overview

This repository demonstrates training, optimizing, and compressing deep learning models for medical image segmentation. It currently focuses on U-Net, but will expand to other architectures in the future. The optimization techniques explored include:
1. Quantization:
-  Post-Training Quantization (PTQ)
-  Quantization-Aware Training (QAT)
3. Pruning.
4. Mixed precission.
5. Change Dataset to medical Images:
-  iTS - Liver Tumor Segmentation Challenge: https://competitions.codalab.org/competitions/17094
-  Medical Segmentation Decathlon: http://medicaldecathlon.com/
7. Trying networs beyond U-net(Future Work):
-   Net++
-  Mobile-UNet
-  DeepLabV3 / DeepLabV3+
-  Mask R-CNN


## 🚧 **Work in Progress** 🚧
This project is in its early stages and is actively evolving. The current implementation serves as a code skeleton, and several improvements are planned, including:
-  Better model training (e.g., more epochs, adaptive learning rates, improved loss functions)
-  Refactoring and improved code structure
-  Enhanced optimization techniques

Expect frequent updates and breaking changes as the project progresses.
