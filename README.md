# K Nearest Neighbors with Python

This repository contains a K Nearest Neighbors (KNN) classification project. The goal is to predict the class for a new data point based on the given features. The project uses a classified dataset with hidden feature column names, but the data and target classes are provided.

## Project Overview

In this project, we use the KNN algorithm to classify data points into target classes based on their feature values. The project demonstrates data standardization, model training, and evaluation.

## Requirements

- pandas
- seaborn
- matplotlib
- numpy
- scikit-learn

## Project Steps

1. **Import Libraries**: Import necessary libraries for data manipulation, visualization, and machine learning.
2. **Get the Data**: Load the classified dataset and inspect its structure.
3. **Standardize the Variables**: Scale the features to ensure all variables have equal influence on the distance calculations.
4. **Train-Test Split**: Split the data into training and testing sets.
5. **Train the Model**: Use KNN with different values of k to train the model and make predictions.
6. **Evaluate the Model**: Evaluate model performance using confusion matrix and classification report.
7. **Determine Optimal k**: Use the elbow method to determine the optimal value of k.

## Results and Conclusion

- Implemented the KNN classifier and evaluated its performance.
- Used the elbow method to find the optimal k value.
- Compared the model performance for k=1 and the optimal k.

## Usage

Run the Jupyter notebook to see the implementation and results.
