# Project Name
Melanoma Detection Assignment
In this assignment, we have build a multiclass classification model using a custom convolutional neural network in TensorFlow.

## Table of Contents
* [General Information](#general-information)
* [Problem Statement](#Problem-Statement)
* [Project Pipeline](#Project-Pipeline)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis. In this assignment, I am building multiclass classification model using a custom convolutional neural network in TensorFlow. The model can classify images in malignant and benign oncological diseases (Actinic keratosis,Basal cell carcinoma,Dermatofibroma,Melanoma,Nevus,Pigmented benign keratosis,Seborrheic keratosis,Squamous cell carcinoma,Vascular lesion)
The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

## Problem Statement
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:

Actinic keratosis
Basal cell carcinoma
Dermatofibroma
Melanoma
Nevus
Pigmented benign keratosis
Seborrheic keratosis
Squamous cell carcinoma
Vascular lesion

## Project Pipeline
Data Reading/Data Understanding
Dataset Creation
Dataset visualisation
Model Building & training
Chose an appropriate data augmentation strategy to resolve underfitting/overfitting
Model Building & training on the augmented data
Class distribution
Handling class imbalances
Model Building & training on the rectified class imbalance data

## Technologies Used
Tensorflow 
Keras
Numpy 
Pandas 
Matplotlib 
Scikit-learn
Augmentor
PIL

## Conclusions
Model overfits as the there is a huge gap between training and validation accuracy is the first model without augmented data and with class rebalance - Train_accuracy: 0.8783, validation_accuracy: 0.5168
After image augmentation the overfit is resolved as the gap between training and validation loss decreased, but the accuracy is still low - Train_accuracy: 0.5525, validation_accuracy: 0.4474
Model performs much better after class imbalance treatment - Train_accuracy: 0.8448, validation_accuracy: 0.7528

## Acknowledgements
References:
Melanoma Skin Cancer from https://www.cancer.org/cancer/melanoma-skin-cancer/about/what-is-melanoma.html
Efficient way to build CNN architecture from https://towardsdatascience.com/a-guide-to-an-efficient-way-to-build-neural-network-architectures-part-ii-hyper-parameter-42efca01e5d7
Image classification using CNN from https://www.analyticsvidhya.com/blog/2020/02/learn-image-classification-cnn-convolutional-neural-networks-3-datasets/

## Contact
Created by [@vaibhavi-4440] - feel free to contact me!
