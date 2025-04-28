# 🌳 Tropical Forest Assessment Using Satellite Images

## Overview
This project focuses on assessing tropical forests by leveraging satellite imagery and deep learning models. We aim to classify and detect changes in tropical forest regions by training a convolutional neural network (CNN) model, specifically **DenseNet-121**.

## Objectives
- Collect satellite images from multiple tropical regions.
- Build and train a classification model for tropical forest assessment.
- Compare model predictions with publicly available environmental data.

## Methodology
### Data Collection
- Satellite images were gathered from diverse tropical regions.
- Images were preprocessed (resizing, normalization, augmentation).

### Model
- **DenseNet-121** CNN architecture was used for classification and detection.
- Transfer learning techniques were applied to enhance model performance.

### Evaluation
- Model predictions were validated against public datasets and ground truth information.


## Requirements
- Python 3.8+
- PyTorch
- torchvision
- scikit-learn
- matplotlib
- pandas
- numpy

### Install Dependencies
```bash
pip install -r requirements.txt
```
## Output Example

The model successfully detects and classifies tropical forest regions based on satellite imagery.

![Tropical Forest Detection Output](outputs/6.png)


