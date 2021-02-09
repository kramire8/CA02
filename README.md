# CA02: Naive Bayes Classification Algorithm
This is an email spam classifier that uses the Gaussian Naive Bayes model.

**Data Overview** <br />
There are two files in the data folder. The test files contain 702 emails that are equally divided into spam and non spam categories. The testing folder is used to predict the category of the email and report the accuracy with the known results.

## Steps 
1. Data Cleaning and Preparation 
2. Creating a dictionary with the 3,000 most common words
3. Extracting features and corresponding label matrix
4. Training and predicting with sklearn Naive Bayes
5. Printing the accuracy of test set for the training model

## Packages 
import os <br />
import numpy as np <br />
from collections import Counter <br />
from sklearn.naive_bayes import GaussianNB <br />
from sklearn.metrics import accuracy_score <br />

## Launch
Add the .ipynb file to: <br />
/content/drive/MyDrive/MSBA_Colab_2020/ML_Algorithms/CA02/Data <br />
Add the data to: <br />
'/content/drive/My Drive/MSBA_Colab_2020/ML_Algorithms/CA02/Data <br />

## Author
Karina Ramirez

## Contributors 
This project was provided by Dr. Arin Brahma at Loyola Marymount University for the Intro to Machine Learning course. <br />
