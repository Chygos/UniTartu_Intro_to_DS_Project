![page_image](images/page_design.png)

# [Forecasting Household Hourly Electricity Consumption Rate](https://www.kaggle.com/competitions/predict-electricity-consumption)

## Description

This repository contains a group project for the Introduction to Data Science course of the University of Tartu.
Project will be undertaken by 

- Wei-Chieh Wang
- Patricia Kika Obinwanne
- Chigozie Nkwocha

## Introduction

Since the Russian invasion on Ukraine, energy, rent and food costs have skyrocketed. World economies are now faced with record high losses in revenue. Workers are now being laid off because their employers are no longer capable of paying their salaries in a bid to cut costs. Small businesses as well, are now forced to close due to huge operational costs. As a result, electricity consumers around the world are now seeking for better ways of reducing electricity costs and conserving energy.

Similarly, the excessive use of electricity causes an increase in the environmental carbon footprint. Enefit, one of the largest energy companies in the Baltic countries is strategizing on a better approach to help their customers achieve their goal while preserving the environment from excess release of carbon. One possible strategy is to forecast energy consumption for a household and optimise its energy usage by controlling smart devices in such a way that they minimise energy cost and the environmental footprint of consumption. Another is the use of solar panels and other forms of cheaper electricity.

## Aim
In this project, we aim to develop a predictive model capable of forecasting electricity consumption for a household for the next 7 days. We intend that this project will enable consumers understand their electricity usage and identify the hour(s) of the day when usage is high or least. 

## Objectives
- Use Data visualisation to understand electricity consumption of household
- Develop at least two machine learning models to predict electricity consumption
- Compare classical time series model (ARIMA) with machine learning model
- Forecast electricity consumption for the next 7 days

## Data
To accomplish this, we will use a historical dataset containing a household's hourly electricity consumption used between Sept 1st, 2021 to 24th August, 2022. A holdout test set is kept to be used for forecasting. The historical data contains 8,592 hourly electricity consumption, with 168 hourly consumption as test set [[link]](https://www.kaggle.com/competitions/predict-electricity-consumption/data).

### Variables

Variable Name | Definition
--------------|-------------
time |definition of example_id
temp | Air Temperature (°C)
dwpt | The dew point in °C
rhum | The relative humidity in percent (%)
prcp | The one hour precipitation total in mm
snow | The snow depth in mm
wdir | The wind direction in degrees (°)
wspd | The average wind speed in km/h
wpgt | The peak wind gust in km/h
pres | The sea-level air pressure in hPa
coco | The weather [condition code](https://dev.meteostat.net/formats.html#weather-condition-codes)
el_price | the electricity price in Estonia on that hour (€/kWh)
consumption | the electricity consumption (kWh)

## Results

### Model Evaluation

## Forcasting






