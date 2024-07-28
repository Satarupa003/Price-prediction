# Price-prediction
Predicting the price of real estate by the factors of location, square-feet area, number of bathrooms and bedrooms.
Before procceding towards creating model, data cleaning has been done using Pandas and Numpy.
The datas has been loaded from csv to dataframe using Pandas library of Python.
By using MatplotLib and visualizing the datas, some more modification has been made.
As dealing with charecters is not easy for machine, we have used 'One Hot Encoding' to create columns by the name of locality where the places were represented by binaries(0/1).
K fold cross validation also have used to measure the accuracy.
BY using GridsearchCV the best model has found for the prediction.
During model building I came across all data science concepts such as data load and cleaning, outlier detection and removal, feature engineering, dimensionality reduction, gridsearchcv for hyperparameter tuning, k fold cross validation etc.

#Technologies used:
Python
Numpy and Pandas for data cleaning
Matplotlib for data visualization
Sklearn for model building
Google Collab fpr IDE
