# Spiral Image classification for Parkinsons' Diagnosis

This repository contains code and data for the binary classification problem of Parkinsons Diagnosis with the help of Hand-drawn Spiral image drawings.

## Dataset

The original dataset provided was 80 images of handwritten spiral drawings consisting of 15 images of static spiral test drawings of control patients, 15 image of dynamic spiral test drawings of control patients, 25 images of static spiral tests of Parkinson’s patients and 25 dynamic spiral tests of Parkinson’s patients. The size of the given dataset was increased to a dataset size of 240 images by applying a horizontal flip and vertical flip to all the original images. This augmented dataset was then randomly split into training and validation dataset each epoch with 80% of the dataset allocated to the training process and the rest allocated to validate the model. In order to test the performance of the model, a spiral drawings dataset was obtained from Kaggle [5]. The testing dataset contained a total of 30 images, where 15 were of control patients and 15 were of Parkinson’s patients.

## Project Details

MODEL Used : ResNet50 <br />
Epochs : 50    <br />
Loss Function : Cross Entropy Loss <br />
Optimizer : Stochastic Gradient Descent with Momentum<br />
