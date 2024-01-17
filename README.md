# HarvestWise-Predictor

## Overview
This repository contains the code for a machine learning project focused on recommending suitable crops based on soil and environmental conditions. The project employs various machine learning algorithms, including Decision Trees, Gaussian Naive Bayes, Support Vector Machine (SVM), and Logistic Regression. These models are trained on a dataset featuring information such as nitrogen, phosphorous, potassium levels, temperature, humidity, pH, and rainfall.

## Project Structure

- **Data:** The dataset used for training and testing is stored in the file `Crop_recommendation.csv`.
- **Code:** The Python code for the project is organized into a Jupyter Notebook named `Crop_Recommendation.ipynb`.
- **Models:** Trained models are saved for future use. The Decision Tree model is saved as `DecisionTree.pkl`, Randomforest is saved as `RandomForest.pkl` and the Gaussian Naive Bayes model is saved as `NBClassifier.pkl`.

## Results

- Decision Tree Model Accuracy: 90.0%
- Gaussian Naive Bayes Model Accuracy: 99.1%
- SVM Model Accuracy: 10.7%
- Logistic Regression Model Accuracy: 95.2%


## Data

The dataset (`Crop_recommendation.csv`) contains information about soil and environmental conditions, including N (Nitrogen), P (Phosphorous), K (Potassium), temperature, humidity, pH, rainfall, and the corresponding crop labels.

