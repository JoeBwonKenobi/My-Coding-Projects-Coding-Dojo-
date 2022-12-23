# Sales Prediction Project

This project will predict sales for food items sold in various stores.

# Description

The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. To help our stakeholders better understand, we will provide in-depth visualizations that show what we have found.
#Data

Here is the link to the original data:

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

#Methods:

Before splitting the data, we will drop and duplicates, and check for any inconsistancies. 
This will help prepare our dat for machine learning.
Then We identified the features (X) and the target (y).
Then we performed a validation split.
Next we created a preprocessing object to prepare the dataset for Machine Learning.
We imputed missing values using the Simple Imputer after the validation split to 

#Models:

Outlet Sales vs. Food category count



![Model 1](https://user-images.githubusercontent.com/117705408/209273225-32b196b4-e6cb-4693-816e-91c8f409e969.png)

Interpretation:

Here we see that the highest sold item in the outlets is starchy food, while the other catrgory is the lowest.


Outlet Sales vs. Item Type

![Model 2](https://user-images.githubusercontent.com/117705408/209273528-4a571e5a-3ca7-4ffd-8d25-1e6325468580.png)

Interpretation:

Here we see that tier 2 has the highest sales, while teir 1 has the lowest.

#Description of Model:

For the final model, we choose the Rndom Tree Regression Model
It has some bias, but overall it has the highest testing score.
Report the most important metrics
Refer to the metrics to describe how well the model would solve the business problem

Recommendations:

It's important to know the best max depth and estimators.
For this model the best max depth is 5 and the best estimators is 92.

Limitations & Next Steps
There were no limitations theoughout this project.

For further information
For any additional questions, please contact davydronez@gmail.com
