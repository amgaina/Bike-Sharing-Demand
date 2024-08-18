# Bike-Sharing-Demand Prediction Project

## Overview

This project focuses on predicting bike rental demand based on historical usage patterns and external factors such as weather, time of day, and seasonal variations. By leveraging various machine learning models, the goal was to create an accurate and reliable predictive model that can assist bike-sharing companies in optimizing their services and resources.

The final model achieved approximately 90% accuracy on unseen data, demonstrating its effectiveness in capturing the underlying factors influencing bike rental demand.

## Data

The dataset includes historical bike rental data, along with associated features such as:

- **Datetime**: Hourly timestamps for the bike rental records.
- **Season**: Season of the year (spring, summer, fall, winter).
- **Holiday**: Whether the day is a holiday.
- **Functioning day**: Whether the day is a working day.
- **Weather**: Weather situation (clear, misty, rainy, etc.).
- **Temperature**: Hourly temperature in Celsius.
- **Humidity**: Hourly humidity percentage.
- **Windspeed**: Hourly wind speed.
- **Hour**: Length of time bike was rented
- **Rented Bike Count**: Total count of bike rentals (target variable).
- **Dew point temperature(°C)**
- **Solar Radiation (MJ/m2)**
- **Rainfall(mm)**
- **Visibility (10m)**
- **Snowfall (cm)**

## Models Used

The project explored various machine learning models to predict bike rental demand. The models evaluated include:

1. **Linear Regression**
2. **Lasso Regression**
3. **KNeighborsRegressor**
4. **Support Vector Regressor (SVR)**
5. **XGBRegressor**
6. **Decision Tree Regressor**
7. **RandomForestRegressor**
8. **ExtraTreeRegressor**
9. **GradientBoostingRegressor**
10. **MLPRegressor (Multi-layer Perceptron)**
11. **LightGBM Regressor**

## Model Performance

After extensive experimentation, the **XGBRegressor** achieved the best performance with approximately 90% accuracy on the unseen test data. This model was selected based on its balance between predictive accuracy and generalization capability.

## How to Run the Project

1. **Clone the repository**:
   ```bash
   git clone https://github.com/amgaina/Bike-Sharing-Demand.git
   cd Bike-Sharing-Demand
   ```
2. **Clone the repository**:

   ```bash
   pip install -r requirements.txt

   ```

3. Navigate to the notebooks/ directory and open the relevant notebook to explore data, train models, and evaluate performance.

## Conclusion

In the Bike Sharing Demand project, we successfully developed and trained a predictive model to estimate the number of bike rentals based on various features such as weather conditions, time of day, and seasonal factors. Through rigorous data preprocessing, feature engineering, and model selection, we were able to capture the underlying patterns and trends that influence bike-sharing demand.

Our final model demonstrated strong predictive performance, as evidenced by its ability to generalize well to unseen data, achieving 89.61% accuracy score on the test set and 97.5% on the training set. We explored different types of regression models, including linear regression, decision trees, and ensemble methods, ultimately selecting XGBRegressor or Light-GBM due to its superior accuracy and ability to handle the complexity of the dataset.

## Acknowledgements

1. The dataset is taken from Kaggle.

Feel free to adjust the codes as needed and play around it.
