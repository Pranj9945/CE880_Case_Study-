# -CE880_Case_Study-

# Postnatal Depression Prediction

This repository contains code for analyzing and predicting postnatal depression based on a dataset stored in an Excel file. The code is written in Python and utilizes libraries such as pandas, matplotlib, seaborn, numpy, scikit-learn, XGBoost, and neural networks.

## Setup

To run the code, make sure you have Python installed on your system along with the required libraries mentioned in the `requirements.txt` file.

```bash
pip install -r requirements.txt

Usage

Upload the Excel file named data_PostNatal.xlsx containing the dataset. The file is then stored in session storage.
The code reads the Excel file into a pandas DataFrame and performs various data exploration and preprocessing steps.
Missing values are filled using appropriate methods.
Data visualization is performed using seaborn and matplotlib to gain insights into the dataset.
One-hot encoding is applied to categorical features.
The dataset is split into training, validation, and testing sets.
Feature scaling is applied using StandardScaler.
Several machine learning models are trained, including Support Vector Machine (SVM), Random Forest, k-Nearest Neighbors (KNN), XGBoost, Multi-layer Perceptron (MLP), and Decision Tree.
Model evaluation metrics such as accuracy, precision, recall, F1-score, ROC-AUC curve, and confusion matrix are calculated.

Files

data_PostNatal.xlsx: Input dataset file.
postnatal_depression_prediction.ipynb: Jupyter Notebook containing the code.

This README provides an overview of the code, its usage, and the files included in the repository.

