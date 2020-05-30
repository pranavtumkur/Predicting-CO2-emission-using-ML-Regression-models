# CO2-emission-prediction-using-Regression-models

![rsz_1car-emitting-carbon-dioxide-co2-environmental-vector-21630081](https://user-images.githubusercontent.com/65482013/83296928-3ecc3180-a20f-11ea-94c1-a3ace3ad0d21.jpg)

Experimenting with various regression models, we try to arrive at the most accurate prediction of the CO2 emission of a new car model. Following are the regression models we experiment with:-

• [Single Variable Linear Regression](https://github.com/pranavtumkur/Predicting-CO2-emission-using-ML-Regression-models/blob/master/Simple%20Linear%20Regression%20Model.ipynb) - To begin with, we build a ML model considering only 1 independent variable- Engine Size and try to establish a best fitting line to determine the CO2 emissions.

• [Multiple Variable Linear Regression](https://github.com/pranavtumkur/Predicting-CO2-emission-using-ML-Regression-models/blob/master/Mulitple%20Linear%20Regression%20Model.ipynb) - Moving ahead, we use all paramteres which linearly affect the CO2 emissions- _Engine Size, No. of cylinders and Fuel Consumption_ build a ML model to determine the CO2 emissions.

• [Polynomial Regression](https://github.com/pranavtumkur/Predicting-CO2-emission-using-ML-Regression-models/blob/master/Polynomial%20Regression%20Model.ipynb) - We try to fit polynomials of different degrees to determine the best fitting curve to determine the CO2 emissions.

• [Non-linear Regression](https://github.com/pranavtumkur/Predicting-CO2-emission-using-ML-Regression-models/blob/master/Non%20Linear%20Regression%20Model.ipynb) - We move to a different dataset, since CO2 emissions are mostly linearly dependent on all its independent parameters. We explore the different kinds of non-linear curves viz. exponential, sigmoidal, logarithmic, parabolic etc. and try to find out the best fitting curve to determine the CO2 emissions.

Analysis is done using Python Scikit-learn library on Jupyter notebooks. Accuracy of each model is verified using Residual MSE, Mean abosolute error, R-squared value and Explained-variance.
