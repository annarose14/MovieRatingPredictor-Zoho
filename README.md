# MovieRatingPredictor-Zoho
A machine learning project to analyze and predict movie audience ratings using data from Rotten Tomatoes. This pipeline cleans, preprocesses, and models the data with advanced regression techniques to deliver insights and predictions. The project includes visualizations, feature engineering, and model evaluation metrics.








# Rotten Tomatoes Movies Analysis and Prediction

This project is a machine learning pipeline to analyze and predict the audience ratings of movies using a dataset from Rotten Tomatoes. The pipeline preprocesses the data, applies feature transformations, and trains a regression model to predict the audience rating.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Requirements](#requirements)
4. [Setup](#setup)
5. [Usage](#usage)
6. [Evaluation Metrics](#evaluation-metrics)
7. [Results](#results)
8. [Visualizations](#visualizations)
9. [Contributing](#contributing)

## Project Overview

The goal of this project is to develop a regression model that predicts the audience ratings of movies based on features such as genre, directors, runtime, tomatometer scores, and more. The pipeline leverages preprocessing techniques and machine learning algorithms, primarily focusing on the Random Forest Regressor.


## Features

- Data Cleaning: Handles missing values and drops irrelevant columns.
- Data Preprocessing:
  - Label encoding for categorical variables.
  - One-hot encoding for categorical features.
  - Imputation for missing data.
- Machine Learning Pipeline:
  - Preprocessor combining numerical and categorical transformations.
  - Random Forest Regressor for predictions.
- Metrics Evaluation: Includes MAE, MSE, RMSE, and R² Score.
- Visualizations:
  - Missing data heatmap.
  - Distribution plot for the target variable.
  - Correlation heatmap.

## Requirements

To run this project, ensure the following libraries are installed:

- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- openpyxl (for reading Excel files)

## Setup

1. Clone this repository:

    ```bash
    git clone https://github.com/your-username/rotten-tomatoes-analysis.git
    cd rotten-tomatoes-analysis
    ```

2. Install the required libraries:

    ```bash
    pip install -r requirements.txt
    ```

3. Place the dataset (`Rotten_Tomatoes_Movies3.xls`) in the project directory.


## Usage

1. Run the main script:

    ```bash
    python main.py
    ```

2. View results for model evaluation metrics and visualizations.

## Evaluation Metrics

The model is evaluated using the following metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**


## Results

The following results were observed after training the Random Forest Regressor:

- Mean Absolute Error: 11.438245881635146
- Mean Squared Error: 216.68686982916415
- Root Mean Squared Error: 14.720287695190068
- R² Score: 0.4749722527951892



## Visualizations

The project includes the following visualizations:

1. Heatmap showing missing data.
2. Distribution plot of the target variable (`audience_rating`).
3. Correlation heatmap of numerical features.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature/fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add new feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.



