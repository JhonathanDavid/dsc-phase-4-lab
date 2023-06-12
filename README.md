# Phase 4 Project : Time-Series DataSet
# Predictive Modeling 
# REAL ESTATE FORECASTING

![awesome](https://www.construction21.org/data/sources/users/44110/breno-assis-r3wawu5fi5q-unsplash.jpg)

### Project Overview

This project will look into a Real Estate database to find valuable information about the value of homes and return on investment. My company, Xabios data international, has been hired to determind the change of prices in this market over time and to determine which areas have the most potential to increase. Thus, this project is aimed at two very targeted goal using Time Series Modeling :
Jupyter Notebook A brief note on this Jupyter notebook. This notebook presents story line following this structure:
* Part 1: Overview, Business Understanding & Objective 
* Part 2 : EDA
* Part 3 : Modeling
* Part 4 : Conclusion

### Business Modeling Objectives

1. Understand Real Estate Prices - how they have changed overtime 
2. 2. Find out Real Estate Areas of Growth Measured by ROI


### Business Understanding & Business Problem
As important to Telecommunications companies as it is to earn new customers to their services, is the need to retain current customers and preventing them from going to competitors. The act of leaving customers or loss of customers are referred to in this industry as "Churn", from a business perspective. The business would like to understand exactly what factors or situations contribute to churning, and most importantly, post identification of those factors, define precises strategic initiatives to retain customers. This project, therefore aims to help the business first in identifying the attributes and factors that cause the churn, and in turn, building models that can help the business predict it, so that in fact strategic business initiatives can be outlined for solution.


### DataSet & Business Modeling Objectives
The database is a kaggle available dataset called "bigml_59c28831336c6604c800002a.csv" relabeled in this presentation as "Customer_Churn.csv", holding 3,333 values. 
The goal of this lab is to build the following with that data set: 
1) Identifying important attributes or features that are key in predicting customer churn
2) Building a model than can predict who will churn with a high level of accuracy

### Model Considerations Metrics (Recall)

Recall is an important metric in evaluating our model and this kind of problem. Recall pertains to the rate at which the model makes correct predictions about customer churning. Aided by a Confusion Matrix- our goal is to minimize false negatives. Recall is the best metric since failure to identify a customer who is about to churn is more costly from a business persepective, than wrongly classyfing a non-churning customer. A good successful model therefore should have a 80% - 85% recall at the very least. Precision and accuracy are also metrics to have in mind.

### Important Modeling Sucess Considerations

We are conducting a Time Series Analysis over the Zillow Home Value Index (ZHVI):A data set that tracks a sample of real estate prices over time. In particular, a time series allows one to see what factors influence certain variables from period to period. Time series analysis can be useful to see how a given asset, in this case Real Estate, or economic variable, in this case ROI, changes over time.

### Conclusions
to Invest in these ZIP Codes due to Higher ROI
Highest projected ROI:
6069 = 24.12%, 6610 = 31%, 6330 = 21%, 6039 = 19%, 6058 = 19%.

## Summary
```
├── README.md                      <- The top-level README for reviewers of this project
├── Folder                         <- Folder containing 2 ipynbs one for EDA and second for Arima Modeling
├── PDF1_Nontechnical Presentations <- PDF version of Business Power Point 
├── PDF2_Jupyter Notebook.pdf      <- PDF version of ipynb project containing EDA and Arima modeling
└── time series folder             <- contains initial instructions
```
