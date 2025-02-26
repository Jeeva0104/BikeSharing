# Linear-Regression-Bike-Sharing-Assignment

# General Information

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

# Conclusion

### Model Equation for Predicting Bike Rentals (`cnt`)

The regression equation for predicting bike rentals (`cnt`) is:

\[
cnt = (0.5102 \times temp) + (-0.1496 \times hum) + (-0.1820 \times windspeed) + (0.1092 \times season\_summer) + (0.1540 \times season\_winter) + (-0.0548 \times weather\_mist\_cloud) + (-0.2389 \times weather\_light\_snow\_rain) + (0.0680 \times yr\_q3) + (-0.0745 \times holiday) + (0.0182 \times workingday) + (0.2292 \times yr\_2019) + (0.2119)
\]

#### **Variable Descriptions:**
- `temp` = Normalized temperature
- `hum` = Normalized humidity
- `windspeed` = Normalized wind speed
- `season_summer`, `season_winter` = One-hot encoded season variables
- `weather_mist_cloud`, `weather_light_snow_rain` = One-hot encoded weather conditions
- `yr_q3` = Indicator for third quarter of the year
- `holiday` = Whether the day is a holiday (1 = Yes, 0 = No)
- `workingday` = Whether the day is a working day (1 = Yes, 0 = No)
- `yr_2019` = Indicator for the year 2019
- The constant term is **0.2119**


