# SAT Score Analysis


 ## Contents:
 
- [Problem Statement](#Problem-Statement)  
- [Data](#Data)
- [Data Dictionary](#Data-Dictionary)
- [Outside Research](#Research)
- [Data Analysis](#Data-Analysis)
- [Conclusions and Recommendations](#Conclusions-and-Recommendations)


## Problem Statement:

I am exploring the financial impact that good architectural design can have on home values. 


## Background:

Architects feel they are adding value but generally don't have any hard numbers to back it up. Using Ames, Iowa as a case study I am investigating what architects can take advantage of to create better designs while increasing value for the client.


## Data

* [train](./datasets/train.csv): Original housing data for Ames, I used for training the model
* [test](./datasets/test.csv): Original housing data for Ames, I used for testing the model
* [train_clean](./datasets/train_clean.csv): Null values removed and many objects converted to numeric values, used for training the model
* [train_clean_outlier](./datasets/train_clean_outlier.csv): Model after removing the outliers, used for training the model
* [train_clean](./datasets/train.csv): Null values removed and many objects converted to numeric values, used for testing the model
* [train lasso](./datasets/train_lasso.csv): Contains one hot encoded features, I used for training the model using lasso
* [test lasso](./datasets/test_lasso.csv): Contains one hot encoded features, I used for testing the model using lasso

## Data Dictionary

The original [data dictionary](http://jse.amstat.org/v19n3/decock/DataDocumentation.txt) that came with the training csv can be found here.

The [data dictionary](data_dictionary.md) that I used in training the model can be found here.

## Outside Research:

Source: https://home-builders.promatcher.com/cost/ames-ia-home-builders-costs-prices.aspx

Data used in the presentation with figures for construction costs in Ames, Iowa.
    

## Data Analysis:

I started by creating a box plot to visualize the distribution of our target variable, Sales Price.

![Box Plot: Overall Sales Prices](images/box_plot_home_prices.png)

I then made two heatmaps, one to see overall correlations and intercorrelations, and the other to see what different correlations exist with Sales Price.

![Correlation Heatmap: Overall](images/overall_heatmap.png)
![Correlation Heatmap: To Sale Price (Target)](images/saleprice_heatmap.png)

After making a list of potential features that were highly correlated with the target variable, I made a pair plot to see if the features also had a linear relationship with Sales Price.

![Pair Plot](images/pair_plot.png)

After adding a few columns that had potential to be exponentially related to Sales Price I ran a Linear Regression model and calculated the Root Mean Squared Error.

To analyze the coefficients I created a scatter plot:

![coefficient plot](images/coefficient values.png)

I then filtered the list of features further by only using the coefficients that affected the price by over $100 per unit change, holding all else constant.

I ran a new Linear Regression model on the data and calculated a new (and slightly higher) Root Mean Squared Error.

I then one hot encoded features and used Lasso to determine the optimal Features to use in the model. After calculating the RMSE, I then ran a standard Linear Regression using only the features from Lasso and without the penalty score, acheived the highest score in the notebook.
    
## Conclusions and Recommendations:

I would recommend to architects that they be intelligent when creating an initial layout for a home. Simple decisions, such as locating the kitchen above ground or adding a fireplace, have significant impact on the overall value of the home.

The overall quality of the home has the greatest impact, so it is in the architect's and client's best interests to move up from an average quality to an excellent quality.

However, the average construction costs in Ames puts the client already towards the upper levels of Sales Prices when they decide to build their home in the first place. Therefore, it is the architect's responsibility to be precise when making recommendations to upgrade.