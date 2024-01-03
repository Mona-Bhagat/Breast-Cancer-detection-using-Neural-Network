# Breast-Cancer-classification-using-Neural-Network


![Breastcancer](https://github.com/Mona-Bhagat/Breast-Cancer-detection-using-Neural-Network/assets/148805047/67c4c111-6fd7-4860-8a07-a32afa298ac5)


# Project Overview
This project aims to build a Tumour classification model using Neural Network. The dataset has 30 features which are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.


# Data Sources
The primary dataset used for this analysis is the multivariate type of dataset "breastcancerdata" file. The dataset is publicly available on link -(https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
The model diagnostically helps classify whether the tumor is Benign or Malignant.  


# Tools
	• Excel CSV
 	• Google Colab
  • Following dependencies/libraries were imported:
  * pandas
  * numpy
  * matplotlib
  * sklearn
  * TensorFlow
    
      
# Steps involved

* Import of required libraries
* import of data from sklearn and loading into a data frame
* Checking any missing values 
* Checking the distribution of Target Variable
* Separating the features and target
* Splitting the data into training and test data
* Standardize the data as features due to their nature are captured on a different scale from each other 
* Building the Neural Network using Tensorflow and Keras
* Model evaluation using accuracy score
* Building a Predictive system with our trained model


# Results
The analysis results are summarized as follows:
* Accuracy on Training data:  0.9565 (Epochs - 10)
* Accuracy score on Test Data:  0.9386
* The model build was able to correctly classify the sample data into Benign or Malignant category
