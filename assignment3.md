# Umuzi assignment 3: Predicting salary differences
## Multiple Linear Regression

## Submission:
Create a notebook and commit your notebook changes to Github.
Once you are done, create an html report from the notebook.

## To complete this assignment, you should go through the following materials:
Robust One-Hot Encoding in Python, https://blog.cambridgespark.com/robust-one-hot-encoding-in-python-3e29bfcec77e
Emulating R Regression Plots in Python, https://medium.com/@emredjan/emulating-r-regression-plots-in-python-43741952c034
Statsmodels Regression Plot, https://www.statsmodels.org/dev/examples/notebooks/generated/regression_plots.html

##Instructions:
In the next series of challenges, we will predict employee salaries from different employee characteristics (or features).
Import the data salary.csv to a Jupyter Notebook. A description of the variables is given in the metadata. You will need the packages `matplotlib` / `seaborn`, `pandas` and `statsmodels`.

## Answer the following questions:

Use multiple linear regression to predict salary from all the variables in the dataset.

a)	Create scatterplots, histograms, and a descriptive statistics table of the variables of interest.

b)	One-hot encode the variable Field into three dummy variables, using HR as the reference category. You can use `pandas`' get_dummies() function for this.

c)	Produce a correlation matrix comparing the relationship of salary to the predictor variables. Is there any multicollinearity or other problems that may be a problem in the multiple regression?

d)	Run the multiple linear regression and interpret the standardised coefficients given in the statsmodels output. What are the most important features when predicting employee salary?

e)	Calculate the standardised residuals (resid()) and standardised predicted values (fittedvalues()).

f) Plot the residuals versus the predicted values using `seaborn`'s `residplot` with fitted values as the x parameter, and the dependent variable as y. lowess=True. Are there any problems with the regression?
