# Cancer Risk Prediction using Naïve Bayes

## Overview

This project focuses on predicting patient outcomes based on cancer-related risk factors using a machine learning classification approach. The model is built using the Gaussian Naïve Bayes algorithm, providing a simple yet effective probabilistic solution for medical risk prediction.

## Objective

The goal of this project is to analyze patient data and classify outcomes into two categories:

* 0 → Survived
* 1 → Died

By leveraging statistical learning techniques, the model aims to support early risk assessment and decision-making.

## Dataset

The dataset includes multiple patient features associated with cancer risk.
Irrelevant columns such as Patient_ID and non-predictive attributes were removed during preprocessing.

## Methodology

The workflow of the project includes:

1. Data Preprocessing

   * Removing unnecessary features
   * Splitting dataset into training and testing sets using stratified sampling

2. Model Building

   * Applying Gaussian Naïve Bayes classifier

3. Model Evaluation

   * Classification Report (Precision, Recall, F1-score)
   * Confusion Matrix
   * Performance visualization per class

4. Visualization

   * Confusion matrix heatmap
   * Bar charts for performance metrics
   * Comparison between actual and predicted values

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Results

The model demonstrates effective performance in classifying patient outcomes, with balanced evaluation metrics across both classes. Visualizations provide clear insights into prediction behavior and model accuracy.

## How to Run

1. Install required libraries:
   pip install pandas scikit-learn matplotlib seaborn

2. Open the notebook:
   cancer_risk_nb.ipynb

3. Run all cells to reproduce results

## Project Structure

* cancer_risk_nb.ipynb → Main notebook containing full implementation
* cancer_risk1.csv → Dataset file

## Author

Suahil – AI System Engineering Student


