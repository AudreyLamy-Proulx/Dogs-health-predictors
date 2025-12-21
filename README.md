# Dog Health Status Prediction

A project to predict dog health status based on demographic, lifestyle, and owner characteristics.

## Overview

This project analyzes factors that influence pet dog health status using logistic regression. The analysis is based on data from a research study on demographic changes across the lifespan of pet dogs.

## Data Source

Data from: **Wallis LJ, Szabó D, Erdélyi-Belle B, Kubinyi E. Demographic Change Across the Lifespan of Pet Dogs and Their Impact on Health Status.** Front Vet Sci. 2018 Aug 23;5:200. doi: 10.3389/fvets.2018.00200.

## Research Question

**What are the best predictors of dog health?**
   - Hypothesized predictors: Sex, Breed, Food, Owner age, Life events, Ratio weight/height, Training level

## Files

- `health_status_prediction.ipynb` - Main analysis notebook with EDA, feature engineering, and model training
- `config.py` - Variable label mappings for data encoding
- `Data_Sheet_1_Demographic_Change_Across_the_Lifespan_of_Pet_Dogs_and_Their_Impact_on_Health_Status.XLSX` - Dataset

## Key Features

- **Data preprocessing**: Handling outliers, feature engineering (weight/height ratio, training level composite)
- **Modeling**: Logistic regression
- **Evaluation**: confusion matrices, metric scores
- **Statistical analysis**: P-values and significance testing using statsmodels (to-do)

## Requirements

- Python 3.9+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- statsmodels
- openpyxl (for reading Excel files)

## Usage

1. Open `health_status_prediction.ipynb` in Jupyter Notebook or JupyterLab
2. Run the cells sequentially to perform the analysis
3. The notebook includes:
   - Data loading and exploration
   - Feature engineering
   - Model training and evaluation
   - Results visualization

## Results

The models identify key predictors of dog health status, including age, owner characteristics, and lifestyle factors. Model performance metrics and feature importance are displayed in the notebook.
