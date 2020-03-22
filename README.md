# Occupancy Detection
Occupancy of an office room prediction 

### Introduction:-

Previous studies showed that knowing occupancy certainly can save energy in the control system of building. In
this regard, occupancy detection has a significant role in many smart building applications such as heating, cooling,
ventilation (HVAC) and lighting system.

### About the dataset:-

The data set can be loaded from the following link: https://archive.ics.uci.edu/ml/datasets/Occupancy+Detection+
It is a zip file consisting of three data sets that were used in the evaluation of the accuracy of predicting the occupancy of the room, one for training, and two for testing the models considering the office door opened and closed during occupancy. 
The attributes in the datasets are-
1. date on which the following physical parameters where observed and recorded
2. Temperature of the room in Celsius
3.Relative Humidity in %
4. Light in Lux
5. CO2 in ppm
6. Humidity Ratio derived quantity from temperature and relative humidity, in kgwater-vapor/kg-air and 
7. Occupancy- 0 or 1, 0 for not occupied, 1 for occupied status.
Occupancy is the target value to be used for prediction.

### Results that were obtained with this project:- 
I've trained the model using Neural networks and Logistic regression, written as raw codes, once with just one variable and again with two variables.
It was observed that Neural networks gave an accuracy of 98.84% and Logistic regression gave an accuracy of 98.64%. 
Both the algorithms gave pretty good accuracies. Let's dive in and see how this was achieved.
* Accuracies with Neural Networks
    * Training data with test data 1
          Training accuracy  | Validation accuracy
          -----------------  | -------------------
              98.84%         |     97.07%
    * Training data with test data 2
       Training accuracy  | Validation accuracy 
       -----------------  | ------------------- 
            98.84%        |    91.97%           
            
* Accuracies with Logistic Regression
    * With one variable 
          Training accuracy  | Test accuracy 1 | Test accuracy 2 
          -----------------  | --------------- | --------------- 
                 97.87%      |      97.86%     |   99.14%   
    * With two variables 
          Training accuracy  | Test accuracy 1 | Test accuracy 2 
          -----------------  | --------------- | --------------- 
                 98.64%      |      97.89%     |   82.48%   
### Instructions to run the code:-  
1. View the visualization of the datatraining.  
2. Check how the accuracy is obtained in Neural networks
3. Check how the accuracy is obtained in Logistic regression with just one variable and also with two variables.
