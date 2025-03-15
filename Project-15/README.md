# Introduction
A supermarket chain called Good Seed wanted to see if Data Science could help them comply with the law by ensuring that they were not selling age-restricted products to underage customers. The researchers were asked to conduct an evaluation by considering the following:
- The stores of this franchise are equipped with cameras at the checkout area that will display a signal when someone purchases an age-restricted product
- Computer vision methods can be used to determine a person's age from a photo
- The researcher's task is to build and evaluate a model to verify a person's age

To begin working on this task, the researcher will have a collection of photos of people with an indication of their age.

The goal of this project is to build a machine learning model using regression that determines the approximate age of a person from a photo. There is a collection of photos of people that show their age. Analysis is carried out on the collection of photos of people with an indication of age using computer vision using ResNet and the Keras library.

# Objectives
In this case, the researcher's task is to create a model that is able to predict the age of a collection of photos of people using computer vision using ResNet and the Keras library.

# Stages
The researcher has a dataset stored in the file */datasets/faces/*

A final_files folder with 7.6k photos. A labels.csv file with labels, consisting of two columns: file_name and real_age