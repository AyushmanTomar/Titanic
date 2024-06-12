# Titanic Survival Prediction

## Overview
This repository contains a Jupyter notebook that implements a linear regression model to predict the survival of passengers aboard the Titanic.

## Dataset
The dataset used in this project is the famous Titanic dataset that describes the survival status of individual passengers on the Titanic. The dataset includes the following fields:

- `PassengerId`: An unique index for passenger rows. It starts from 1 for first row and increments by 1 for every new rows.
- `Survived`: Shows if the passenger survived or not. 1 stands for survived and 0 stands for not survived.
- `Pclass`: Ticket class. 1 stands for First class ticket. 2 stands for Second class ticket. 3 stands for Third class ticket.
- `Name`: Passenger's name. Name also contain title. "Mr" for man. "Mrs" for woman. "Miss" for girl. "Master" for boy.
- `Sex`: Passenger's sex. It's either Male or Female.
- `Age`: Passenger's age. "NaN" values in this column indicates that the age of that particular passenger has not been recorded.
- `SibSp`: Number of siblings or spouses travelling with each passenger.
- `Parch`: Number of parents or children travelling with each passenger.
- `Ticket`: Ticket number.
- `Fare`: How much money the passenger has paid for the travel journey.
- `Cabin`: Cabin number of the passenger. "NaN" values in this column indicates that the cabin number of that particular passenger has not been recorded.
- `Embarked`: Port from where the particular passenger was embarked/boarded.

## Model
The Jupyter notebook in this repository uses a linear regression model to predict whether a passenger on the Titanic would have survived or not, based on features like age, sex, passenger class, etc.

## Usage
To use this project, follow these steps:
1. Clone this repository to your local machine using git clone.
2. Install the required Python packages numpy, pandas, matplotlib, scikit-learn, seaborn.
3. Open the Jupyter notebook and run the cells to see the model in action.

