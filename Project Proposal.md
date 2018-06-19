# Capstone Project 1 Proposal

## Title 
Air Quality (PM2.5) Prediction for Major Cities of China

## Problem
In recent years, air pollution has become an increasingly severe problem in China due to rapid industrialization and high energy consumption. The thick haze and smog, characteristic of unhealthy air condition, raise intense public concerns and media attentions, as it has been linked to the increased occurrence of various respiratory diseases and resident mortality rates.
According to reports, PM2.5 is the main pollutant accountable for at least two thirds of the severely polluted days in Chinese major cities. Different from other groups of air pollutants, PM2.5 (ultrafine particles less than 2.5 microns in diameter) is small in size, high in surface area, easily transported, and deeply penetrated into the human body, therefore posting a significant threat to human health.
China has started the PM2.5 monitoring and reporting program in major cities since early 2013, and has extended to 388 cities by 2015. However, besides live monitoring and reporting, a PM2.5 prediction system is strongly desired. With accurate predictions, government and citizens can plan ahead and take actions accordingly.

## Who might care
This model is beneficial to people at all levels, ranging from Chinese government, local organizations to individual citizens. Government can use this model to predict air quality, provide outdoor activity guideline for adults and children and issue appropriate warnings in advance. Local organizations can benefit from the model prediction to plan outdoor events, schedule emergency facility shutdowns when necessary. Individual citizens can also consult this predictive model to plan their commute choices, better schedule their daily outdoor activities to take full advantage of the clear sky hours and wear protective mask and clothings.
A predictive model with good accuracy will enable people to plan ahead accordingly, reducing the hassles and economical loss due to last minute changes as well as limiting the exposure to unhealthy air.

## Dataset
PM2.5 data will be acquired from UCI Repository at https://archive.ics.uci.edu/ml/datasets/PM2.5+Data+of+Five+Chinese+Cities and https://archive.ics.uci.edu/ml/datasets/Beijing+PM2.5+Data. The first dataset contains hourly PM2.5 measurements for five Chinese cities (Beijing included), along with many other meteorological readings collected during the period of 2010-2015. These meteorological readings include dew point, temperature, humidity, pressure, combined wind direction, cumulated wind speed and hourly precipitation etc. The second dataset contains similar measurements for city Beijing alone during the period of 2010-2014. In this project, we will focus on the first dataset, but also taking into consideration the ‘cumulated hours of snow’ and ‘cumulated hours of rain’ for Beijing from the second dataset. Besides weather conditions, different demographic characteristics may play a role in shaping up the air quality of the city. Therefore, the demographic data will be acquired from National Bureau of Statistics of China at http://www.stats.gov.cn/english/statisticaldata/AnnualData/ and taken into consideration. 

## Approach
Our approach is outlined below (subject to changes and updates):
1. Data wrangling: 
  data acquisition from excels files;
  clean up missing data and outliers;
  incorporate additional data from the second dataset.
2. Exploratory data analysis:
  verify data consistency by examining data collected at various locations for each city; 
  use statistical EDA and visual EDA to identify daily, weekly, seasonal, and yearly trends of PM2.5;
  use inferential statistics an visual EDA to identify the correlation between PM2.5 and weather conditions, rank the weather parameters accordingly;
  use statistical EDA and visual EDA to run cross-city comparisons on PM2.5.
3. Machine learning modeling:
  Model the correlation between PM2.5 and weather data based on data from 2010-2014, and use the model to predict year 2015;
  Model the correlation between PM2.5 and weather data based on data from four cities, and use the model to predict the fifth city; 
  Improve the model according to the insights from 1) and 2). Take into consideration the demographic characteristics when necessary.
4. Visualization, summary and outlook:
  Visualize important trends and findings using matplotlib and Seaborn;
  Compile all approaches and findings into report, slides and code package, upload to Github repo;
  Specify the limitation and future improvement directions for the model.

## Deliverables
  A report on the project;
  A slide deck on the project;
  Source codes on data acquisition, data wrangling, exploratory data analysis and machine learning model build.
