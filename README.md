## Flight Price Prediction using Machine Learning
## Project Overview

This project focuses on predicting airline ticket prices using Machine Learning techniques. The objective is to build a regression model that can estimate flight prices based on various travel-related factors such as airline, source city, destination city, departure time, arrival time, travel class, number of stops, flight duration, and days left before departure.

The project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

## Dataset Information

The dataset contains flight-related information such as:

Airline
Flight Number
Source City
Destination City
Departure Time
Arrival Time
Number of Stops
Travel Class
Flight Duration
Days Left Before Departure
Flight Price (Target Variable)
Target Variable
Price

The goal is to predict the flight ticket price using the available features.

## Project Workflow
1. Data Collection
Imported the flight price dataset.
Loaded the dataset using Pandas.
2. Data Preprocessing
Removed unnecessary columns.
Checked and handled missing values.
Encoded categorical variables using Label Encoding.
Prepared the dataset for machine learning models.
3. Exploratory Data Analysis (EDA)
Analyzed feature distributions.
Identified relationships between variables.
Visualized trends using Matplotlib and Seaborn.
4. Feature Selection

Selected important features affecting ticket prices:

Airline
Flight
Source City
Destination City
Departure Time
Arrival Time
Stops
Travel Class
Duration
Days Left
5. Model Building

Implemented and compared multiple regression algorithms:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
6. Model Evaluation

Evaluated model performance using:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
7. Prediction

Used the trained model to predict flight prices for new flight records.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Machine Learning Concepts Applied
Data Cleaning
Feature Engineering
Label Encoding
Train-Test Split
Regression Analysis
Decision Tree Regression
Random Forest Regression
Model Evaluation
Price Prediction
Key Learnings

Through this project, I gained hands-on experience in:

Building an end-to-end Machine Learning pipeline.
Handling and preprocessing real-world datasets.
Working with categorical and numerical features.
Training and evaluating regression models.
Comparing model performance using multiple evaluation metrics.
Making predictions on unseen data.
Results

The trained model successfully predicts flight ticket prices based on travel details. Among the tested algorithms, tree-based models such as Decision Tree Regressor and Random Forest Regressor provided better performance compared to basic linear models, capturing complex relationships within the dataset more effectively.

Future Improvements
Hyperparameter Tuning using GridSearchCV.
Feature Importance Analysis.
Deployment using Flask or Streamlit.
Real-time Flight Price Prediction Web Application.
Integration with live flight datasets.
