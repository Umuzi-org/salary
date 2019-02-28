# Umuzi assignment 2: Predicting salary differences
## Simple Linear Regression

## Submission:
 Create a notebook and commit your notebook changes to Github.
Once you are done, create an html report from the notebook.

## To complete this assignment, you should go through the following materials:
Introduction to Linear Regression, https://github.com/justmarkham/DAT4/blob/master/notebooks/08_linear_regression.ipynb
Simple and Multiple Linear Regression in Python, https://towardsdatascience.com/simple-and-multiple-linear-regression-in-python-c928425168f9


Crash Course Statistics: Regression, https://youtu.be/WWqE7YHR4Jc
Khan Academy Engageny Algebra Topic D, Lessons 14 – 18 (Modelling relationships with a line & Residuals):
https://www.khanacademy.org/math/engageny-alg-1/alg1-2/alg1-2d-modeling-relationships-line/v/fitting-a-line-to-data

##Instructions:
In the next series of challenges, we will predict employee salaries from different employee characteristics (or features).
We are going to use a simple supervised learning technique: linear regression. We want to build a simple model to determine how well Years Worked predicts an employee’s salary.
Import the data salary.csv to a Jupyter Notebook. A description of the variables is given in Salary Metadata. You will need the packages matplotlib, pandas and statsmodels.

## Answer the following questions:
a)	Using the `statsmodels` package, run a simple linear regression for Salary with one predictor variable: Years Worked.

i.	Does the model significantly predict the dependent variable? Report the amount of variance explained (R^2) and significance value (p) to support your answer.

ii.	What percentage of the variance in employees’ salaries is accounted for by the number of years they have worked?

b)
i.	What does the unstandardized coefficient (B or 'coef' in statsmodels) tell you about the relationship between Years Worked and Salary?

ii.	What do the 95% confidence intervals [0.025, 0.975] mean?

iii.	Calculate the expected salary for someone with 12 years’ work experience.

iv.	Calculate the expected salary for someone with 80 years’ work experience. Are there any problems with this prediction? If so, what are they?

c)	We have only looked at the number of years an employee has worked. What other employee characteristics might influence their salary?
