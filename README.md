# Bike_Sharing_Demand_Prediction

Hello, all. We have worked on the Seoul Bike Sharing dataset for the time period Dec 2017 - Nov 2018. The dataset contains information of various environmental conditions like the temperature, the dew point temperature, humidity, visibility, solar radiation, rainfall and the snowfall levels. 

It also contains informations on the type of the day. As in it tells whether the day was functional or not and whether it was a public holiday or not.

We have tried to work on the data and get three things out of it:

a. We have tried to generate insights through the EDA process

b. We have tried to analyse the kinds of relations between the demand of bikes and environmental changes

c. And most importantly, we have tried to build a machine learning predictive model that helps us predict the number of bikes that could be in demand on a given hour of a day when provided with certain attributes of the day.

We hope that you like the project and we would like to listen to your thoughts on it. You can reach us at shivchirag1997@gmail.com and er.tapomay@gmail.com

## Problem Statement

The dataset is of Seoul's public bike rental service called "Ttareungi," also known as Seoul Bike. It has become one of the capital city's most popular public transport systems by being used more than 100 million times since the service was launched in December 2015, as reported in early 2022. The popularity however has posed the challenge of keeping the bikes available as and when the demand for them rises. 

So our goal is to identify the variables that have a say in the demand of the bikes and then build a model that helps predict the demands as and when the climatic conditions change.

## Dataset

**Date :** Date of the rental agreement

**Rented Bike Count :** Number of bikes rented

**Hour :** Hour of the day

**Temperature(°C) :** Temperature 

**Humidity(%) :** Humidity measure

**Wind speed(m/s) :** Wind speed

**Visibility (10m) :** Visibility measure

**Dew point temperature(°C)	:** Dew point temperature measure

**Solar Radiation (MJ/m2)	:** Solar Radiation measure

**Rainfall(mm) :** Rainfall in mm

**Snowfall(cm) :** Snowfall measure

**Seasons :** Season

**Holiday :** Whether a holiday or not

**Functioning Day :** Whether a functional day or not

## Data Cleaning and Wrangling

From the first looks, the dataset looks a lot cleaner than most ones we usually work with. It has no null values and no duplicate values.

We have 8760 datapoints, 13 independent variables and one dependent variable, Rented Bike Count.

Most of the variables are numeric. Only four of the 14 are object datatypes.

We have converted the Date column into Datetime datatype from object datatype. We have also added some new columns which we believe may be useful during our EDA process. The columns included are Month and Day to depict the month and the day of the week.

## EDA Process

We did an extensive analyis of the dataset using charts like heatmap, barplot, scatterplot, line plot and pie chart. These were used to do multiple univariate, bivariate and multivariate analysis. For the insights generated, please look at the presentation.

## Predictive Model

We created a predictive model with an R2 score of 0.93. The model uses an advanced gradient boosting regression algorithm with the hyperparameters tuned using GridSearchCV cross validation technique. 

For more on the process and the results, would recommend to go through the project notebook uploaded and/or the final presentation prepared.
