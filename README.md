# Sales Prediction Project

   ![image](https://github.com/JoeBwonKenobi/Sales-Prediction-Project/assets/117705408/74fbead5-6035-4ce9-9140-e6ca2058c07b)

This project will predict sales for food items sold in various supermarket stores.

# Description

The goal of this project is to help the retailer understand the properties of products and outlets that play crucial roles in predicting sales for a supermarket chain. I extracted, processed, and analyzed the dataset to prepare it for machine learning. Then, by developing sales prediction models using Linear Regression, KNN, and Random Forest Regressor models, I was able to create sales predictions for the stakeholders. To help the stakeholders better understand my findings, I've provided in-depth visualizations that show the trends and correlations that affect sales. The stakeholders can use these valuable insights, along with the predictive models, to make informed decisions.

# Data

Here is the link to the original data:

https://drive.google.com/file/d/1syH81TVrbBsdymLT_jl2JIf6IjPXtSQw/view

# Methods:

Before we start working with the data to teach the machine, we need to clean it up and make sure everything looks good. So we'll remove any duplicate information and check to make sure there aren't any mistakes. Then we'll separate the data into different groups: one group that will be used to teach the machine (the "features" or X), and another group that we want the machine to learn (the "target" or y).

We'll also divide the data into training and testing groups so that we can check how well our machine is learning. To get the data ready for the machine, we'll use a set of tools called a "preprocessing object." One of the things we'll do with this is fill in any missing information.

Once everything is set up, we'll build different machine models to try to get the best results. We'll use the training data to teach each model, and then we'll tweak the models until they work as well as possible. Finally, we'll use the best model to analyze the testing data and see how well it works.

Here are the steps taken in each part of the project and the notebooks associated with them:

1.Set up a GitHub account and a repository for the project that includes a template notebook for the project.

https://github.com/JoeBwonKenobi/Sales-Prediction-Project/blob/main/Sales_Project_Template.ipynb

2.Import the data and clean it.

https://github.com/JoeBwonKenobi/Sales-Prediction-Project/blob/main/Sales_Project_Data_Cleaning.ipynb

3.Create visualizations that assist in the analysis of the data.

https://github.com/JoeBwonKenobi/Sales-Prediction-Project/blob/main/Sales_Project_Data_Visualizations.ipynb

4.Feature identification, null values, use EDA to create visualizations.

https://github.com/JoeBwonKenobi/Sales-Prediction-Project/blob/main/Sales_Project_EDA_Visualizations.ipynb

5.Start cleaning process over by importing the orignial dataset again, ensuring there was no data leakage. Preprocess the data for modeling.

https://github.com/JoeBwonKenobi/Sales-Prediction-Project/blob/main/Sales_Project_Preprocessing.ipynb

6.Build several machine learning models to predict the sales of the supermarkets and analize the results.



# Visualizations:

The 
Outlet Sales vs. Food category count

![image](https://user-images.githubusercontent.com/117705408/235286820-09e4f7f5-f661-4382-9515-c3c331e7605b.png)


## **Interpretation:**

The top-selling item type was fruits and vegetables, closely followed by snack foods. Dairy placed fifth in front of canned foods, while breakfast and seafood were the two lowest.


Outlet Sales vs. Item Type

![image](https://user-images.githubusercontent.com/117705408/235287026-1d9219a9-3388-4744-867c-84932cdf801a.png)



## **Interpretation:**

Here we see that the top-selling outlet type was that of tier 3, followed by tier 2, and then tier 1 was the lowest selling outlet type.

# Description of Final Model choice:

Used a Random Forest Regressor Model as our final model. Here, we saw the best results in terms of the regression metrics and the model's performance. This model still has some bias. However, this model has the best performance on the testing set. For the R^2 score, 60.4% of the variance is explained. For the MAE, the testing score is off by about 728.039.

# Recommendations:

Overall, the best model is definitely the tuned Random Forest Regressor Model. There was still some bias in the model, but by far, it outperformed the linear regression model. This model could be used to make predictions to a point; they would only be so accurate because of the data the model was trained on. With more data, the accuracy could greatly increase.

# Limitations & Next Steps
There were no immediate limitations throughout this project. However, with more data, a much more accurate model could be trained and then used to make better predictions. I'm limited to the data I was given; this was also my first project in Coding Dojo.

# For further information
For any additional questions, please contact davydronez@gmail.com
