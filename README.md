# Data Science Projects

**Author:** Diarmuid O'Neill (C00282898@setu.ie)  
**Dates:** 27/11/2025 – 26/03/2026

## Brief Description

This repository demonstrates the application of a wide range of data science, machine learning, deep learning and clustering techniques using datasets sourced from Kaggle and the UCI Machine Learning Repository. The projects are written in Python using Jupyter Notebook and aim to investigate real-world problems through predictive modelling, classification, regression, clustering and neural networks.

The first section of the project investigates whether sleep and lifestyle factors can predict the presence of sleep disorders using a sleep, health and lifestyle dataset from Kaggle. Specifically, it examines which factors most significantly influence the presence of sleep disorders, what types of sleep disorders can be predicted and which factors most affect sleep quality. It was expected that stress level, sleep duration and physical activity would be among the most significant predictors of sleep disorders.

The second section expands on these concepts by applying additional machine learning and deep learning techniques to a variety of datasets. These notebooks investigate stock market prediction using K-Nearest Neighbours, image classification using Convolutional Neural Networks, binary classification using Support Vector Machines, time series forecasting using Recurrent Neural Networks and unsupervised clustering using Fuzzy C-Means and K-Medoids.

For more information about the sleep disorder investigation and research methods, see the technical specification:

* [Technical Specification](https://github.com/Revolution825/Data-Science-Project/blob/main/Documentation/Data%20Science%20Project%20Technical%20Specification.pdf)

## Models Used

### Regression Models

* [Linear Regression](https://github.com/Revolution825/Data-Science-Project/blob/main/LinearRegression.ipynb)
* [KNN Regression](https://github.com/Revolution825/Data-Science-Project/blob/main/KNN-Regression.ipynb)

### Classification Models

* [Gaussian Naive Bayes](https://github.com/Revolution825/Data-Science-Project/blob/main/NaiveBayes.ipynb)
* [Random Forest Classification](https://github.com/Revolution825/Data-Science-Project/blob/main/RandomForest.ipynb)
* [Logistic Regression](https://github.com/Revolution825/Data-Science-Project/blob/main/LogisticRegression.ipynb)
* [KNN Classification](https://github.com/Revolution825/Data-Science-Project/blob/main/KNN-Classification.ipynb)
* [Support Vector Machine](https://github.com/Revolution825/Data-Science-Project/blob/main/SVM-Sonar.ipynb)

### Clustering Models

* [K-Means Clustering](https://github.com/Revolution825/Data-Science-Project/blob/main/KMeansClustering.ipynb)
* [Fuzzy C-Means](https://github.com/Revolution825/Data-Science-Project/blob/main/Fuzzy%20C%20Means.ipynb)

### Deep Learning Models

* [Convolutional Neural Network](https://github.com/Revolution825/Data-Science-Project/blob/main/CNN.ipynb)
* [Recurrent Neural Network (LSTM)](https://github.com/Revolution825/Data-Science-Project/blob/main/RNN.ipynb)

## Results

### Sleep Health and Lifestyle Analysis

The Linear Regression models showed that as stress levels increase, reported sleep quality decreases as expected. Physical activity level was positively correlated with sleep quality, while age also appeared to have a positive relationship with sleep quality.

The Gaussian Naive Bayes and Random Forest Classification models proved to be the most successful at classifying whether individuals had particular sleep disorders. Age and physical activity emerged as particularly important features when predicting sleep apnea and insomnia.

K-Means Clustering using age and sleep duration revealed that individuals aged approximately 45–60 slept around half an hour longer than younger age groups. When all numerical features were included, K-Means naturally separated individuals into groups corresponding closely to different sleep disorder categories.

Logistic Regression also performed exceptionally well when predicting sleep disorders using all numerical features. AUC values of 0.9929 for insomnia and 0.95 for sleep apnea indicated strong predictive performance and high true positive rates.

### Additional Machine Learning and Deep Learning Investigations

The KNN Regression and Classification models were used to investigate whether stock market movements could be predicted one week in advance. Various values of *k* and feature combinations were evaluated to determine their impact on predictive performance.

The Convolutional Neural Network successfully learned visual patterns from butterfly images and demonstrated the effectiveness of deep learning techniques for image classification tasks.

The Support Vector Machine models compared both linear and non-linear kernels when classifying sonar responses as either rocks or sea mines. Model performance highlighted the importance of kernel selection when dealing with non-linearly separable data.

The Long Short-Term Memory (LSTM) Recurrent Neural Network was used to forecast household energy consumption. The notebook included model evaluation and hyperparameter tuning to improve forecasting accuracy and demonstrate the suitability of recurrent architectures for time series prediction.

The Fuzzy C-Means and K-Medoids clustering models were applied to a wheat seed dataset and compared in terms of clustering performance. The results provided insight into the strengths and limitations of both clustering approaches when dealing with naturally occurring classes in agricultural data.

## Weekly Log

* [Weekly Log](https://github.com/Revolution825/Data-Science-Project/blob/main/Log.txt)
