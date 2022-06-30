
## Solar Radiation Prediction using Random Forest and Randomized SearchCV

Solar Energy is the future, considering the fact that it is an inexhaustible energy source and requires low installation cost.

PV panels often cannot provide stable electrical power output due to variations in weather conditions, the power grid stability is reduced significantly while integrating the PV power to the power grid.As a stable power grid is a necessity, a precise forecasting technique is required for the stable and safe integration of the PV power to the power grid.

We can predict the power output for a particular array of solar power generators, knowing some environmental conditions. Generation of energy by a solar panel or cell depends upon the doping level and design of solar PV array but the main factors are the amount of solar radiation falling on the panel, environmental factors like atmospheric temperature and humidity and pressure and wind speed present on the panels . These factors are naturally variable and hence the output of solar cell directly depend on it.


About Data

These datasets are meteorological data from the HI-SEAS weather station from four months (September through December 2016) between Mission IV and Mission V.

For each dataset, the fields are:

* A row number (1-n) useful in sorting this export's results
* The UNIX time_t date (seconds since Jan 1, 1970). Useful in sorting this export's results with other export's results
* The date in yyyy-mm-dd format
* The local time of day in hh:mm:ss 24-hour format
* The numeric data, if any (may be an empty string)
* The text data, if any (may be an empty string)

The units of each dataset are:

* Solar radiation: watts per meter^2

* Temperature: degrees Fahrenheit

* Humidity: percent

* Barometric pressure: Hg

* Wind direction: degrees

* Wind speed: miles per hour

* Sunrise/sunset: Hawaii time

## Dependencies
* Python 3.6

* Pandas

* scikit-learn

* Matplotlib

* Seaborn

* Numpy

## Model
XGBoost falls under the category of Boosting techniques in Ensemble Learning. Ensemble learning consists of a collection of predictors which are multiple models to provide better prediction accuracy. In Boosting technique the errors made by previous models are tried to be corrected by succeeding models by adding some weights to the models. 

Unlike other boosting algorithms where weights of misclassified branches are increased, in Gradient Boosted algorithms the loss function is optimised. XGBoost is an advanced implementation of gradient boosting along with some regularization factors.

![Flow-chart-of-XGBoost](https://user-images.githubusercontent.com/105455186/176742631-1009cf5a-0459-4671-9d7b-c6a34296a641.png)
## Refrences

 - [XGBoost](https://xgboost.readthedocs.io/en/stable/)

 - [Hyperparameter Tuning](https://www.jeremyjordan.me/hyperparameter-tuning/)

 - [Optuna](https://optuna.org/)


## Results

