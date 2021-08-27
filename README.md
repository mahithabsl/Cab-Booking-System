# Cab Booking System
- Objective of this project is to combine historical usage pattern along with the open data sources like weather data to forecast cab booking demand in a city. 
- Predict the total count of cabs booked in each hour covered by the  test set, using the information available prior to the booking period

### Dataset Description ###

Please find the descriptions of the columns present in the dataset as below:
- datetime - hourly date + timestamp
- season - spring, summer, autumn, winter
- holiday - whether the day is considered a holiday
- workingday - whether the day is neither a weekend nor holiday
- weather - Clear , Cloudy, Light Rain, Heavy temp - temperature in Celsius
- atemp - "feels like" temperature in Celsius
- humidity - relative humidity
- windspeed - wind speed
- Total_booking - number of total booking

### Performed ###
1) Feature Engineering
2) Outlier Analysis
3) Correlation Analysis
4) Data Visualization
5) Regression analysis using various models (Random Forest Regressor, Ada Boost Regressor, Bagging Regressor,SVR, and K-Neighbors Regressor)
6) Hyperparameter tuning using GridCV

### Run on Jupyter ###
```
git clone https://github.com/mahithabsl/Cab-Booking-System
cd Cab-Booking-System
jupyter notebook
```
