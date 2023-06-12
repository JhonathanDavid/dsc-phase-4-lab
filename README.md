# Phase 4 Project : Time-Series DataSet
# Predictive Modeling 
# REAL ESTATE FORECASTING

![awesome](https://images.sw.cdn.siemens.com/siemens-disw-assets/public/5On2CPXFPpWpiTstd3DJsB/hu-HU/5G-Solutions-hero-1280x720.jpg?w=500&fit=max&q=50&dpr=2&auto=format)

### Project Overview

Syria Tel is a telecommunication company- mobile network- provider in Syria, founded in 2000. Using the DataSet holding Syria Tel Customer Churn information available on Kaggle, this project aims to build a best in class Machine Learning Algorithm, that can predict which and how many customers will churn based on the information available on the dataset

### Background
As important to Telecommunications companies as it is to earn new customers to their services, is the need to retain current customers and preventing them from going to competitors. The act of leaving customers or loss of customers are referred to in this industry as "Churn", from a business perspective. The business would like to understand exactly what factors or situations contribute to churning, and most importantly, post identification of those factors, define precises strategic initiatives to retain customers. This project, therefore aims to help the business first in identifying the attributes and factors that cause the churn, and in turn, building models that can help the business predict it, so that in fact strategic business initiatives can be outlined for solution.

### Business Understanding & Business Problem
As important to Telecommunications companies as it is to earn new customers to their services, is the need to retain current customers and preventing them from going to competitors. The act of leaving customers or loss of customers are referred to in this industry as "Churn", from a business perspective. The business would like to understand exactly what factors or situations contribute to churning, and most importantly, post identification of those factors, define precises strategic initiatives to retain customers. This project, therefore aims to help the business first in identifying the attributes and factors that cause the churn, and in turn, building models that can help the business predict it, so that in fact strategic business initiatives can be outlined for solution.


### DataSet & Business Modeling Objectives
The database is a kaggle available dataset called "bigml_59c28831336c6604c800002a.csv" relabeled in this presentation as "Customer_Churn.csv", holding 3,333 values. 
The goal of this lab is to build the following with that data set: 
1) Identifying important attributes or features that are key in predicting customer churn
2) Building a model than can predict who will churn with a high level of accuracy

### Model Considerations Metrics (Recall)

Recall is an important metric in evaluating our model and this kind of problem. Recall pertains to the rate at which the model makes correct predictions about customer churning. Aided by a Confusion Matrix- our goal is to minimize false negatives. Recall is the best metric since failure to identify a customer who is about to churn is more costly from a business persepective, than wrongly classyfing a non-churning customer. A good successful model therefore should have a 80% - 85% recall at the very least. Precision and accuracy are also metrics to have in mind.

### Business Conclusion & Recommendations

For Syria tel, customer service is a key differentiatior. Syria tel should focus on training programs to enhance this features that mostly need to reduce the number of minutes spent by a customer on the phone. Therefore effective communication training to customer service representatives is a key success factor. When a customer spends or makes 3 or more phone calls to customer service, this is an indication of higher churn. So providing customer incentives provided at the third call will be a recommendation.

The most important features in predicting churn are :

* The total number of minutes that the customer has done during the day
* The total number of evenining minutes
* The number of customer calls to customer service
* The total international minutes in international calls

The business recommendation to Syria Tel includes:
* For Syria tel, customer srvice is a key differentiatior. Syria tel should focus on training programs to enhance this features that mostly need to reduce the number of minutes spent by a customer on the phone. 
* Effective communication training customer service representatives is a key success factor. When a customer spends a higher number of minutes on the phone, this is an indication of higher churn. 
* Providing customer incentives provided at the third call 

The modeling- next steps recommendations & conclusions
The best performing model at a targeted level of 85% is not achieved by best model, however did a achieve a near 80%. There is still some overfitting, thus increasing the training data set should reduce the overfitting and improve performance. 

## Summary
```
├── README.md                      <- The top-level README for reviewers of this project
├── index.ipynb                    <- Jupyter notebook. Overview, Business Problem, Data Understanding.Modelin
├── index.pdf                      <- PDF version of project presentation
├── data                            <- the database used 
└── BusinessPresentation.pdf        <- pdf of business presentation
└── Regression.png                  <- image sourced internally from notebook
```
