# Project Name
> Linear Regression Bike Sharing Case Study


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Linear Regression Bike Sharing Case Study
 By: [Vikas Dadhich](https://github.com/vikasdadhich100) Date : 26 June 2024

We have a dataset day.csv 
- **Problem Statment:** 
BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

- **Business Goal:**
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

Target Variable: cnt

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


**Based on the provided results, here is a comprehensive conclusion:**
- **Model Performance**
Train dataset R^2 : 0.8195564314872248
Test dataset R^2 : 0.7919791167382211
These R-squared values indicate that the model explains approximately 81.96% of the variance in the target variable on the training set and 79.20% on the test set. This demonstrates that the model generalizes well and performs consistently across both the training and test datasets.

- **Regression Equation**
The regression equation for predicting the target variable

**cnt(y)=0.1850+yrX(0.2306)+tempX(0.4885)+season_SpringX(-0.1188)+season_WinterX(0.0582)+mnth_JulX(-0.0715)+mnth_SepX(0.0542)+weathersit_Light_Snow_RainX(-0.3016)+weathersit_Mist_CloudyX(-0.0747)**

- **Interpretation of Coefficients**
  - yr (0.2306): Indicates a positive impact on the target variable. As the year progresses, the target variable tends to increase.
  - temp (0.4885): Suggests a strong positive relationship with the target variable. Higher temperatures are associated with higher counts.
  - season_Spring (-0.1188): Implies that counts are lower in the Spring season compared to the reference season.
  - season_Winter (0.0582): Suggests a slight increase in counts during the Winter season.
  - mnth_Jul (-0.0715): Indicates that counts are lower in July compared to other months.
  - mnth_Sep (0.0542): Indicates that counts are slightly higher in September compared to other months.
  - weathersit_Light_Snow_Rain (-0.3016): Shows a strong negative impact. Light snow or rain significantly reduces the counts.
  - weathersit_Mist_Cloudy (-0.0747): Indicates a decrease in counts during misty or cloudy weather, although the effect is smaller than for light snow or rain.
- **Residual Analysis**
The residual errors of the model are normally distributed with a mean of 0. This suggests that the model's assumptions are likely satisfied, and there are no significant patterns in the residuals that would indicate a problem with the model.


## Conclusion
Overall, the model appears to perform well, explaining a substantial portion of the variance in the target variable and showing good generalization across the training and test datasets. The coefficients indicate that temperature and year are significant positive predictors, while certain seasons, months, and weather conditions can negatively impact the target variable. The normal distribution of residuals further validates the reliability of the model.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Google Collab](https://colab.research.google.com/?authuser=0#create=true)
- Python 3.0 
- Pandas 2.0.3
- Seaborn 0.13.1
- Matplotlib 3.7.1
 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was based on [AI/ML PG Course](https://learn.upgrad.com/).


## Contact
Created by [@vikasdadhich100]/vikasdadhich1990@gmail.com - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->

