# Food_Delivery_Time_Prediction

## Data Loading and Preprocessing:

The code starts by importing necessary libraries and loading training and test datasets (Train_Food.csv and Test_Food.csv).
Data preprocessing steps include dropping unnecessary columns, handling missing values, converting data types, calculating distances between coordinates, and extracting features from datetime columns.

## Exploratory Data Analysis (EDA):

Various exploratory data analysis tasks are performed, such as analyzing value counts of categorical variables, plotting histograms, and creating correlation matrices.

## Feature Engineering:

Feature engineering involves encoding categorical variables using label encoding and creating new features from datetime columns.

## Model Building:

The code uses the XGBoost regressor for training a predictive model to estimate the delivery time.
It splits the data into training and testing sets, scales the features, and trains the model.
Model evaluation metrics like R-squared score are computed, and predictions are made on the test set.

## Visualization:

Scatter plots are created to visualize the relationship between actual and predicted delivery times.

## Applying Model to Test Data:

The trained model is applied to the test dataset to predict delivery times.
