# UCI Heart Disease ETL Pipeline

## Project Overview
This project demonstrates a complete ETL (Extract, Transform, Load) pipeline for the UCI Heart Disease dataset using Python. The goal is to preprocess and transform the raw dataset into a clean, machine-learning-ready format.

## Dataset
The dataset used is the **UCI Heart Disease Cleveland** dataset, which contains patient medical information used to predict the presence of heart disease.

## Features
- Loads data directly from the UCI repository.
- Handles missing values in numeric and categorical columns.
- Converts the target variable into binary classification (presence or absence of heart disease).
- Encodes categorical variables using one-hot encoding.
- Scales numerical features.
- Builds a reusable preprocessing pipeline using Scikit-learn.
- Exports the processed dataset and pipeline for future machine learning tasks.

## Files in this Repository
- `heart_disease_etl.ipynb`: Jupyter Notebook with step-by-step ETL pipeline implementation.
- `heart_disease_processed.csv`: The processed dataset saved as CSV after ETL.
- `heart_disease_preprocessor.pkl`: Pickled Scikit-learn pipeline for data preprocessing.

## How to Use
1. Open the Jupyter Notebook `heart_disease_etl.ipynb` to explore the code and pipeline.
2. Use the pipeline (`heart_disease_preprocessor.pkl`) to transform new data in the same format.
3. Use the processed dataset for training or evaluating machine learning models.

## Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- joblib
- Jupyter Notebook

## Installation
You can install required libraries via pip:

