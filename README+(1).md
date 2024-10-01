# Predicting Bike Share Demand
> This repository contains the code and analysis for predicting bike rental demand using a dataset of bike-sharing data. The project involves data loading, exploratory data analysis (EDA), feature selection, model building, and evaluation.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes, a US bike-sharing provider, has experienced a significant decline in revenue due to the COVID-19 pandemic. To recover and thrive, they aim to understand the factors influencing bike share demand and develop a strategic plan to meet customer needs once the pandemic subsides.
- The primary business problem is to identify the key variables affecting bike share demand in the American market. This information will enable BoomBikes to:
Optimize their business strategy to meet anticipated demand levels.
Understand the demand dynamics in new markets.
Gain a competitive advantage in the bike-sharing industry.
- Data set used contain details of weather, Season, Holiday, Working day, week day, month, year etc... and attached it to this repositary for refrence.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Seasonal Influence: Bike rentals are lowest in spring and show an upward trend from April to September.
- Weather Conditions: Clear weather conditions lead to the highest number of bike rentals, followed by partly cloudy conditions.
- Weekday vs Weekend: There is a slightly higher median of bike rentals on weekdays compared to weekends.
- Yearly Trends: There is an increase in median bike rentals from 2018 to 2019.
- Dimensionality Reduction: The workingday and weekday variables were dropped as they did not significantly impact bike demand, improving model performance.
- Key Factors: Temperature, windspeed, weather conditions, and season significantly influence bike rental demand.
- Model Accuracy: The linear regression model accurately predicts bike rental demand, with residual analysis and assumption checks confirming the model’s reliability.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- matplotlib: 3.8.0
- numpy: 1.26.4
- pandas: 2.1.4
- seaborn: 0.12.2
- statsmodels: 0.14.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by AI/ML course in UPGRAD

## Contact
Created by [@Bhaskara-patnaik] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
