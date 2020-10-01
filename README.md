# Black Friday Insights and Prediction

------------

![](https://raw.githubusercontent.com/EagleDangar/BlackFriday-prediction/master/images/blackfridaycanceled.jpg)

## I also released my article on [Medium](https://medium.com/@mayur11061997/black-friday-insights-and-prediction-16933b8a8bfb).


## Table Of Contents

  - [What is Black Friday ?](#what-is-black-friday-?)
  - [Python and Libraries](#python-and-libraries)
  - [File Structure](#file-structure)
  - [Summary](#summary)
  - [Acknowledgements](#acknowledgements)

## What is Black Friday ?
Black Friday is the day after Thanksgiving. Retailers typically offer steep discounts on Black Friday to kick off the holiday season.Black friday is the one of the most profitable days for all the retailers and for the buyers too. It's common for retailers to offer special promotions and open their doors during the pre-dawn hours on Black Friday to attract customers.

To keep up with the competition, retailers need some insights and cluster of customers to segmantize and to target them. So, retailers can use different marketing strategies to attract different types of customers.

Data scientist can help retailers with proper insights based on the historical data of black friday and also give proper data driven solutions by using Data science methods and by following the **CRISP-DM Process (Cross Industry Process for Data Mining)**. Thus, they can achieve thier target/goal.This project is all about this.

below are the steps of CRISP-DM Process ,

1. Business Understanding
2. Data Understanding
3. Prepare Data
4. Data Modeling
5. Evaluate the Results
6. Deploy


------------

## Python and Libraries
- Python 3.7+
- pandas , scikit-learn, seaborn, XGBoost, jupyter notebook.

## File Structure

        ├── README.md
        ├── blackfriday-insights-and-model.ipynb
        ├── images
        │   ├── blackfriday-1.jpg
        │   ├── blackfriday-2.jpg
        │   └── blackfridaycanceled.jpg
        ├── kaggle
        │   └── input
        │       └── black-friday
        │           ├── test.csv
        │           └── train.csv
        └── model
            ├── BFriday_XGB_Model_V1.pkl
            └── BFriday_XGB_Model_V1_details.json

- Directories
	-  kaggle/input/black-friday/ :-  Contains all the data-sets
	-  images/ :- Contains all the required images
	-  model/ :- Contains all the files related to saved model


- Files
	- blackfriday-insights-and-model.ipynb :-  Main notebook of this project
	- train.csv :-  Training Data-set
	- test.csv :- Test Data-set
	- BFriday_XGB_Model_V1.pkl  :- saved xgboost model
	- BFriday_XGB_Model_V1_details.json  :-  saved xgboost model's definition 


## Summary

In summary, We went through each and every steps of **CRISP_DM**, did different types of analysis on the data, visualized the data with different types of charts and trained the model with different types of machine learning models to predict the purchase amount that user might spend on next black friday.


## Acknowledgements

- [Kaggle - Black Friday ](https://www.kaggle.com/sdolezel/black-friday )
