Time Series Forecasting Using FbProphet

This project demonstrates how to perform time series forecasting using Facebook's Prophet library. 
The notebook guides you through loading and preprocessing data, fitting a time series model, and 
making future predictions with an emphasis on ease of use and effectiveness for forecasting tasks.

Dataset
Dataset Used: airline_passengers.csv
Data Description: The dataset contains monthly totals of international airline passengers from 1949 
to 1960. It includes a date column (ds) and a corresponding passenger count column (y).

Project Workflow

Installation of Dependencies:
The project uses fbprophet (now known as Prophet) and other essential libraries like pandas, numpy, and seaborn.

Dependencies are installed using:

        !pip install pystan
        !pip install fbprophet
        
Data Loading and Preprocessing:

The dataset is loaded and preprocessed to fit the requirements of the Prophet model.
The date column is renamed to ds and the target variable to y.
The date column is converted to a datetime format.

Model Initialization and Fitting:

A Prophet model is initialized and fitted on the preprocessed data.
Future dates are generated for forecasting, and the model predicts future values.

Prediction and Visualization:

The model's predictions are plotted to visualize the forecast.
Additional components like trends and weekly patterns are also visualized.
Cross-Validation and Performance Evaluation:

The model's performance is evaluated using cross-validation.
Performance metrics such as RMSE are calculated and visualized to assess the model's accuracy.


To run the project, ensure you have the following dependencies installed:

      pip install pystan
      pip install fbprophet
      pip install pandas numpy seaborn
