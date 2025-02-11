# Netflix_Project
# Netflix Movie Recommendation System 🎬📊
# Overview
# This project implements a Netflix Movie Recommendation System using collaborative filtering and Singular Value Decomposition (SVD). The dataset consists of user ratings for various movies, and the model predicts personalized movie recommendations.
# Dataset 📂
# Netflix user ratings dataset containing:
# Movie_Id → Unique movie identifier
# Customer_id → Unique user identifier
# Rating → Movie rating (1-5 stars)
# Movie Titles dataset (movie_titles.csv) containing:
# Movie_Id, Year, Name
# Technologies Used 🛠
# Python (pandas, NumPy, matplotlib)
# Scikit-Surprise (for SVD-based recommendations)
# Data Processing: Pivot tables, filtering inactive users/movies
# Machine Learning Model: SVD (Singular Value Decomposition)
# Project Workflow 🔄
# 1️⃣ Data Preprocessing
Load and clean the dataset
Handle missing values
Assign Movie_IDs correctly
# 2️⃣ Exploratory Data Analysis
Distribution of Ratings
Remove inactive users and less-rated movies
# 3️⃣ Building the Ratings Matrix
Convert dataset into a user-item rating matrix
# 4️⃣ Model Training
Train a SVD-based collaborative filtering model
Use cross-validation to evaluate RMSE & MAE
# 5️⃣ Making Predictions
Find highly-rated movies by a given user
Generate personalized recommendations
