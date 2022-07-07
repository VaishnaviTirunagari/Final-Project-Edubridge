#                Bike Buyers Analysis

  - Build a model to analyize the Bike Buyers data
 
 ![showroom5](https://user-images.githubusercontent.com/98824022/177540035-a01c964c-06bc-49e2-b394-b79b23eb5073.jpg)
 ![bike_0](https://user-images.githubusercontent.com/98824022/177540234-b65556cd-ab05-4a34-a2f8-51cf19b61466.jpg)

# Overview:
Bike Buyers Dataset for Exploratory Data Analysis.

This dataset has details of 1000 users from different backgrounds and whether or not they buy a bike. This data can be used for prediction models using Machine Learning Algorithms. There are some NA values injected in the dataset. Use this dataset for Data Cleaning, Exploration and Visualization.

## About the Data

| Columns            |      Description                                                        |
|--------------------|------------------------------------------------------------------------ |
| ID                 |       ID of the Customer                                                |
|                    |                                                                         | 
|Marital Status      |   Marital status of the customer( Single or Married )                   |
|                    |                                                                         |
| Gender             |   Gender of the Customer ( Male or Female)                              |
|                    |                                                                         | 
| Income             |   Monthly Income of the Customer in Rs.                                 | 
|                    |                                                                         |
|Children            |   Number of Children Customer has/have                                  |
|                    |                                                                         |
|Education           |   Educational Qualification of the Customer                             |       
|                    |                                                                         |
|Occupation          |   Occupation of the Customer                                            |
|                    |                                                                         | 
|Home Owner          |   If the Customer is a home owner .Yes/no                               |  
|                    |                                                                         |
|Cars                |   Numbers of Cars a Customer own (In numbers)                           |
|                    |                                                                         |
|Commute Distance    |   Max Distance travelled by the customer everyday to workplace          |
|                    |                                                                         |
| Region             |   Region of the Customer belonging to                                   |
|                    |                                                                         |
|  Age               |    Age of the Customer (In numbers)                                     |
|                    |                                                                         |
| Purchased Bike     |    Bike Purchased by the Customer                                       |

## Problem Statement:

The study on Customer buying behaviour while purchasing a bike , the possibility and the factors that influence the customer to purchase the bike.

The objective is to analize the criteria where and by whom more numbers of bikes have been purchased.

Implementation:

## Libraries:
NumPy

Pandas 

sklearn 

Matplotlib 

Seaborn

## Approach:

The aim is to create a model that helps the users to apply machine learning approach to predict Purchasing criteria. Here, the models used are

Logistic Regression

Decision Tree Classifier 

Random Forest Classifier

GaussianNB

XGBoost Classifier

## Comparison of all Models:

|Model                      | Accuracy Percentage |	                                                            
|---------------------------|-------------------- |
|Logistic Regression	      |      68%	          |    
|Decision Tree Classifier  	|      72%	          |   
|Random Forest	Classifier  |      77.5%	        |    
|GaussianNB                 |      65%	          |   
|XGBoost Classifier         |      75%	          |   

## From all the models Best Model is Random Forest Classifier and the Accuracy of model is .77

