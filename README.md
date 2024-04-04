# Taxi Fare Prediction

This project aims to predict taxi fares based on various factors using a Random Forest Regressor.

## Dataset

The dataset contains information about different taxi rides and their respective fares.
https://www.kaggle.com/datasets/raviiloveyou/predict-taxi-fare-with-a-bigquery-ml-forecasting/code

## Analysis

The analysis includes:

- Checking the dimensions of the data
- Checking unique classes in the label
- Checking the frequency of the classes in the dataset
- Viewing the first 5 rows of input features
- Making a boxplot to view the distribution in the data
- Plotting the Pearson correlation for our input features
- Identifying highly correlated input features
- Creating a random forest regressor
- Training the regressor and viewing estimates for prediction error
- Using k-fold cross-validation to measure performance

## Results

The performance of the model is evaluated using Mean Squared Error.

## Usage

To run the project, open the `taxi_fare.ipynb` notebook and execute the cells.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- sklearn
