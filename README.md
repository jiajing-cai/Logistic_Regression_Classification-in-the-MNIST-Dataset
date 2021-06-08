# Logistic_Regression_Classification-in-the-MNIST-Dataset
Handwritten Digit Recognition System (MNIST) Based on Logistic Regression Model


## Introduction
This project is to use logistic regression model to predict handwritten digits recognition. The logistic model aims to classify the digit as even and odd. The data set is based on MNIST and contains 10 digits from 0 to 9. MNIST is a typical data set for machine learning and deep learning algorithms. The training set contains 60000 examples, and the test set 10000 examples. The first column indicates the label of the digits, and the rest of 784 columns indicate pixel of each image.

## Goal
Implement a basic character recognition system of handwritten digits using logistic regression. The data set provided contains instances of the 10 digits available (0 through 9). The goal is to train and test a logistic regression model that classifies the image of a digit as even or odd.
Steps:
1. Relabel each row with a 1 if the digit it corresponds to is even, and 0 if it is odd.
2. Train a logistic regression model to learn the binary variable you just created using all the columns that correspond to pixel values as inputs.
3. Study and create the ROC to understand the effects of various threshold values for classification.


## Critical Analysis of the Results
Through the establishment of a logistic regression model, the prediction and analysis are carried out on the handwritten digit recognition data set. From the training results, the logistic regression model achieved a great accuracy of 89.95%. This means that most of the predictions are accurate.
In addition, I also created an ROC curve based on the model. As we all know, ROC curve is widely used in machine learning and many other fields. It can easily detect the influence of any threshold on the generalization performance of the learner. The closer the ROC curve is to the upper left corner, the higher the recall of the model. The point on the ROC curve closest to the upper left corner is the best threshold with the least classification error, and has the least total number of false positives and false negatives.
In this project, the value of TPR (0.899) is high, the value of FRP (0.100) is low, and even the AUC is 0.96, which is almost close to 1. This can indicate that using a logistic regression model to predict this data is a good choice. Besides the logistic regression model, I haven't tried other machine learning and deep learning models. I am not sure if there are other models with better predictive performance. However, in my opinion, from the current accuracy and ROC curve performance, logistic regression is a good model so far.
