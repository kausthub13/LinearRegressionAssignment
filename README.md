# Linear Regression Assignment
> a linear regression analysis on a dataset related to bike rentals. The objective here is to build a predictive model that estimates the total number of bike rentals (cnt), using various features available in the dataset. It uses features likes seasons, weather situation , year and numerical data like humidity , temperature etc.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project focuses on analyzing and predicting bike rental counts using Linear Regression
- The primary business problem addressed by this project is to develop a predictive model that can estimate the number of bike rentals on a given day based on various influencing factors
- The dataset used in this project contains daily records of bike rentals. It includes features such as: dteday, season, yr, mnth, holiday, atemp etc


## Conclusions
- The Categorical Variables Weekday, Day (Inferred from dteday) were not part of the final model since they had a high p-value
- The Categorical Variables Summer, Workingday, month (inferred from dteday) were not part of the final since they had high p-value and high VIF and were removed as part of RFE
- The remaining categorical variables holiday, Sprint(inferred from season), Light Snow, Mist (Inferred from weathersit) have a negative impact on the final rental bike count
- Winter (inferred from Season) seems to have a positive implact on the final rental bike count
- Temp and atemp both seem to have the highest correlation with the target variable
- Positive correlation observed in : temp, yr, winter
- Negative correlation observed in : holiday, windspeed, sprint, light snow and mist



## Technologies Used
- pandas
- numpy
- scikit-learn
- statsmodels
- matplotlib


## Contact
Created by [@kausthub13] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
