# Introduction
Sweet Lift Taxi Company has collected historical data of taxi orders at the airport. In order to attract more drivers during peak hours, the researcher needs to estimate the number of taxi orders for the next hour. The researcher needs to build a model to predict this. Note that the RMSE metric on the test set should not be more than 48.

# Objectives
In this case, the researcher's task is to create a model that is able to predict taxi drivers during peak hours.

# Stages
The researcher has data related to clients stored in the file */datasets/taxi.csv*

The steps that need to be done are as follows:
- Download the data and resample it within an hour.
- Perform data analysis.
- Train different models with different hyperparameters. The test sample should be 10% of the initial data set.
- Test the data using the test sample and provide conclusions.

*Target*
- num_orders — number of orders

There is no information regarding the quality of the data, so it needs to be checked first before doing further analysis.

First, we will evaluate the quality of the data and see if there are any significant things that need to be followed up before the analysis process is carried out.

This project will consist of four stages:
- Data Overview
- Data Pre-processing
- Analysis
- Testing