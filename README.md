# Bike Sharing
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Problem Statement

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 



## Conclusions

Analysis between Train model and Test model:
 - r-squared value for train dataset : 0.83
 - r-squared value for test dataset : 0.80

As per our final Model, there are top 3 predictor variables that influences the bike booking are:
    temp - 
            A coefficient value of ‘0.4583’ 
            indicates that a unit increase in temp variable increases the bike hire numbers by 0.4583 units.
            therefore as temperature increases the bike booking increases
     Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds -  
             A coefficient value of ‘-0.2863’
             therefore in snowy climate the bike booking decreases
     Year (yr) - 
             A coefficient value of ‘0.2349’ indicated that a unit increase in yr variable increases
             the bike hire numbers by 0.2349   units. 
             therefore in year 2019 the bike booking increased
    
     For Business Goals:
     - Temperature could be a prime factor for more demand of bikes
     - We can see demand for bikes was more in 2019 than 2018
    


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- statsmodels


## Acknowledgements
- This project was inspired by Upgrad


## Contact
Created by [femishajan@githubusername] - feel free to contact me!

