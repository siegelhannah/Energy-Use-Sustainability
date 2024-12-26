# Energy Usage/Production and Sustainability: a Personal Project

## Description

This project analyzes energy production and consumption data across countries to obtain sustainability insights. The project includes:
1. Data cleaning/preprocessing
2. Exploratory data analysis and visualization to identify trends
3. Inference/hypothesis testing and confidence quantification
4. Prediction (both quantitative/continuous prediction and categorical classification) using various models, optimized using k-fold cross validation for best fit, predictive ability, and lowest error


## Installation Instructions

To run this project, follow these steps:

1. Clone the repository:
   git clone https://github.com/siegelhannah/Energy-Use-Sustainability.git
2. Navigate to the project directory:
   cd Energy-Use-Sustainability
4. Install required Python packages
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter

## Usage

1. Open the Jupyter Notebook:
   jupyter notebook Energy-Use-Sustainability.ipynb
2. Follow the notebook to:
   - Load and preprocess the dataset.
   - Visualize trends in energy and emissions data
   - Perform subset selection, hyperparameter tuning, and k-fold cross validation of predictive models, and train & evaluate the models
   - Predict attributes of countries like CO2 emissions based on energy usage
  

## Files Overview

This repository contains the following files:

- Energy-Use-Sustainability.ipynb: Jupyter Notebook containing the implementation of the KNN classifier, data preprocessing, and evaluation.
- global-data-on-sustainable-energy.csv: Kaggle dataset containing temporal and country-level information on energy production/consumption/sources, and other metrics like GDP, CO2 emissions, etc.
