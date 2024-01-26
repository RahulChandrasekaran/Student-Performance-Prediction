Student Performance Prediction
Overview
This project focuses on predicting students' performance in mathematics based on various factors such as gender, race/ethnicity, parental level of education, lunch type, and completion of a test preparation course. The goal is to understand the influence of these factors on students' math scores and build a predictive model.

Dataset
The dataset used in this project is sourced from Kaggle and consists of information about students' demographics, test scores, and other relevant attributes. The dataset can be found here.

The dataset includes the following columns:

gender
race/ethnicity
parental level of education
lunch
test preparation course
math score
reading score
writing score
Project Structure
The project is organized into several stages:

Understanding the Problem Statement: Clearly define the problem statement, which is to predict students' math scores based on various factors.

Data Collection: Import the dataset from Kaggle using pandas and explore its structure.

Data Checks and Exploration: Perform data checks such as checking for missing values, duplicates, and data types. Explore the data through summary statistics and visualizations.

Model Training: Prepare the data for training by handling categorical variables and splitting it into training and testing sets. Train multiple regression models, including Linear Regression, Lasso, Ridge, K-Neighbors Regressor, Decision Tree, Random Forest, XGBRegressor, CatBoostRegressor, and AdaBoost Regressor.

Evaluation: Evaluate the performance of each model on both the training and testing sets using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R2 Score.

Conclusion: Summarize the findings and insights gained from the exploratory data analysis and model training. Discuss the impact of different factors on students' math scores.

Results
The project provides insights into the factors influencing students' math scores and compares the performance of various regression models in predicting these scores.
