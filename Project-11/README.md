# Introduction
An insurance company called "Sure Tomorrow" wants to solve some problems with the help of machine learning. You are asked to evaluate the possibilities.

- Task 1: Find clients who are similar to certain client criteria. This task will make it easier for the company to market.
- Task 2: Predict whether new clients are likely to take out insurance claims. Is the model's prediction better than the dummy model's prediction?
- Task 3: Predict the amount of insurance claims that new clients are likely to receive using a linear regression model.
- Task 4: Protect clients' personal data without damaging the model from the previous task. It is very important to develop a data transformation algorithm that can prevent misuse of clients' personal information if the data falls into the wrong hands. This is called data hiding or data obfuscation. However, the data protection procedure also needs to be considered so that the quality of the machine learning model does not decrease. Here, you don't need to choose the best model, just prove that your algorithm works accurately.

# Objectives
This time, the researcher has the following objectives:
1. Find clients that are similar to certain client criteria
2. Predict whether new clients are likely to take out insurance claims and whether the model's predictions are better than the dummy model's predictions.
3. Predict the amount of insurance claims that new clients are likely to receive using a linear regression model.
4. Protect client personal data without affecting the quality of the machine learning model used.

# Stages
The researcher has data related to clients stored in the file */datasets/insurance_us.csv*

There is no information regarding the quality of the data, so it needs to be checked first before further analysis.

First, an evaluation of the data quality will be carried out and see if there are any significant things that need to be followed up before the analysis process is carried out.

This project will consist of four stages:
- Data Overview
- Data Pre-processing
- Analysis
- Testing

Related to ML needs:
*Feature*: gender, age, salary, and number of family members of the insured
*Target*: the amount of insurance benefits received by the insured over the past five years