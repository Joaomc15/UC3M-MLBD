# UC3M-MLBD
Repo for UC3M's ML for Business Decision Making course

**Authors**: João M. Carvalho, George Y. Fang

## Project 1: Predicting Solar Energy Production with scikit-learn

### Introduction
This assignment focuses on practicing machine learning methods and hyper-parameter tuning to determine the optimal model for a given dataset. Participants will engage in model selection, evaluation, and making predictions on unseen data.

The context of this assignment is the challenge of forecasting energy production from renewable sources, specifically wind and solar energy. Unlike traditional sources, the generation of solar and wind energy depends on weather conditions and must be accurately predicted 24 hours in advance to ensure a balanced electricity network. Accurate weather forecasting models, like GFS and ECMWF, play a crucial role in predicting variables related to these renewable energies.

Participants will use meteorological data forecasted by GFS to train a machine learning model that estimates solar energy production at a solar plant in Oklahoma. The available dataset contains 15 meteorological variables, each forecasted at 5 different times of the day and at 4 locations around the solar plant, leading to 300 input attributes in total. The dataset spans from 1994-2007, and the model’s performance will be evaluated using competition data from 2008-2009. The objective is to accurately predict the energy produced, with the last column of the dataset indicating the response variable, i.e., the energy production.

### Deliverables
* EDA
* Two Simple models (KNN and Tree) and training and evaluation process description in ipynb
* One Final Model (Using Joblib) (Advanced Model - Random Forest / SVM) and training and evaluation process description in ipynb
* One .csv file with final predictions