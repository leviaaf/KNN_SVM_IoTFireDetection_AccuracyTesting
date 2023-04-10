# KNN_SVM_IoTFireDetection_AccuracyTesting
This repository contains code for testing the accuracy of the K-Nearest Neighbors (KNN) and Support Vector Machine (SVM) classifiers for IoT fire detection.

## Introduction
This repository contains two Python scripts to test the accuracy of KNN and SVM classifiers in detecting fires in an IoT environment. The [dataset](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/Training%20Dataset.csv) used in this project is the IoT Fire Detection [dataset](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/Training%20Dataset.csv), which contains data from various sensors that detect temperature, humidity, smoke, and flame in the environment.

The [KNN_IoTFireDetection.ipynb](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/KNN_IoTFireDetection.ipynb) script uses the KNN classifier to predict whether a fire has occurred based on the sensor data. The [SVM_IoTFireDetection.ipynb](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/SVM_IoTFireDetection.ipynb) script uses the SVM classifier to predict the same.

Open the complete analysis here.

## Dependencies
The following libraries are required to run the scripts:
- [numpy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib.pyplot](https://matplotlib.org/stable/api/pyplot_summary.html)
- [seaborn](https://seaborn.pydata.org/)
- [sklearn](https://scikit-learn.org/stable/)
### KNN
- [sklearn.neighbors.KNeighborsClassifier](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
### SVM
- [sklearn.svm.SVC](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)

## Usage
To run the scripts, open [KNN_IoTFireDetection.ipynb](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/KNN_IoTFireDetection.ipynb) or [SVM_IoTFireDetection.ipynb](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/SVM_IoTFireDetection.ipynb) on Google Colab, download the [dataset](https://github.com/leviaaf/KNN_SVM_IoTFireDetection_AccuracyTesting/blob/7e88c54b21fe9e7821a5f33881781d5f2d74e840/Training%20Dataset.csv) and upload it to Files in Google Colab.

You can also modify the percentage of training and testing data by adjusting **test_size** in In [10] for KNN and In [9] for SVM. The value of K in KNN can be changed by replacing the value of **n_neighbors** in In [21].

Do you have your own dataset? Please upload your dataset and change the dataset filename in In [2] to your new filename.
