# Data Science Project
Author: Diarmuid O'Neill (C00282898@setu.ie) <br />
Date: 26/11/2025 <br />
Brief Description: <br />
This repository demonstrates the use of several data science models on a sleep, health and lifestyle dataset from [Kaggle](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset). The project aims to investigate if sleep and lifestyle factors can predict the presence of sleep disorders. Specifically which factors most significantly influence the presence of sleep disorders, what kind of sleep disorders can be predicted and what factors most affect sleep quality. It is expected that stress level, sleep duration and physical activity will be the most significant predictors of sleep disorders. For more information about the dataset and research methods, see [technical specification](https://github.com/Revolution825/Data-Science-Project/blob/main/Documentation/Data%20Science%20Project%20Technical%20Specification.pdf). <br />
### The models used:
* [Linear Regression](https://github.com/Revolution825/Data-Science-Project/blob/main/LinearRegression.ipynb)
* [Gaussian Naive Bayes](https://github.com/Revolution825/Data-Science-Project/blob/main/NaiveBayes.ipynb)
* [K-Means Clustering](https://github.com/Revolution825/Data-Science-Project/blob/main/KMeansClustering.ipynb)
* [Random Forest Classification](https://github.com/Revolution825/Data-Science-Project/blob/main/RandomForest.ipynb)
* [Logistic Regression](https://github.com/Revolution825/Data-Science-Project/blob/main/LogisticRegression.ipynb)

### Results
The Linear Regression models show us that as stress increases reported sleep quality decreases as expected. Interestingly, as physical activity level increases so too does sleep quality and as age increases, quality of sleep also increases. Gaussian Naive Bayes and Random Forest Classification models proved to be the most successful at correctly classifying if individuals had particular sleeping disorders or not. Age and physical activity also appeared to be the most important features for predicting the presence of sleeping disorders as they achieved a high level of accuracy when used with Gaussian Naive Bayes to predict sleep apnea and insomnia. Using K-Means Clustering with age and sleep duration revealed that people aged 45 - 60 sleep roughly half an hour longer than people in younger groups. When provided with all numerical features from the dataset K-Means Clustering naturally seperated people into groups based on which sleeping disorder they had. Logistic regression also proved to be very successful at predicting if an individual had a sleeping disorder or not given all numerical features from the dataset. AUC values of 0.9929 for insomnia and 0.95 for sleep apnea imply a high true positive rate.
