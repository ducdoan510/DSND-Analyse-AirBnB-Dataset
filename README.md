# Udacity DSND Project 4: Analyse AirBnB Dataset

In this project, a dataset from AirBnB about the listings in Seattle will be analyzed. A notebook for analysis follows CRISP-DM methodology. 
This method consists of 6 steps

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment

Download the dataset from the link in **Acknowledgement** section and put the 3 csv files under _seattle_ folder on project root directory.

Follow [this link](https://medium.com/@duc0510/making-sense-of-airbnb-data-insight-from-seattle-listing-dataset-e02e79476162) to a Medium article associating with the the analysis in this repo

## Motivation
AirBnB is a leading platform for short term room renting service. This project analyzes different attributes provided in Seattle listing dataset and aims to answer the following three questions:
1. What is the best time to visit Seattle based on room availability on AirBnB platform?
2. What is the price range for renting room in Seattle on AirBnB?
3. How can we use the data to predict price for a certain listing?


## Installation

It is recommended to install Anaconda so that all needed packages are available
If not run the following commands

```pip install requirements.txt```

## Findings and Conclusion
The questions as in **Motivation** section can be answered as below:
1. What is the best time to visit Seattle based on room availability on AirBnB platform?
Based on room availability and the number of comments that users leave on the platform, July-September is a suitable time to visit Seattle
2. What is the price range for renting room in Seattle on AirBnB?
Most AirBnB listings fall under \$200. Price can go up to \$1000
3. How can we use the data to predict price for a certain listing?
Different machine learning algorithms are used to predict the listing price. Random Forest Regression seems to perform best based on R2 score

## Acknowledgement

The dataset analyzed in this project is from AirBnB and provided by Kaggle at [this link](https://www.kaggle.com/airbnb/seattle/data)
