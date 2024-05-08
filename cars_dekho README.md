# Cars-Dekho Dataset using Linear Regression Model

## Overview
The CarDekho company maintains a database of the cars sold through their platform. The data represents the cars sold by Car Dekho and the car related features. We will build a linear regression model to predict the Selling price of the car. Calculate all the error metrics and diagnostic plots to check the regression result. The dataset consists of information about cars, including their names, manufacturing years, present prices, selling price, kilometers driven, and many other relevant details. With data sourced from CarDekho, it encompasses data of 301 cars, offering a wide array of features such as fuel type, seller type, transmission, and ownership history. 

## Data Description:
Car_Name: Name of the cars.
Year: Year of the car when it was bought.
Selling_Price: Price at which the car is being sold.
Present_Price: Current ex-showroom price of the car.
Kms_Driven: Distance completed by the car in km.
Fuel_Type: Fuel type of the car.
Seller_Type: Tells if a Seller is Individual or a Dealer.
Transmission: Gear transmission of the car (Automatic/Manual).
Owner: Number of previous owners of the car.

## Project Overview
## Tasks/Activities List:

Read the cars dataset.
Exploratory Data Analysis (EDA) - Showed the Data quality check, treat the missing values, etc.
Visualize the diagnostic plots
Transform the categorical data.
Model building.
Apply the Multiple Linear Regression model assumptions.
Print the model results


Success Metrics:
Below are the metrics for the successful of this project
The R-squared of the trained model > 0.8
The Adjusted R-squared of the trained model > 0.8



## Model Result
## `Intial Model`
   - R2 Value : 0.859
   - Adjusted R2 : 0.855
   
## `Tuned Model`
   - R2 Value : 0.931
   - Adjusted R2 : 0.929
   
### `Overall there is an good increase in R2 and Adjusted R2 values after Tuning the Model.`
