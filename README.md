# MLP-11
time series forecasting hourly energy consumption using prophet 
MLP 11 - Time series forecasting hourly energy consumption using prophet

Industry 
Energy sector | Utilities

Skills
Python | Time series | Data manipulation | FBprophet

Problem statements
Predict energy consumption. 

Data Structure 
PJM Hourly Energy Consumption Data
PJM Interconnection LLC (PJM) is a regional transmission organization (RTO) in the United States. It is part of the Eastern Interconnection grid operating an electric transmission system serving all or parts of Delaware, Illinois, Indiana, Kentucky, Maryland, Michigan, New Jersey, North Carolina, Ohio, Pennsylvania, Tennessee, Virginia, West Virginia, and the District of Columbia.
The hourly power consumption data comes from PJM's website and are in megawatts (MW).
The regions have changed over the years so data may only appear for certain dates per region.

Methods 
Train/test split data
  Create time series features based on time series index.
'hour, 'dayofweek', 'quarter','month','year','dayofyear','dayofmonth' and 'weekofyear'
Visualize our Feature / Target Relationship using boxplots (hr of the day vs energy consumption and month vs energy consumption)
Create model with XGBoost regressor and set parameters 
Fit model to training dataset
Investigate feature importance with bar plot 
Investigate ground through vs predicted values
Validate model accuracy with RMSE Score on Test set 
Calculate the error of prediction by looking at the worst and best predicted days
Add holidays 
Create new dataframe for future predictions

Results 
Month and hour influences energy consumption the most 
Most energy consumed during winter months 
Most energy consumed during early morning hours
Increase model accuracy with fine tuning model 
