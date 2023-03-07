# Predicting Machines Failure using Machine Learning Classification Models

Predicting Machines Failure using Machine Learning Classification Models

The goal of this project is to use historical data of machines and their failures to predict whether a machine is likely to fail or not.

## Motivation
Machine failure can be costly for companies in terms of downtime, maintenance, and repair costs. Predictive maintenance has become an important tool for companies to reduce these costs by identifying potential failures before they occur. Machine learning classification models are well-suited for predicting machine failure, and can help companies implement proactive maintenance strategies.

## Data Source
The data used for this project is from <a href="https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification" target="_blank">Kaggle</a>. The dataset contains information on various machines and their failures, including attributes such as Temperature, Type, Rotational Speed, Torque and Tool wear in minutes.

## EDA (Exploratory Data Analysis)
Checking distribution and correlations.

## Data Preprocessing
The data is preprocessed to handle outliers values and remove irrelevant features.

## Data Pipeline
Pipeline to convert categorical features into numbers and testing MinMaxScaler and Standard Scaler.

## Cross-Validation of models
We compared several classification models based on its precision (since it's a imbalanced dataset, accuracy is not the best metric to monitor).

## Hyperparameters
180 Combinations of models to identify the best hyperparameters.

## Model Building
Using the best model and best hyperparameters, generating a confusion matrix.

## Predicting
Dropping features on the original dataset and predicting failures using our pipeline.

## Conclusion
In conclusion, this project demonstrates the feasibility of using machine learning classification models for predicting machines failure. The best performing model can be used by companies to implement proactive maintenance strategies and reduce the costs associated with machine failure.
