# Regression_Capstone_Project
Project Title : Seoul Bike Sharing Demand Prediction
Problem Description
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.

Out of all above models Random forest Regressor gives the highest R2 score of 92% for Test Set and XG Boost Gridsearch CV gives the highest R2 score of 93.4% for Test set.

No overfitting is seen.

We can deploy XG Boost Gridsearch CV model.

Hour of the day holds most importance among all the features for prediction of dataset
We observed that the highest number of bike rentals on a clear day and the lowest on a snowy or rainy day
As we can see the top 5 important features of our dataset are: Functioning day,Hour,Season_winter, Temperature,Rainfall,Humidity
Peoples dont use rented bikes in no functioning day.
people tend to rent bikes when the temperature is between -5 to 25 degrees.
people tend to rent bikes when the visibility is between 300 to 1700
for all the above experiments we can conclude that Random Forest and XGBoost regressor with using hyperparameters we got the best results
