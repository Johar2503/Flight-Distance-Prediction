# Flight-Distance-Prediction
✈️ Flight Distance Prediction
Predicting flight distances is a critical task in the aviation industry, with applications in fuel estimation, route planning, scheduling, and improving passenger experience. This project builds a machine learning model to predict the distance between two airports using various geographical and operational features.

🧠 Problem Statement
Airlines require accurate predictions of flight distances to:

Optimize fuel consumption

Plan efficient flight paths

Enhance scheduling accuracy

Improve overall operational performance

Your task is to predict the flight distance using features like:

Origin and destination coordinates (latitude, longitude)

Great Circle Distance

Timezone differences

Continent information (origin & destination)

Route popularity

🗃️ Dataset Features
Feature	Description
Origin Latitude	Latitude of departure airport
Origin Longitude	Longitude of departure airport
Destination Latitude	Latitude of arrival airport
Destination Longitude	Longitude of arrival airport
Great Circle Distance	The shortest distance between two points on a sphere
Timezone Difference	Time difference between origin and destination
Continent Origin	Continent of departure airport
Continent Destination	Continent of arrival airport
Route Popularity	Popularity score of the given flight route

🔍 How We Solved It
1. 📊 Data Preprocessing
Identified and handled missing values

Removed irrelevant or redundant columns

Encoded categorical features where necessary

2. ⚙️ Model Development
Implemented machine learning models:

Linear Regression

Random Forest Regressor

3. 🔧 Model Optimization
Applied Grid Search CV for hyperparameter tuning

Trained models using the processed dataset

4. ✅ Validation & Testing
Validated models to ensure generalization on unseen data

Evaluated performance using appropriate regression metrics

Generated predictions in required format for submission
