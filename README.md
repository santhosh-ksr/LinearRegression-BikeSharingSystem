# Project Name
> Linear Regression Model for bike-sharing system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- From the model we derived that the equation of our best-fit line is
    cnt = 0.196 + (0.234 X yr)-(0.094 X holiday)+(0.492 X temp)-(0.150 X windspeed)-(0.067 X season_spring)+(0.047 X season_summer)+(0.082 X season_winter) - (0.053 X mnth_jul) + (0.077 X mnth_sep) +(0.020 X Weekday_Sat) - (0.285 X weathersit_LightSnow_LightRain) - (0.080 X weathersit_Mist_Cloudy)
- Top three features that contributing significantly to explain the demand of bikes are
	a. temp
	b. weathersit_LightSnow_LightRain
	c. yr
- R-Sqaured and adj R-Sqaured value of both train and test dataset well explains the demain of bikes by 80% atleast.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandaslibrary
- matplotliblibrary
- seaborn
- sklearn
- statsmodels



<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Thanks to professor Harish.



## Contact
Created by [@santhosh-ksr] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->