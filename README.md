# Project Name
> Outline a brief description of your project.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This repository contains the Linear Regression model for the Bike sharing service provider named BoomBikes.
- <b>Background</b>: A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
    
    A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

    In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


- <b>Business Problem</b>: Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
    
- Dataset Provided: The dataset provided for this problem contains 730 records and 29 columns

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
### R-squared is 84% on train set and 81.4% on test set
### Adjusted R-squared is 83.6% on train set and 80.5 on test set

#### The good predictors for the target variable were these 12 predictor variables:
- temp: tells about the temperature
- workingday: tells if the it was a working day or not
- windspeed: tells about speed of the wind
- spring: represents the season
- year
- Sat: represents saturday
- Jan: represents January month
- Mist + Cloudy: represents the weather situation
- July: represents the July month
- Sept: represents the September month
- Oct: represents the October month
- Light Snow: represents the snow

#### the equation of the regression line:
##### let Xi denote the variables with i is the variable number in the above list of predictors, so the equation will be:
$ Count = 0.258 + 0.381 \times B1 + 0.054 \times B2 - 0.159 \times B3 - 0.121 \times B4 + 0.236 \times B5 + 0.066 \times B6 - 0.051 \times B7 - 0.081 \times B8 -    0.061 \times B9 + 0.061 \times B10 + 0.057 \times B11 - 0.298 \times B12 $

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- IDE - Anaconda Jupyter Notebook and VS Code
- language - python v3.9
- library - pandas v1.4.4
- library - numpy v1.21.5
- library - matplotlib v3.5.2
- library - seaborn v0.11.2
- library - sklearn
- library - statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was a business problem provided by Upgrad
- References taken for this case study are:
    1. https://stackoverflow.com/
    2. https://www.kaggle.com/
    3. https://www.google.com/
    4. https://towardsdatascience.com/
    5. https://medium.com/


## Contact
Created by [https://github.com/sanskar752000/] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->