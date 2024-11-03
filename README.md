# Iterative Linear Regression

## Introduction
This project aims to extend the use of the linear regression house valuation model to analyze housing data from Boston, Massachusetts, particularly around various attributes for the homes observed in the area and their prices using multiple algorithms.

This project will scope, analyze, prepare, plot data, and seek to explain the findings from the analysis.

Here are some questions that this project seeks to answer:

- Can an alternative cost minimization approach such as **gradient descent** be utilized to reduce training duration?
- How does this approach affect the mean squared error(MSE)? 



### Scenario
As the scope of the real estate models continues to broaden, there is the realization that soon it will be necessary to work with enormous datasets — datasets containing hundreds of thousands of instances and hundreds or even thousands of features. The conventional closed-form solution of the normal equation will likely hinder training efficiency, potentially causing the training process to slow down to an unacceptable level. Therefore, an alternative cost minimization approach, like gradient descent, will be explored in hopes of reducing training time. Retraining the Boston regularized linear regression housing model will be the first step.

**Data Sources:**

- data/BostonHousing.csv
- [StatLib Archive](https://lib.stat.cmu.edu/datasets/boston)
- [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/)

## Project Goals
The objective is to explore the use of a different cost minimization method, such as gradient descent, to **potentially reduce training duration**. 




#### Why use a linear regression algorithm to produce a real estate price estimator?
The model aims to forecast the selling price of a house based on specific characteristics. This outcome falls under the category of regression. Although various algorithms can generate regression results, linear regression is straightforward, fairly simple to apply, and often yields satisfactory results in numerous situations.

The house's median value(**Target**) is the output (the dependent variable). The model determines (predicts) the
price through multiple inputs (independent variables). This is an appropriate task for a regression model.

## Data
The same data used to train the regularized linear regression model will be employed. It is a CSV file containing more than 506 anonymized real estate transactions in Boston, Massachusetts. 

## Conclusions
TBD