# Boston-Airbnb-EDA-and-Insight



### About the Analysis:

Airbnb is one of the widely used platform by hosts to accommodate guests for lodging and tourism-related activities.
We will be analyzing the Boston Airbnb data to get more insight into it . It will include prediction about the pricing and various factors influencing the pricing related to listing by hosts.


### About the Data:

The data in consideration includes three files, named as;
1. Listings: It contains useful information related to listings since 2016 to 2018. e.g. Host information, pricing, amenities, location, property type,ratings, price etc.
2. Reviews: It has reviews related to listings from customers.
3. Calendar: It has listings availability and pricing related information for a particular day.

### Details of the Analysis:

In this analysis we have performed the Exploratory Data Analysis on the Boston AirBNB data, identified the factors influencing the prices of the listings in and around Boston area. Finally a model has been created to predict the price of listing using the important variables and most important features according to the model are identified. This is a SUPERVISED LEARNING REGRESSION PROBLEM

#### Libraries used:
1. numpy, pandas and seaborn etc. to clean, gather and visualize the data. 
2. scikit learn library to build our predictive models.

#### Models used:
1. Linear Regression
2. RandomForest Regression

#### Insights and model performance:

1. The linear regression model gave a r_squared value of 0.41
2. The RandomForest Model improved the model performance and gave a r_squared value of 0.6
3. The most important variables are number of bedrooms, availability, host_listing count and number of reviews


#### Medium Blogpost details

There is a blog post posted at medium with the analysis related to "Insight into Airbnb data using python, EDA and simple Machine learning techniques". The Blog Post can be accessed at https://sadique2abdullah.medium.com/insight-into-airbnb-data-using-python-eda-and-simple-machine-learning-techniques-f191295766bc.


##### Acknowledgements:
The data was accessed from Kaggle: https://www.kaggle.com/airbnb/boston
