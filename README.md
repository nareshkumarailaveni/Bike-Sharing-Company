# Bike Sharing Assignment
Develop a model to assess the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features and accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* Data Understanding/Cleaning, Outlier Identification, Correlation, Univariant/Bivariant analysis/Data Visualisation/Building a linear module with all the variables/Residual Analysis of the train data/Model Evaluation/Calculating R-squared score on test data
* Numpy,Pandas, Matplotlib, Seaborn and Sklearn libraries used
* Conclusions
* Course Lectures

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

## Conclusions
* The R-squared score on predicted data from test dataset is 0.79
* From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 79% of bike demand. Coeffiencients of the variables explains the factors effecting the bike demand.
* The equation of our best fitted line is:
  cnt=0.0986+(0.2335×yr)+(-0.0786xholiday)+(0.0521×weekday)+(0.5755×temp)+(-0.1663xwindspeed)+(0.0767×season_2)+(0.1280×season_4)+. 
  (-0.0755×weathersit_2)+(-0.2766×weathersit__3)
* Based on final model top three features contributing significantly towards explaining the demand are:
   - Actual Temperature (0.5755)
   - weathersit_3 : Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds (-0.2766)
   - year (0.2335)
So it suggested to give these three variables the utmost importance while planning to achieve maximum demand.


## Technologies Used
* numpy - version 1.21.5
* pandas - version 1.4.4
* Seaborn - version 0.11.2
* Matplotlib - version 3.5.2
* Python - version 3

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on this tutorial.


## Contact
Created by [ailaveninareshkumarailaveni@gmail.com] - feel free to contact me @+91-9972423009.
