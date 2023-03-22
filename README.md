# Subsidy Authenticator

## Problem statement :

   - "Subsidy Inc. delivers subsidies to individuals based on their income

   - Accurate income data is one of the hardest piece of data to obtain across the world

   - Subsidy Inc. has obtained a large data set of authenticated data on individual income, demographic parameters, and a few financial parameters.

   - Subsidy Inc. wishes us to:

   - Develop an income classifier system for individuals.

### The Objective is to:

Simplify the data system by reducing the number of variables to be studied, without sacrificing too much of accuracy. Such a system would help Subsidy Inc. in planning subsidy outlay, monitoring and preventing misuse.

#### Size : 31,978 x 13  ,    Data File : income.csv


![incomecsvss](https://user-images.githubusercontent.com/123350287/227032019-493150c4-1513-4490-b6bc-878bfdd70c3d.JPG)

#### We have 13 Features including indivisual's income (Label)
## out of 13 features ! is Outcome Variable


## FrameWork :

![Screenshot (80)](https://user-images.githubusercontent.com/123350287/227035447-c1fb4630-e58b-463e-a4b5-577794cba31e.png)

   - Problem Conceptualization 
      - Develop an income classifier for indivisuals with reduced no. of variables
   - Problem characterization - Classification

## -Dependent Variable -> Categorical (Binary)
## -Indepent Variables -> Numerical + categorical

![sscvx](https://user-images.githubusercontent.com/123350287/227037066-e4c1e3fc-f1d1-4d4a-b030-bac5cbbffbdf.JPG)


## By looking at this problem we understand that :
### This problem can be conceptualized as a Binary Classification Problem 
### Also it is Supervised ML Problem as Labels are avaliable in DataSet


![dx](https://user-images.githubusercontent.com/123350287/227038029-2639e225-0785-435c-9921-3f81e5a0c2a8.JPG)



## Solution conceptualization


   - Identify if data is clean
   - Look for missing values
   - Identify variables influencing salary status and look for possible relationships between variables
      -  Correlation, chi-square test, box plots, scatter plots etc.
   - Identify if categories can be combined
   - Build a model with reduced number of variables to classify the individual's salary status to plan subsidy outlay, monitor and protect misuse
 
## Method identification

   - Logistic Regression
   - Random Forest
   - K Nearest Neighbors
   - Realization of solution
   - Evaluate performance metrics
   - If assumptions are satisfied and solutions are acceptable then model is good
