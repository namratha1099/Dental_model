# Dental Radiographs analysis using Neural Networks 
## Overview
This repository contains project code with .ipynb file written in Python that predicts output of an x-ray whether person having caries or not based on probability output that predicts from model.

## Project Objectives-
- **Analyze Dental X-rays:** Apply advanced neural networks and transfer learning to analyze dental radiographs.
- **Use Transfer Learning:** Employ transfer learning models to take advantage of pre-trained weights for improved accuracy.
- **Accurate Caries Detection:** Utilize MobileNet and other architectural models to segregate radiographs with caries, providing a probability output.
- **Efficient Application:** Offer a quick and accurate web application to assist dentists in evaluating x-rays, thereby saving time.

## Techniques-
- **Neural Networks:** Implemented various neural network architectures for training data and developing model.
- **Transfer Learning:** Applied different transfer learning models to utilize pre-trained weights and improve model performance depending upon the accuracy of the model that provides better prediction results.
- **MobileNet:** Achieved error-free results with better accuracy compared to others with MobileNet architecture, demonstrating high accuracy in caries detection.
- **Architectures**Along with MobileNet architecture, VGG16,ResNet,GoogleNet are the other implemented transfer learning models for optimized results.
  ## Methodology-
- **Data Preparation:** Collected dataset of x-ray images from hospitals in form of .pano images and converted into .jpg images with TWV software and uploaded data into google collaboratory
- -**Importing Modules:** Imported Keras module necessary for using algorithms from python using pip to install different modules.
- -**Data Splitting**-Trained data by dividing data into Train-validation-test approach that takes 60% of dataset for training 20% for validation and 20% for testing data.
- -**Model Development:** and used CNN layers with transfer learning algorithms for yielding better results with using pooling layers, sigmoid activation function and binary classification.
- -**Training model:** Trained model with epochs that can better make the model and saved model with .h5 extension that can be used elsewhere. Final model is having convolutional layer with mobile net architecture.
- **Model prediction:** Provided x-ray as input to model for prediction that gives out output value between 0 and 1. This was developed as web application using Flask as web framework

