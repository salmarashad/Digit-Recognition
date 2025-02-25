# Digit-Recognition

This project is a PyTorch-based solution for the [IEEE Digit Recognition Competition](https://www.kaggle.com/competitions/ieee-digit-recognition-competition). The goal is to train a neural network to classify handwritten digits (0-9) using image data. This implementation had a 96.77% accuracy when tested using Kaggle's dataset. 

## Features  
- Loads and preprocesses training and test datasets  
- Defines a fully connected neural network  
- Trains the model using cross-entropy loss and Adam optimizer  
- Makes predictions on test data  
- Saves the results as a CSV file for submission  

## Requirements  
- Python 3  
- PyTorch  
- Pandas  

## Dataset  
You need to manually download the dataset from the [Kaggle competition page](https://www.kaggle.com/competitions/ieee-digit-recognition-competition):  
- **Training Data (`train.csv`)**: Contains pixel values and labels
- **Test Data (`test.csv`)**: Contains only pixel values 
