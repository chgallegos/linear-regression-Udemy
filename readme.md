# UFOs
## Overview

The purpose of this analysis was use a linear regression in order to predict the estimated purchase value per customer at a vehicle dealership. For this analysis, the technology used was tensorflow Keras.
----
## Results
### PART 1 "ETL"

The data was provided via .csv file with information about historical purchases. From the data we could establish our X and Y variables as follow:

![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/dataframe.png)

Where the red framed data is the X variable and the Y variable is framed in blue.

### PART 2 "Scale the data"

The X variables were scaled on a range between 0 and 1 for consistency and training the model. Min  max scaler was used for X variables and reshape was used for Y variable

![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/x_scaled.png)
![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/y_scaled.png)


### PART 3 "Split into Test and Train data"

The method utilized for splitting the train and test data was the following:

![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/split.png)


### PART 3 "Train the Model"

The model ran with 25 nodes on the first and only hidden layer. The activation used was "Relu" and "linea" for the output layer.


![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/regression_model.png)

![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/fit_%20model.png)

### PART 3 "Evaluate the Model"

The curve on the model shows that the loss is achieved in less than 10 epocs, meaning that the model has a high degree of accuracy as well as allignment to the linear data.

![Screenshot](https://github.com/chgallegos/linear-regression-Udemy/blob/main/resources/evaluate_and_utilize.png utilize)

----
## Summary 

The linear regression is one tool that can have an effective use when predicting a number based on historical data, yet it seems that the predictions have a tendency to be higher than what reality might suggest. It is still a good model to have and use as a reference as well.



