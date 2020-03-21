# Occupancy Detection
Occupancy of an office room prediction 

### Introduction:-

Previous studies showed that knowing occupancy certainly can save energy in the control system of building. In
this regard, occupancy detection has a significant role in many smart building applications such as heating, cooling,
ventilation (HVAC) and lighting system.

### About the dataset:-

The data set can be loaded from the following link: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+
It is a zip file consisting of three data sets that were used in the evaluation of the accuracy of predicting the occupancy of the room, one for training, and two for testing the models considering the office door opened and closed during occupancy. 
The attributes in the datasets are date on which the following physical parameters where observed and recorded, Temperature of the room in Celsius, Relative Humidity in %, Light in Lux, CO2 in ppm, Humidity Ratio, derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air and Occupancy-0 or 1, 0 for not occupied, 1 for occupied status.
Occupancy is the target value to be used for prediction.

### Results that were obtained with this project: 
I've trained the model using Neural networks and Logistic regression, once with just one variable and again with two variables.
It was observed that Neural networks gave an accuracy of 98.84% and Logistic regression gave an accuracy of 98.64%. 
Both the algorithms gave pretty good accuracies. Let's dive in and see how this was achieved.
