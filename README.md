# Project Name
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This assignment is a programming assignment wherein you have to build a multiple linear regression model for the prediction of demand for shared bikes. You will need to submit a Jupyter notebook for the same. 
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- seems that temp and atemp variables are have linear relationship with cnt variable/column
- # Season
#There are more number of bookings in season3(fall), then season2(summer) and then season4(winter). all have a median above 5000
#Season can be a good predictor for dependent variable cnt

#mnth
#there is an increase in bike bookings from month 5 to 10, all have median above 5000. It shows the cnt column is dependent on
#mnth column

#weathersit
#bikes are booked mostly in the weather conditions Clear, Few clouds, Partly cloudy, Partly cloudy
# and there is a little decrease in booking for weather conditions Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
#there is drastic change in booking in conditions Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 
#and no bookings for conditions Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

#holiday
#most of the bikes are booked when there is no holiday, here the variable is biased with cnt. The variable holiday is not a good predictor 
#for cnt

#weekday
#all the weekdays maintain similar trend with median between 4000 to 5000.

#Workingday
#most of the bikes are booked in working day when compared to holiday,this is also a good predictor for cnt
- #the equation for the best fitted line is 
#cnt = 0.075009 + (yr × 0.233139) + (workingday × 0.056117) + (temp × 0.549892) − (windspeed × 0.155203) + (season2 × 0.088621) + (season4 × 0.130655) + (mnth9 × 0.097365) + (weekday6 × 0.067500) − (weathersit2 × 0.080022) − (weathersit3 × 0.287090)
- 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python 3
- jupyter playbook  
- sklearn
- pandas
- numpy
- matplotlib
- statsmodels

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->