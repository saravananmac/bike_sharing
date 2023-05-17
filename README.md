# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
Bike sharing using linear regression
- What is the background of your project?
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 
Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. 
This bike can then be returned to another dock belonging to the same system.
- What is the business probem that your project is trying to solve?
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. 
The company is finding it very difficult to sustain in the current market scenario. 
So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
Variables classification as of Reading the Dataset
The categorical variables are:

season
yr
mnth
holiday
weekday
workingday
weathersit

The continuous variables are:

temp
atemp
hum
windspeed
casual
registered
cnt
- Conclusion 2 from the analysis
1. Boxplot used for Categorical Variables against Count to determine the Median and outliers in the dataset.
    There are no outliers present in the dataset.
2. Barplot used for Categorical variables against count to determine Mean/Med, identify trends and comparison for year 2018, 2019. Also Predictor for Dependent variables. 
    Season - Most of the bookings do happen in season '3-fall' when compared to others
    month - 6-Jun, 9-Sep & 8- Aug do have the highest overall bookings
    Weather - This variables plays a major role in determining dependent variable as the bookings have increased significantly when Weather is good and dry. The same subdues if the condition is wet.
    Holiday - Most of the bookings were done on a weekday 
    weekday - All the days in the weekday show similar trend and this variable could influence prediction 
    workingday - Higher # of bookings were made on a working day and this cound be a candidate for determining if this variable to determine the bookings 
3. Heatmap used for determining the Correlation between two Continuous variable. 
    Liner relationship exists betweek temp & atemp; hence this variable cannot be used in the model. 
- Conclusion 3 from the analysis
# Final Comparison of the results between Training & Test Dataset
R-squared Training Dataset - 0.839
R-squared Test Dataset - 0.8066
Adjusted R-squared Training Dataset - 0.835
Adjusted R-squared Test Dataset - 0.7963
- Conclusion 4 from the analysis
Demand of the bikes are dependent on following variables Year Holiday Temp Windspeed Months (Sep) Climate (Cloudy, Lightrain, spring, summer, winter)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

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