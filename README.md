# Earthquake Prediction

It is well known that if a disaster has happened in a region, it is likely to happen there again. Some regions really have frequent earthquakes, but this is just a comparative quantity compared to other regions. So, predicting the earthquake with Date and Time, Latitude and Longitude from previous data is not a trend which follows like other things, it is natural occuring.

# About Dataset
Dataset is taken from Kaggle , https://www.kaggle.com/datasets/usgs/earthquake-database
This dataset includes a record of the date, time, location, depth, magnitude, and source of every earthquake with a reported magnitude 5.5 or higher since 1965.

# Algorithm used
 RandomForestRegressor and to improve it GridSearchCV

#Steps
1.Import the necessary libraries required for buidling the model 
 a. numpy
 b. pandas
 c. matplotlib
 d. Sklearn
 e. datetime
 f. basemap
 
 2. Data loading and cleaning
  a. Used pandas to load data from CSV file 
  b. Changing date time to tiemstamp
  c. Visulazing data on world map
  
 3. Training Model 
  a. Splitting Data 
  b. RandomForest Regression 
  c. GridSearchCV
  
 4. Evulating model 
  a. RandomForest Regression   score >85%
  b. GridSearchCV   score >90%
  
