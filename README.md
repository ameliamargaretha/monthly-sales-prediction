# Monthly Sales Prediction using LSTM

by: Amelia Margaretha (152236035100-393)

dataset: Sample - Superstore

This project is created as the final project for Kominfo Professional Academy: Machine Learning. In this project, I did some basic exploration and build a very simple LSTM model to predict monthly sales at Superstore.

The data is grouped by month, because it is more natural to predict sales in monthly basis rather than daily basis. In addition, since the prediction is made in a monthly basis, it can be used by the management to set target sales which usually made in monthly basis.

The model is build in a way that it is using the past 12 months of sales data to make predictions. So it's like, we need sales data from Jan to Dec '21 to predict sales in Jan '22. 

The model also used the sales difference for training and validation, not the actual sales value. This is because I want the data to be more stationary in order to improve the model performance. 
