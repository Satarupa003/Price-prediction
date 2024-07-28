# Price-prediction
Predicting the price of real estate by the factors of location, square-feet area, number of bathrooms and bedrooms.
Before procceding towards creating model, data cleaning has been done using Pandas and Numpy.
The datas has been loaded from csv to dataframe using Pandas library of Python.
By using MatplotLib and visualizing the datas, some more modification has been made.
As dealing with charecters is not easy for machine, we have used 'One Hot Encoding' to create columns by the name of locality where the places were represented by binaries(0/1).
K fold cross validation also have used to measure the accuracy.
BY using GridsearchCV the best model has found for the prediction.
