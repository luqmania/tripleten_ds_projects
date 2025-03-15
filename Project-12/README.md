# Introduction
Rusty Bargain is a used car trading company that is developing an application to attract new buyers. In the application, researchers can quickly find out the market value of a car. Researchers have access to historical data, vehicle technical specifications, vehicle model versions, and vehicle prices. Rusty Bargain is interested in:
- prediction quality
- prediction speed
- time required to train the model

# Objectives
In this case, the researcher's task is to create a model that is able to determine the market value of a car.

# Stages
The researcher has data about clients stored in the file */datasets/car_data.csv*

*Features*
- DateCrawled — the date when the profile was downloaded from the database
- VehicleType — the type of vehicle body
- RegistrationYear — the year of vehicle registration
- Gearbox — the type of transmission
- Power — the power (hp)
- Model — the model of the vehicle
- Mileage — the distance traveled (measured in km based on a specific regional dataset)
- RegistrationMonth — the month of vehicle registration
- FuelType — the type of fuel
- Brand — the brand of the vehicle
- NotRepaired — whether the vehicle has been repaired before
- DateCreated — the date the profile was created
- NumberOfPictures — the number of vehicle images
- PostalCode — the postal code of the profile owner (user)
- LastSeen — the date of the last user activity

*Target*
- Price — the price (in Euro)

There is no information about the quality of the data, so it needs to be checked before conducting further analysis.

First, we will evaluate the quality of the data and see if there are any significant things that need to be followed up before the analysis process is carried out.

This project will consist of four stages:
- Data Overview
- Data Pre-processing
- Analysis
- Testing