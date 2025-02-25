# Project Name

US bike-sharing (BoomBikes)

## Table of Contents

* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

* What is the background of your project?
  > The background of this project is to develop a linear regression model for shared bikes with the available multiple variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations.
  
* What is the business probem that your project is trying to solve?
  > A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

* What is the dataset that is being used?
  > we are using a dataset for the time period 2018 to 2019 by US bike-sharing provider BoomBikes.


## Technologies Used

* `numpy`      - version 2.2.1
* `pandas`     - version 2.2.3
* `matplotlib` - version 3.10.0
* `seaborn`    - version 0.13.2
* `missingno`  - version 0.5.2
* `jupyter`    - version 1.1.1
* `python`     - version 3.13.0
* `sklearn`    - version 1.6.1
* `statsmodels`- version 0.14.4


## Conclusions

* `Temp` - Demand is high when the tempature is between 10 to 15 & 25 to 30.
* `Hum` - Demand is high when the humidity is between 50 to 70.
* `Windspeed` - Demand is high when the Windspeed is less between 9 to 12.
* `Season` - Demand is almost equal in all seasons.
* `Mnth` - Demand is high during month of December.
* `Weather` - Demand is high when the weather is 'Clear, Few clouds, Partly cloudy'.

* `Temperature` is co-related with target variable `cnt`.

* `Train Dataset` - r_squared is 82.8%.
* `Prediction on Test Dataset` - r_squared is 80.5%.


## Acknowledgements

* This project was based on [Linear Regression Assignment](https://learn.upgrad.com/course/7715/segment/58878/354740/1069859/5340643).

## Contact

Created by [@pradeepkumarr355199](https://github.com/pradeepkumarr355199) - feel free to contact!
