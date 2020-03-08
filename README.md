# predicition_houseprice_for_incubator
For a fictional case I want to predict the houseprice for a newly found incubator (like in the HBO series "Silicon Valley")

# Data Cleaning

The dataset King County Houses is based on sold houses from 2014-2015 in the King County. They include a variety of parameters, which are explained in the column_names.md
The first part of the notebook is for cleaning these data and reduce complexity for the first simple linear regression.

# Linear Regression

The dataset is filtered on the conditions mentioned in the business case. The linear regression is based on the feature sqm which has the highest correlation with the price. The model will be evaluated by a test-set.

# Exploring with mapping

For a better understanding of the location, the dataset will be displayed on a map. Different features can be chosen to be displayed.

# Multilinear regression

In this section there are some functions, which can calculate automatically the model by the desired input features.
The output is the model and some statistics.
The model will be evaluated by a test-set.

# Outlook

The notebook is not finished yet, it needs some more structure and better explonation.
Most importantly the average zipcode price can be explored more.
The feature grading includes in my understanding the feature view in some aspects. Maybe it can be split more into detail, so that in the end we have only a value, which indicates only the value of the location independent from the condition of the house or the individual location (i.e. view only in one direction).