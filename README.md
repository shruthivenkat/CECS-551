# CECS-551
Advanced Artificial Intelligence - California State University Long Beach (Fall 2022)


### MIDTERM PROJECT : 

#### Problem statement 

The dataset has five independent failure modes TWF, HDF, PWF, OSF, and RNF. If one of the five mode fails, then the process fails, and the machine is marked as failed. However, the end user or administrator is never aware of the feature which lead to failure of the process. The task is to design a model which address explainability for the failure. 

(1) Design a decision tree based explainable model and provide an explanatory interface

(2) Compute the fairness of the model  

(3) Perform a what-if analysis using CeterisParibus on the given dataset

Dataset :
https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset

### FINAL PROJECT : 

#### Sprint 1 :
The dataset represents the unit sales (in number/quantity) of various products sold in the USA, organized in the form of grouped time series. More specifically, the dataset involves the unit sales of around 3000 products, classified in 3 product categories (Hobbies, Foods, and Household), and 7 product departments in which the above-mentioned categories are disaggregated. 

The products are sold across 10 stores, located in 3 States (CA, TX, and WI). In this respect, the most disaggregated data, i.e., product- store unit sales, can be grouped based on either location (store and state) or product-related information (department and category).

1. Use Tableau to visualize the dataset_02.
https://www.tableau.com/products/desktop

2. Publish the Tableau dashboard on public server. 
For example, https://public.tableau.com/app/profile/joslininsight/viz/AONLLongitudinalL4NursingLeadershipInsightStudy/AONLLongitudinalL4NursingLeadershipInsightStudy

-- Refer AI_ASSIGNMENT.twd for Tableau workbook

#### Sprint 2:

A) Design a machine learning model to make accurate predictions for product sales for next 10 days in advance (the data set includes daily unit sales per product) and compare the performance of different machine learning algorithms.

  Extra credit: Perform down-casting (shrink dataset size) https://pypi.org/project/pandas-downcast/

B) Feature engineering: create two new features using the information provided in Table 1. 
  a) weather data
  b) median income

You need to consider the weather information of each store location in particular state and use it as a feature to build the forecasting model.

C) Use the below machine learning algorithms to model n-step ahead forecasting (n = 10).
  Note: First create model without using any external features, and then create model with the external features. 

  Begin with ARIMA and compare the RMSE values for each category. 
  Long short-term memory (LSTM) – Perform hyper-parameter to improve the model. 
  Plot the relevant graphs and tabulate the performance metrics of each model. 

