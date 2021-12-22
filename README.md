# Bike_Sharing_Assignment

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Tools](#tools)
* [Acknowledgements](#acknowledgements)

## General Information
Individuals can rent or borrow bikes from a bike-sharing system on a short-term basis for a fee or for free. To unlock the bicycle, the user enters their payment information into a computer-controlled "dock," which is usually located in a public place. Afterwards, this bike can be returned to another dock of the same system.

Revenues for a US bike-sharing service BoomBikes have recently dropped significantly due to the ongoing Corona pandemic in America. The current market conditions are making it difficult for the company to continue. When the current lockdown ends and the economy returns to a healthy state, the company has decided to devise a business plan that will allow it to quickly increase its revenue.

After the Covid-19 quarantine ends, BoomBikes hopes to learn more about the demand for shared bikes from the general public. They have planned this in order to be ready to serve the people's needs once the situation improves and stand out from other service providers and make enormous profits..

They've hired a consulting firm to help them figure out what drives demand for these bikes. For this study, they're looking at the factors that drive demand for these shared bikes in the United States, specifically. What's the company's interest?

In predicting the demand for shared bicycles, what factors are most important to keep in mind.

## Conclusion:
>Uploaded a Python Notebook which consist of the the practical work done using Linear Regression Model and Presentation for explaination of the result and work done.

Variables that are significant to predict the demand for shared bikes are described below:
- temp
- yr
- holiday
- season
- weekday Sunday
- month

And Here described below is the final list of variables with the size impacting the demands of bike sharing:
- yr: coefficient of yr depicts that yr will increase bike hiring by 2019.944545 value if the unit increase in yr variable
- season_Spring: coefficient of season_Spring depicts that season_Spring will decrease bike hiring by 1026.694652 value if the unit increase in season_Spring variable.
- season_Winter: coefficient of season_Winter depicts that season_Winter will increase bike hiring by 534.701970 value if the unit increase in season_Winter variable.
- mnth_Sept: coefficient of mnth_Sept depicts that mnth_Sept will increase bike hiring by 626.386774 value if the unit increase in mnth_Sept variable.
- weathersit_LightRain_LightSnow_Thunderstorm: coefficient of weathersit_LightRain_LightSnow_Thunderstorm depicts that weathersit_LightRain_LightSnow_Thunderstorm will decrease bike hiring by 2685.592063 value if the unit increase in weathersit_LightRain_LightSnow_Thunderstorm variable.
- weathersit_Mist_Cloudy: coefficient of weathersit_Mist_Cloudy depicts that weathersit_Mist_Cloudy will decrease bike hiring by 676.125770 value if the unit increase in weathersit_Mist_Cloudy variable.
- temp: coefficient of temp depicts that temp will increase bike hiring by 676.125770 value if the unit increase in temp variable.
- weekday_Sun: coefficient of weekday_Sun depicts that weekday_Sun will decrease bike hiring by 414.921335 value if the unit increase in weekday_Sun variable.

## Technologies Used
Python 3.8

## Tools
Jupyter Notebook

## Acknowledgements
This assignment is the part of the Linear Regression module in the Upgrad tutorial of Master's in ML & AI.
Thanks to the support given by student support team and my upgrad buddy Mr. Vishwesh
