# Project Name
Shared bikes demand

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This project builds a multiple linear regression model to predict the demand for shared bikes based on various environmental and situational factors.

- The project analyzes data from BoomBikes, a U.S. bike-sharing provider, to understand factors influencing bike rentals and improve business strategies post-pandemic.

- The goal is to identify significant predictors of bike demand to optimize operations, cater to market needs, and regain revenue after a downturn.

- The dataset includes daily records of bike rentals, weather conditions, holidays, and other situational data provided by BoomBikes.


## Conclusions
- Demand is higher in 2019 compared to 2018, on working days, and during favorable weather conditions.
Wind speed negatively impacts demand, while spring sees relatively high rentals.

- Significant factors influencing bike demand include the year (yr), working days (workingday), wind speed (windspeed), spring season (season_spring), Saturdays (weekday_Saturday), and light rain (weathersit_Light Rain).

- The regression model achieved an R² of 81% and an Adjusted R² of 80% on the test data, indicating that it explains approximately 81% of the variance in bike demand.


## Technologies Used
'pandas': '2.2.2',
 'numpy': '1.26.4',
 'matplotlib': '3.8.0',
 'seaborn': '0.13.2',
 'sklearn': 'scikit-learn: sklearn'

<
## Contact
Created by [@githubusername] - feel free to contact me!


