# Iris Dataset classification
## Overview
The Jupyter Notebook focuses on using the K-Nearest Neighbors (KNN) algorithm to classify the Iris dataset. This machine learning model utilizes a unique dataset that includes sepal and petal properties to classify the type of Iris flower. The dataset consists of three types of iris flowers: Setosa, Versicolor, and Virginica, categorized based on their petal and sepal measurements.

## Dataset
The Iris dataset is a well-known dataset for classification tasks, containing:
- Features: Sepal length, Sepal width, Petal length, Petal width
- Target: Iris species (Setosa, Versicolor, Virginica)

## Project Structure
- Import seaborn and load Iris dataset
    - Basic Statistics
- Exploratory Analysis
- MACHINE LEARNING - Predictive Analysis
    - TRAIN and TEST Data
    - Build KNN - K Nearest Neighbors
        - Instantiating the KNN Algorithm
        - Trainning the KNN algorithm
        - Predicting with the Test Data and the KNN Algorithm
    - Validation
        - Cross Tabulation
        - Classification Metrics
             - Cross Validation
    - Optimizing the Parameter K (n_neighbors)
         - Defining a List for Parameter K
         - Instantiating the GridSearch Object
         - Training the GridSearch Object
