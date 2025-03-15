# Introduction
The researcher will conduct data analysis on a Chicago Taxi company. For this, the researcher has 3 data sets to work with. The first contains the company name and the number of trips taken by the company's taxis. The second contains the name of the dropoff location (neighborhood) and the average number of trips to that neighborhood. The first and second will be used for the main analysis. The third data set contains the date and time, weather conditions, and trip duration from the Loop neighborhood to O'Hare International Airport on Saturdays. This dataset will be used for hypothesis testing.

# Objectives
Prepare a report for Zuber, a new ride-sharing company launched in Chicago, to identify patterns that determine passenger preferences and the impact of external factors on trips.

Test the following hypotheses:
The average trip duration from the Loop neighborhood to O'Hare International Airport changes on rainy Saturdays.

# Stages
The data about taxi companies, average trips, and weather conditions are in the files:

*project_sql_result_01.csv* The file contains the following data:
- company_name: name of the taxi company
- trips_amount: number of trips by taxi company in November on November 15-16, 2017.

*project_sql_result_04.csv* The file contains the following data:
- dropoff_location_name: Chicago neighborhood where trips ended
- average_trips: average number of trips that ended in each neighborhood in November 2017.

*project_sql_result_07.csv* The file contains the following data:
- start_ts: departure time and date
- weather_conditions: weather conditions when the trip started
- duration_seconds: trip duration in seconds

There is no information about the quality of the data, so it needs to be checked before doing further analysis.

First, an evaluation of the data quality will be carried out and see if there are any significant things that need to be followed up before the analysis process is carried out, including:
- Converting data into the required data type
- Finding and eliminating errors in the data

This project will consist of four stages:
- Data Overview
- Data Pre-processing
- Analysis Process
- Hypothesis Testing