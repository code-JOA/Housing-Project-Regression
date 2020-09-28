# California Housing-Project-Regression


# Author : Joshua Owusu Ankomah



![](https://forthebadge.com/images/badges/made-with-python.svg)




![UCI](https://img.shields.io/badge/Dataset-Kaggle-blue.svg) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg)

<!-- #region -->
# 1. Experimental Projects

### Students who want to suggest alternative projects can do it at any moment.


### Housing prices. Implement from scratch the ridge regression algorithm for regression with square loss (lecture notes on “Linear prediction”). It is OK to use libraries for linear algebra and basic data manipulation (e.g., Numpy and Pandas). Apply the algorithm to the prediction of the label medianHouseValue in this dataset. Study the dependence of the cross-validated risk estimate on the parameter alpha of ridge regression. Try using PCA to improve the risk estimate. Optionally, use nested cross-validated risk estimates to remove the need of choosing the parameter.

## 2. Data
+ Here is a description of the attributes in the dataset : https://www.kaggle.com/camnugent/california-housing-prices

+ longitude: A measure of how far west a house is; a higher value is farther west
+ latitude: A measure of how far north a house is; a higher value is farther north
+ housingMedianAge: Median age of a house within a block; a lower number is a newer building
+ totalRooms: Total number of rooms within a block
+ totalBedrooms: Total number of bedrooms within a block
+ population: Total number of people residing within a block
+ households: Total number of households, a group of people residing within a home unit, for a block
+ medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
+ medianHouseValue: Median house value for households within a block (measured in US Dollars)
+ oceanProximity: Location of the house w.r.t ocean/sea

### Note: The dataset has an attribute with missing values and an attribute with categorical values. Find a way of handling these anomalies and justify your choice.
<!-- #endregion -->

<!-- #region -->
### 3. Evaluation
The evaluation metric for this competetion is the RMSLE (Root Mean Squared Log Error) between the actual data and the predicted house prices as suggested by the competition.

##### Evaluation metrics used for this project
+ $R^2$ or Coefficient of Determination
+ Root Mean Squared Error (RMSE)
+ Mean Squared Error (MSE)
+ Mean Absolute Error (MAE)

For more on the evaluation of this project check:
https://www.kaggle.com/camnugent/california-housing-prices
    
**Note:**  The goal for the regression evaluation metrics is to minimise the error.

### Our Goal:
The goal of this project is to reduce/build a machine learning model to minimise RMSE.

### 3.5. Models Used
+ Linear Regression 
+ Polynomial Regression
+ RandomForestRegresssor

# Fitting model using Random Forest
- Split dataset into train and test set in order to prediction w.r.t X_test
- If needed do scaling of data
- Scaling is not done in Random forest As its an ensemble method made of different decision trees
- Import model
- Fit the data
- Predict w.r.t X_test
- In regression check RSME Score
- Plot graph

### 4.0 Hyperparameter Optimization 
Improving the performance of the model with GridSearchRegressor and RandomSearchCV after using RandomForestRegressor which improved drastically the performance of the model as linear Regression was initially underfitting and Polynomial Regression improved the $R^2$.
- Choose following method for hyperparameter tuning
- RandomizedSearchCV --> Fast as its doesnt iterate through each parameter.  
- GridSearchRegressor  --> Effective but not fast as it iterates through each parameter to find the best.
- Assign hyperparameters in form of dictionery
- Fit the model
- Check best paramters and best score


### 4.5 Features
The features of this project have been added in this google sheets 
https://docs.google.com/document/d/e/2PACX-1vTqeS0WmZDMvxuN8auSIvAVncNg7zSR73Ibz6XaAKOjk7W3QJsAN4j6kJKUZN156f0y1_BUyrgiJSQk/pub

<!-- #endregion -->

```python

```

# Notebook :



### Workflow.
+ Data Prep
+ EDA
+ Feature Selection
+ Build Model
+ Interpret Model
+ Hyperparameter optimization
+ Done

## End-to-end Workflow.

![](images/workflow.png)


```python

```

<!-- #region -->
**Version Control:**  One and only GitHub :heart:

**Language for this project:**  Python <img src="https://img.icons8.com/color/30/000000/snake.png"> ![Python 3.6](https://img.shields.io/badge/Python-3.7-brightgreen.svg)


Please feel free to keep in touch if you have any queries or would like us to work together on a fun project :wink: 


### Connect with me

[<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/linkedin.png">](https://www.linkedin.com/in/joshua-owusu-ankomah-2b5a9898/)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/github.png">](https://github.com/code-JOA)  [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/facebook.png">]() [<img target="_blank" src="https://img.icons8.com/bubbles/100/000000/instagram-new.png">](https://www.instagram.com/jay_rockerfella/)

<!-- #endregion -->

```python

```
