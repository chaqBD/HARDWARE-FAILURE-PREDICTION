# Hard Drive Failure Prediction Using Random Forest

## Overview
This project utilizes machine learning techniques, specifically Random Forest, to predict hard drive failures. The notebook includes data loading, preprocessing, exploratory data analysis, model building, and hyperparameter tuning using Hyperopt.

## Requirements
The following libraries are required to execute the notebook:
- Python 3
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- hyperopt

## Data
The dataset (`harddrive.csv`) includes various hard drive attributes used to predict failures. Make sure the dataset is located in the correct directory as referenced in the notebook (`../input/hard-drive-test-data/harddrive.csv`).

## Steps Covered in Notebook

### 1. Data Loading and Preprocessing
- Importing libraries
- Loading the dataset
- Handling missing values by removing columns with all missing entries

### 2. Exploratory Data Analysis (EDA)
- Basic exploration such as counting unique hard drives and models

### 3. Model Building
- Splitting data into training and testing sets
- Implementing Random Forest without hyperparameter tuning initially

### 4. Hyperparameter Tuning
- Utilizing Hyperopt for tuning Random Forest parameters
- Cross-validation to evaluate the model's performance

## Usage
1. Ensure all required libraries are installed.
2. Run the notebook step-by-step for best results.

## Evaluation
Model performance is evaluated using:
- Classification report
- Confusion matrix

## Notes
- This notebook is suitable for environments like Kaggle, where data directories follow specific structures.
- Adjust file paths as necessary when running in different environments.

