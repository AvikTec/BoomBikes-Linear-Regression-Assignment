# Project Name
> Build a model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- equation is
      cnt = 4491.30 + 1069.78 x yr + 370.72 x september -257.79 x november - 263.97 x may 
           + 318.96 x june -344.55 x Cloudy - 367.86 x january -216.54 x february - 265.03 x december
             + 260.30 x july + 357.72 x winter + 365.59 x august - 454.45 light snow/rain - 391.91 spring
- The equation provided is a linear regression model for predicting the dependent variable, 
cnt
cnt, which seems to represent a numerical value (possibly count or demand) based on various independent variables like year, months, weather conditions, and seasons. Here's the breakdown:

Key Observations:
Yearly Increase:

The positive coefficient for 
yr
yr (
+
1069.78
+1069.78) suggests that the dependent variable increases over time, by approximately 1069.78 units per year.
Seasonal and Monthly Effects:

September
September (
+
370.72
+370.72), 
June
June (
+
318.96
+318.96), 
July
July (
+
260.30
+260.30), 
August
August (
+
365.59
+365.59), and 
Winter
Winter (
+
357.72
+357.72) positively contribute to 
cnt
cnt. These periods may correspond to higher demand or activity.
January
January (
−
367.86
−367.86), 
February
February (
−
216.54
−216.54), 
November
November (
−
257.79
−257.79), 
May
May (
−
263.97
−263.97), and 
December
December (
−
265.03
−265.03) negatively impact 
cnt
cnt, indicating lower activity or demand during these times.
Weather Conditions:

Cloudy
Cloudy (
−
344.55
−344.55) and 
Light Snow/Rain
Light Snow/Rain (
−
454.45
−454.45) have significant negative coefficients, showing reduced activity or demand under these weather conditions.
Spring
Spring (
−
391.91
−391.91) also reduces 
cnt
cnt, possibly due to seasonal preferences.
Conclusion:
General Trend: The variable 
yr
yr indicates growth or increase over time.
Seasonality: Summer months (June, July, August) and winter contribute positively to 
cnt
cnt, while early spring (February, May) and late fall (November, December) have negative effects.
Weather Impact: Cloudy weather and light snow/rain reduce 
cnt
cnt significantly, suggesting outdoor or weather-dependent activities are likely impacted.
The overall equation highlights the importance of temporal and environmental factors in predicting 
cnt
cnt.

-On analysing data, it was observed that, the linear regression model was able to predict bike demand precisely with an R2 Score of more than 80%
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- python


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements



## Contact
Created by [avikundu@gmail.com] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
