# Project Name
## Bike Sharing Assignment
#### This assignment is a programming assignment wherein I have built a multiple linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Contact](#contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contacted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market.

The company wants to know:<br>
Which variables are significant in predicting the demand for shared bikes?<br>
How well those variables describe the bike demands?<br>
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
#### Below are the top 03 significant predictor variables:
__i.) atemp__: It has the highest coefficient value of 0.441271 that indicates that this variable has the highest impact on the target variable 'cnt'.<br>A unit increase in 'atemp' variable, increases the bikes demand by 0.441271 units. (as per our scaler)<br>
__ii.) Light_Snow_Light_Rain__: It has the highest negative coefficient value of 0.293286 that indicates that this variable has the second highest impact on the target variable 'cnt'.<br>A unit increase in 'Light_Snow_Light_Rain' variable, decreases the bikes demand by 0.293286 units.<br>
__iii.) yr__: It has the second highest positive coefficient value of 0.235210 that indicates that this variable has the third highest impact on the target variable 'cnt'.<br>A unit increase in 'yr' variable, increases the bikes demand by 0.0.235210 units.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Jupyter Notebook 6.4.5
- Numpy 1.20.3
- Pandas 1.3.4
- Matplotlib 3.4.3
- Seaborn 0.11.2
- Scikit Learn 0.24.2
- Statsmodels 0.12.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@atulch09] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->