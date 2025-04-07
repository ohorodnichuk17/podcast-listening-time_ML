# Podcast Listening Time Prediction

Welcome to my first machine learning project! In this project, I work on predicting the listening time of podcast episodes using data from the 2025 Kaggle Playground Series competition.

## Project Overview

The task is to predict the "Listening_Time_minutes" for podcast episodes. The dataset contains various features, and the goal is to train a model that can predict the listening time for each podcast episode in the test set.

## Data

The dataset contains two main components:

- **Training Set:** Features related to each podcast episode.
- **Test Set:** Features for podcast episodes, where you need to predict the "Listening_Time_minutes" and submit the results.

## Approach

1. **Data Preprocessing:**
   - Handle missing values using various imputation techniques.
   - Normalize numerical features for better model performance.
   
2. **Model Selection:**
   - I used **Linear Regression** as the base model for prediction.
   - Multiple experiments were done to tune the model and improve its performance.

3. **Model Training:**
   - The model was trained on the training dataset, and predictions were made on the test dataset.

4. **Evaluation:**
   - The model's predictions were evaluated using MAE and RMSE metrics.

