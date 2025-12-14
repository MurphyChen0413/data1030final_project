# Predicting Used-Car Prices with Machine Learning

This project develops a supervised machine learning pipeline to predict used-car prices in the UK market. Using a large public dataset of online vehicle listings, the project compares linear and nonlinear models and applies modern interpretability techniques to understand the drivers of price variation.

## Project Structure
Project Structure
├── data/        # Raw and preprocessed datasets
├── figures/     # Generated plots and visualizations
├── results/     # Model predictions and evaluation outputs
├── report/      # Final project report (PDF)
├── src/         # Source code and analysis scripts
├── .gitignore
├── LICENSE
└── README.md


## Data

The dataset used in this project is the **DVM-CAR** dataset, a public collection of used-car listings from UK online advertisements.  
If the dataset is too large to be stored directly on GitHub, it can be obtained from:

> *(Insert dataset link here if needed)*

## Methods

The modeling pipeline includes:
- Data cleaning and preprocessing
- Handling missing values and high-cardinality categorical variables
- Feature encoding and scaling using scikit-learn pipelines
- Model training with Elastic Net, KNN, Random Forest, and XGBoost
- Hyperparameter tuning with GridSearchCV
- Model evaluation using MAE, RMSE, and R²
- Model interpretability using SHAP

## Environment

This project was developed using:

- Python 3.10+
- numpy
- pandas
- scikit-learn
- xgboost
- matplotlib
- seaborn
- shap

A reproducible environment can be created using the provided YAML file.

## Results

XGBoost achieved the best overall predictive performance, substantially outperforming a baseline model and linear regression approaches. Model interpretability analyses highlight mileage, vehicle age, engine size, and brand as the most influential predictors of price.

## Author

Mofei Chen  
DATA 1030: Hands-on Data Science
