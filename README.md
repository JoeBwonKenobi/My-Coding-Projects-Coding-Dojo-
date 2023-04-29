# Sales Prediction Project

This project will predict sales for food items sold in various stores.

# Description

The goal of this project is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales. I extracted, processed, and analyized the data set to prepare it for machine learning. Then, by developing sales prediction models using Linear Regression, KNN & Random Forest Regressor models I was able to create sales predictions for the stakeholders. To help the stakeholders better understand my findings, I've provided in-depth visualizations that show the trends and coorlations that effect sales. The stakeholders can use these valuable insights, along with the predictive models, to make informed descisions. 

# Data

Here is the link to the original data:

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

# Methods:

Before splitting the data, we will drop and duplicates, and check for any inconsistancies. 
This will help prepare the data for machine learning.
Then I identified the features (X) and the target (y) and performed a validation split.
Next, I created a preprocessing object to prepare the dataset for Machine Learning.
I imputed missing values using the Simple Imputer after the validation split to ensure there was no data leakage. then build the separate models. After running the training data on the models, I tuned them to get the optimal result and then ran the imporoved models on the testing data to get the best version of the best model.

# Visualizations:

The 
Outlet Sales vs. Food category count

![image](https://user-images.githubusercontent.com/117705408/235286820-09e4f7f5-f661-4382-9515-c3c331e7605b.png)


## **Interpretation:**

The top selling Item type was fruits and vegtables, closely followed by snack
foods. Dairy placed fifth infront of canned foods. while breakfast and seafood
were the two lowest.


Outlet Sales vs. Item Type

![image](https://user-images.githubusercontent.com/117705408/210702522-b8da5291-b6f9-4d15-a08e-cd4f3ec955f0.png)



## **Interpretation:**

Here we see that the top selling outlet type was that of tier 3, followed by tier 2, and then tier 1 was the lowest selling outlet type..

# Description of Final Model choice:

Used a Random Forest Regressor Model as our final model. 
Here, we saw the best results as far as the regression metrics and the model's performance.
This model still has some bias. However, this model has the best performance on the testing set.
For the R^2 score 60.4% of the variance is explained.
For the MAE the testing score is off by about 728.039

# Recommendations:

Overall, the best model is definitely the tuned Random Forrest Regressor Model. There was still some bias in the model, but by far it out performed the linesr regression model.

# Limitations & Next Steps
There were no immediate limitations throughout this project. However, with more data a much more accurate model could be trained and then used to make better predictions. I'm limited to the data I was given, this was also my first project in Coding Dojo.

# For further information
For any additional questions, please contact davydronez@gmail.com
