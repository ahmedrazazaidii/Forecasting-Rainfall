# Forecasting Rainfall

This project focuses on forecasting rainfall in Australia using a dataset sourced from Kaggle. The project involves data preprocessing, exploratory data analysis, model training, and evaluation to predict whether it will rain tomorrow based on various weather features.

## Dataset

The dataset used for this project can be found on Kaggle: [Weather Dataset](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package/data).

### Dataset Description

- **Location**: The city's name in Australia.
- **MinTemp**: The minimum temperature recorded for the day in degrees Celsius.
- **MaxTemp**: The maximum temperature reached during the day in degrees Celsius.
- **Rainfall**: Amount of rainfall measured in millimeters for the day.
- **Evaporation**: Water evaporation measured in millimeters for the day.
- **Sunshine**: Duration of bright sunshine in hours for the day.
- **WindGustDir**: The direction from which the strongest gust of wind originated during the day, given in 16 compass points.
- **WindGustSpeed**: Speed of the strongest gust of wind recorded during the day in kilometers per hour.
- **WindDir9am**: Wind direction ten minutes prior to 9 am, measured in compass points.
- **WindDir3pm**: Wind direction ten minutes prior to 3 pm, measured in compass points.
- **WindSpeed9am**: Wind speed ten minutes prior to 9 am in kilometers per hour.
- **WindSpeed3pm**: Wind speed ten minutes prior to 3 pm in kilometers per hour.
- **Humidity9am**: Humidity percentage at 9 am.
- **Humidity3pm**: Humidity percentage at 3 pm.
- **Pressure9am**: Atmospheric pressure in hectopascals at 9 am.
- **Pressure3pm**: Atmospheric pressure in hectopascals at 3 pm.
- **Cloud9am**: Cloud cover in eighths at 9 am.
- **Cloud3pm**: Cloud cover in eighths at 3 pm.
- **Temp9am**: Temperature at 9 am in degrees Celsius.
- **Temp3pm**: Temperature at 3 pm in degrees Celsius.
- **RainToday**: Indicates whether it rained today; 'Yes' if it did, 'No' if it did not.
- **RainTomorrow**: Indicates if it will rain tomorrow; 'Yes' or 'No'.

## Project Structure

### Pre-Processing

- **Handling Missing Values**: Identifying and imputing or removing missing data.
- **Outliers, Encoding, and Scaling**: Detecting outliers, encoding categorical variables, and scaling numerical features.
- **Correlation Analysis**: Creating a correlation matrix to understand feature relationships.

### Exploratory Data Analysis (EDA)

- **Class Imbalance**: Checking and addressing the imbalance in the target variable.
- **Visualizations**: 
  - Rainfall trends over the years.
  - Monthly rainfall and sunshine patterns.
  - Rainfall distribution across different cities and seasons.
  - Wind patterns at different times of the day.
  - Scatter plots showing relationships between rainfall, temperature, pressure, and humidity.
  - Distribution of categorical and numerical features.

### Feature Extraction

- **Temporal Features**: Extracting date-related features such as the month and season.

### Model Training

Several machine learning models were trained and evaluated:
- Multi-layer Perceptron (MLP)
- Logistic Regression
- Decision Trees
- Random Forest
- Gradient Boosting Machines (GBM)
- AdaBoost Classifier
- Gaussian Naive Bayes (GaussianNB)
- Extra Trees Classifier
- CatBoost Classifier

### Hyperparameter Tuning

Hyperparameters for the above models were fine-tuned to improve performance.

### Model Evaluation

The performance of each model was compared, and the best-performing model was selected based on evaluation metrics.

### Explainable AI

Understanding the model's predictions using explainable AI techniques.

## Report

A detailed report documenting the entire project is also available and provided here. It covers the data analysis, model training, evaluation, and insights derived from the study.

## Usage

To run this project, run the `Forecasting_Rainfall.ipynb` notebook. The Jupyter notebook contains all the code required for preprocessing, analysis, and model training.

