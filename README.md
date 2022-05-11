# Bike Sharing Assignment 
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Suggestions & Interpretation of the result](#suggestions)
* [Contributors](#contributors)


## General Information
- The project imports the data from day.csv. 
- The goal is to make a model with independent variables/features 
- Identify the indepandent feature's respective coefficient. 


## Technologies Used
- pandas library - version 1.3.4
- numpy library - version 1.20.3
- statsmodels - version 0.12.2
- sklearn - version 0.24.1
- matplotlib library - version 3.4.3
- seaborn library - version 0.11.2

## Conclusions
- Variables/features that drives the prediction:
	- `temp` with the coefficient of 0.4657
    - `weathersit_LightRain` with the coefficient of -0.2810
    - `windspeed` with the coefficient of -0.1807

## Suggestions & Interpretation of the result
	- BoomBikes has more booking during Fall season followed by summer season.
	- Year 2019 had more booking as compared to 2018.
	- BoomBikes had more booking during `Fall` months and `clear` weather conditions. 
	- During spring, and light snow rain weather the demand decreases and there is a negative correlation with these variables.

## Contributors
- <a href="https://github.com/sanjaysaini-msn">Sanjay Saini</a>


<!-- You don't have to include all sections - just the one's relevant to your project -->