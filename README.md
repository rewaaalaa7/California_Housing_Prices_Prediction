# California_Housing_Prices_Prediction
Dataset :  https://www.kaggle.com/code/rewa77/california-housing-prices-prediction 

This is a repository containing code for predicting the median house value in Californian districts using various machine learning models. The data used in this repository is the California Housing Prices dataset obtained from the StatLib repository.

## Table of Contents
- [Dataset Description](#dataset-description)
- [Installation](#installation)
- [Usage](#usage)
- [Model Overview](#model-overview)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Dataset Description

The dataset consists of 20640 instances and 10 attributes. The attributes are:

1. `longitude`: A floating-point number representing the longitude of the district.
2. `latitude`: A floating-point number representing the latitude of the district.
3. `housing_median_age`: A floating-point number representing the age of the house in the district.
4. `total_rooms`: An integer representing the total number of rooms in the district.
5. `total_bedrooms`: An integer representing the total number of bedrooms in the district.
6. `population`: An integer representing the population of the district.
7. `households`: An integer representing the total number of households in the district.
8. `median_income`: A floating-point number representing the median income of the households.
9. `median_house_value`: A floating-point number representing the median value of the house in the district.
10. `ocean_proximity`: A string representing how close the district is to the ocean.

## Installation

To use this repository, you will need to have Jupyter notebook installed. You can install Jupyter notebook via pip by running the following command:

```python
pip install jupyter
```

You will also need to install the following dependencies by running the following commands:

```python
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
```

## Usage

1. Clone this repository to your local machine using https://github.com/rewaaalaa7/California_Housing_Prices_Prediction.git
2. Navigate to the root directory of the repository.
3. Open the `California_Housing_Prices_Prediction.ipynb` in Jupyter notebook.
4. Run each cell in the notebook to generate the predictions.

## Model Overview

The following machine learning models have been implemented to predict the median house value in Californian districts:

1. Linear Regression
2. Random Forest Regression
3.Support Vector Regression

## Results

The performance of each model has been measured using the following evaluation metrics:

- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

Based on the evaluation metrics, the Random Forest Regression model was the most successful at predicting median house value. However, as the repo's author notes in the conclusions section of the notebook, there is always room for improvement with further feature engineering, data cleaning, and hyperparameter tuning.
