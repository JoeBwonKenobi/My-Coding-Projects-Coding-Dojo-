![New](https://user-images.githubusercontent.com/117705408/210468337-38bffb62-4028-414c-8056-9e2feeec73aa.png)
# Sales Prediction Project

This project will predict sales for food items sold in various stores.

# Description

The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. To help our stakeholders better understand, we will provide in-depth visualizations that show what we have found.
# Data

Here is the link to the original data:

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

# Methods:

Before splitting the data, we will drop and duplicates, and check for any inconsistancies. 
This will help prepare our dat for machine learning.
Then We identified the features (X) and the target (y).
Then we performed a validation split.
Next we created a preprocessing object to prepare the dataset for Machine Learning.
We imputed missing values using the Simple Imputer after the validation split to 

# Models:

Outlet Sales vs. Food category count



![Model 1](https://user-images.githubusercontent.com/117705408/209273225-32b196b4-e6cb-4693-816e-91c8f409e969.png)

Interpretation:

Here we see that the highest sold item in the outlets is starchy food, while the other catrgory is the lowest.


Outlet Sales vs. Item Type

![New](https://user-images.githubusercontent.com/117705408/210468337-38bffb62-4028-414c-8056-9e2feeec73aa.png)

Interpretation:

Here we see that tier 2 has the highest sales, while teir 1 has the lowest.

# Description of Model:

Used a Random Forest Regressor Model as our final model. 
Here, we saw the best results as far as the regression metrics and the model's performance.
This model still has some bias. However, this model has the best performance on the testing set.
For the R^2 score 60.4% of the variance is explained.
For the MAE the testing score is off by about 728.039

# Recommendations:

It is important to know what you Best Max Depth is along with your Best Estimators are. 
Based on this model the best Max depth is 5 and the Best Estimator is 92.

# Limitations & Next Steps
There were no limitations theoughout this project.

# For further information
For any additional questions, please contact davydronez@gmail.com
