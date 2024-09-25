# CNN Comparison - Performance and Bias


# Project Overview

This project aims to achieve the highest possible accuracy in image classification by exploring the performance of Convolutional Neural Network (CNN) models such as LeNet and AlexNet. It is connected to a Kaggle project. For more information on the topic and to retrieve the data, please refer to the **Objectives.pdf** file.

In addition to classification, the project also examines the potential introduction of bias into machine learning models and its impact on classification results.

## Implemented Models

- **LeNet**
- **AlexNet**

## Key Features

- Image preprocessing with PyTorch, including:
  - Grayscale conversion
  - Resizing
  - Data augmentation (e.g., random vertical flip)
- Training CNN models with different optimizers:
  - Adam for LeNet
  - SGD for AlexNet
- Dataset preparation:
  - Training on both original and biased versions of ImageNet

## Prerequisites

To run the notebooks, you will need:

- **Python** 3.10.12 or higher
- The following packages:
  - `os`, `numpy`, `pandas`, `torch`, `torchvision`, `PIL`, `pathlib`, `matplotlib.pyplot`, `tqdm`, `sklearn`
- Download the data from Kaggle and place it in this directory.

## Content

This Git repository contains:

- A file presenting the project topic: **Objectives.pdf**
- A notebook addressing the image classification problem: **Projet_Kaggle.ipynb**
- A report answering the questions posed by the project: **Compte_rendu_VF.pdf**

---

Follow the detailed steps in the **Objectives.pdf** file to better understand the project's context and results.
