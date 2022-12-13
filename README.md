# Python-Project_Crime
Final project about the Data Science1 course


## Data Clean and Incarceration Prediction
Link: [001_Data_Clean_002_Prediction_incarceration.ipynb](https://github.com/JiaqinWu/Final-Project-Group5/blob/main/Code/001_Data_Clean_002_Prediction_incarceration.ipynb)

In this notebook, we first selected the *"sentencing_asof0405.csv"* and *"Police_Stations.csv"* files, cleaned and merged the data, selected the columns we wanted to use for the prediction model, and created a new data set called *"new_df"*. We changed the Boolean value of binary variables in the cleaned data set into integer values, selected **"Incar"** as the dependent variable and the other 30 variables as independent variables, and did the descriptive analysis on the relationship between the independent variables and the dependent variable. To begin with our prediction, we splitted the whole data set into the training set and test set. Then, we selected 4 models, including **Logistic Regression Model**, **KNN Classifier**, **Decision Tree Classifier**, and **Random Forest Classifier** to predict whether the defendants would be incarcerated or not, compared the prediction results of each model, and adjusted the parameters of part of the models to achieve the best performance.

## Data Clean and Sentence Length Prediction
Link: [001_Data_Clean_003_Prediction_Sentence_Length.ipynb](https://github.com/JiaqinWu/Final-Project-Group5/blob/main/Code/001_Data_Clean_003_Prediction_Sentence_Length.ipynb)

In this notebook, we first selected the *"sentencing_asof0405.csv"* and *"Police_Stations.csv"* files, cleaned and merged the data, selected the columns we wanted to use for the prediction model, and created a new data set called *"new_df"*. We changed the Boolean value of binary variables in the cleaned data set into integer values, selected **"senlength"** as the dependent variable and the other 30 variables as independent variables, and did the descriptive analysis on the relationship between the independent variables and the dependent variable. To begin with our prediction, we splitted the whole data set into the training set and test set. Then, we selected 7 models, including **linear regression model**, **Ridge regression model**, **Lasso model**, **ElasticNet model**, **KNN Regressor**, **Decision Tree Regressor**, and **Random Forest Regressor** to predict how long the defendants would be sentenced, compared the prediction results of each model, and adjusted the parameters of part of the models to achieve the best performance.

## Data Visualization
Link: [001_Data_Clean_004_Data_Visualization.ipynb](https://github.com/JiaqinWu/Final-Project-Group5/blob/main/Code/001_Data_Clean_004_Data_Visualization.ipynb)

In this notebook, we first selected the *"sentencing_asof0405.csv"* and *"Police_Stations.csv"* files, filtered the defendants whose **"LAW_ENFORCEMENT_UNIT"** information were missing or not police stations in Chicago, and created a new data set including the **"LATITUDE"** and **"LONGITUDE"** information of the law enforcement unit through inner merge these two data sets. We also inputted a JSON file *"Boundaries - Neighborhoods.geojson"* to visualize the neighborhood distribution in Chicago. Then we plotted the **Distribution Map**, **Choropleth Map**, and **Heat Map** of defendants in Chicago according to the geographic information and history arrest defendant amount information of each police station to explore which area in Chicago were with most defendants.

