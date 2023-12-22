# Spiral Image classification for Parkinsons' Diagnosis

This repository contains code and data for the binary classification problem of Parkinsons Diagnosis with the help of Hand-drawn Spiral image drawings.

## Dataset

The original dataset provided was 80 images of handwritten spiral drawings consisting of 15 images of static spiral test drawings of control patients, 15 image of dynamic spiral test drawings of control patients, 25 images of static spiral tests of Parkinson’s patients and 25 dynamic spiral tests of Parkinson’s patients. The size of the given dataset was increased to a dataset size of 240 images by applying a horizontal flip and vertical flip to all the original images. This augmented dataset was then randomly split into training and validation dataset each epoch with 80% of the dataset allocated to the training process and the rest allocated to validate the model. In order to test the performance of the model, a spiral drawings dataset was obtained from Kaggle. The testing dataset contained a total of 30 images, where 15 were of control patients and 15 were of Parkinson’s patients.

![image](https://github.com/pranavp369/Parkinsons-Spiral-Classification/assets/41821351/12a02735-2a09-4fa7-a847-3f9eff84085d)  ![image](https://github.com/pranavp369/Parkinsons-Spiral-Classification/assets/41821351/6a26d381-31be-4133-8036-4701b80de697)





## Classification Pipeline

The newly augmented dataset was sent into a Pre-trained neural network module where ResNet50 model was used for feature extraction. The extracted features are sent into machine learning modules where several machine learning models like Support Vector Machine (SVM), Discriminant Analysis (LDA and QDA), K-Nearest Neighbour (KNN) and Decision Tree Classifier and AdaBoost Classifier were trained to binary classify between control patients and parkinsons' patients.


![image](https://github.com/pranavp369/Parkinsons-Spiral-Classification/assets/41821351/c1e73825-75de-4152-89aa-c35ada963c76)
