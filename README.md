# Lymph Node Malignancy Detection using Ensemble Deep Learning

An ensemble learning based deep learning architecture for detecting malignancy in mediastinal lymph nodes from CT images.

## Overview

This project implements an ensemble deep learning approach to detect malignant lymph nodes in CT scan images. The architecture combines multiple custom deep learning models using stacking ensemble techniques to achieve high accuracy in classification.

## Key Features

- Non-invasive malignancy detection using CT images
- Ensemble architecture combining multiple custom CNN models
- Stacking ensemble approach for improved performance
- High accuracy metrics (98.56% accuracy, 99.09% sensitivity)

## Model Architecture

The ensemble architecture consists of:

- Multiple custom CNN models (Model1, Model2, Model3)
- Pre-trained models (AlexNet, FCN, ResNetV2, Xception)
- Stacking ensemble combining model predictions

## Performance Metrics

The model achieves:

- Accuracy: 98.56%
- Sensitivity: 99.09% 
- Specificity: 98.04%
- AUC: 98.56%

## Requirements

- Python 3.7+
- TensorFlow 2.x
- Keras
- NumPy
- scikit-learn
- OpenCV
- pandas



## Citation

If you use this code in your research, please cite:

BibTeX:

```
@INPROCEEDINGS{10048891,
  author={Praneeth, Posina and Lakshmi, Abothula Dhana and Tekchandani, Hitesh and Verma, Shrish and Londhe, Narendra D.},
  booktitle={2023 13th International Conference on Cloud Computing, Data Science & Engineering (Confluence)}, 
  title={Ensemble learning based Deep Learning Architecture for malignancy detection of mediastinal lymph nodes in CT images}, 
  year={2023},
  volume={},
  number={},
  pages={439-443},
  keywords={Deep learning;Sensitivity;Computed tomography;Computational modeling;Biopsy;Computer architecture;Planning;Ensemble learning;Stacking;Deep learning;Lymph nodes;Cancer;CT.},
  doi={10.1109/Confluence56041.2023.10048891}}
```
