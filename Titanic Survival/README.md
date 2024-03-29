# Titanic - Machine Learning from Disaster
Predicts Survival of Passengers.

## Objective
Use machine learning to create a model that predicts which passengers survived the Titanic shipwreck.

## The Challenge
On April 15, 1912, during her maiden voyage, the widely considered “unsinkable” RMS Titanic sank after colliding with an iceberg. Unfortunately, there weren’t enough lifeboats for everyone onboard, resulting in the death of 1502 out of 2224 passengers and crew.

While there was some element of luck involved in surviving, it seems some groups of people were more likely to survive than others.

In this challenge, we ask you to build a predictive model that answers the question: “what sorts of people were more likely to survive?” using passenger data (ie name, age, gender, socio-economic class, etc).

## About Dataset
The data has been split into two groups:
* training set (train.csv)
* test set (test.csv)
##### Training set includes 819 records and 418 records are in Test set and 12 attributes.

The training set should be used to build your machine learning models. The test set should be used to see how well your model performs on unseen data.
#### Variable Note
* pclass: A proxy for socio-economic status (SES)
  * 1st = Upper
  * 2nd = Middle
  * 3rd = Lower

* age: Age is fractional if less than 1. If the age is estimated, is it in the form of xx.5

* sibsp: The dataset defines family relations in this way...
  * Sibling = brother, sister, stepbrother, stepsister
  * Spouse = husband, wife (mistresses and fiancés were ignored)

* parch: The dataset defines family relations in this way...
  * Parent = mother, father
  * Child = daughter, son, stepdaughter, stepson
  * Some children travelled only with a nanny, therefore parch=0 for them.

## Acknoweldgment
The dataset is collected from <a href="https://www.kaggle.com/c/titanic/data">Kaggle</a>


## Structure of Project
- *Step1:* Import Libraries and Load Dataset.        
   - Import required libraries and helper function.
   - Load data set using Pandas.

- *Step2:* Inspect and Visualize Data.
   - Explore Dataframe.
   - Check the Null values.
   - Get *Statistical* Overview.
   - Visualizing data using *SWEETVIZ*(open source library file for python to visualize target column having only binary value *i.e 0's and 1's).

- *Step3:* Data Pre-Processing.
   - Handling Missing values.
   - Droping irrelevant Column.
   - Seperating Categorical and Neumerical Values.
   - Converting categorical value into neumerical
   - Feature Engineering

- *Step4:* Spliting Data into Dependent Variable and Independent Variable.
   - Then Spliting the data into Training and Testing Set.

- *Step5:* Training the Model using Various Algorithms.
   - Logistic Regression
   
- *Step6:* Display Mean Square Error(MSE) and Accuracy Score

- *Step7:* Prediction on Test Data

## Description


## Conclusion

