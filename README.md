# Prediction-of-Cellular-Composition-Using-Machine-Learning

The objective is to develop a regression model for predicting the number of six different types of cells in a given histological image patch as well as the total number of cells in the image patch. Your task is to develop a machine learning model that uses training data (patch images with given cell counts) to predict cell counts of each type in test images as well as the overall number of cells in each image. Counts of different types of cells in a given image patch is called its cellular composition. Using the data for the CoNIC: Colon Nuclei Identification and Counting Challenge (see: https://github.com/TissueImageAnalytics/CoNIC and https://arxiv.org/abs/2111.14485 for details about the challenge)

## The data 
The data consists of 3 folds (in variable F). Here, X is a matrix containing N 256x256x3 Red-Green-Blue (RGB) channel images of size 256x256 pixels and Y is an Nx6 matrix with each row corresponding to a single image patch and each column corresponding to the 6 cell types (called T1: neutrophil , T2: epithelial T3: lymphocyte, T4: plasma , T5: eosinophil and T6: connective). Thus, for a single image, we are given the counts of each of the six cell types. The overall number of cells in an image can be obtained by summing up the number of cells of each type.
## Training and Testing: 
Using data from the first two folds for training and validation and the third fold for testing. 

## Tasks Performed:
### 1. Data Analysis
### 2. Feature Extraction and Classical Regression
### 3. Using Convolutional Neural Networks
