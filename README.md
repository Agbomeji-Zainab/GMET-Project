# Predicting Calories Burned with Decision Trees

This project predicts the number of calories burned based on various features like exercise duration, workout type, and many more using a **Decision Tree** machine learning model.

## Project Overview

In this project, I use a **gym dataset** containing information about different exercises performed, including the duration of the workout, type of exercise, and other features. 
The goal is to predict the number of **calories burned** based on these input features using **Decision Trees**, a popular machine learning algorithm.

## Dataset

The dataset used in this project contains the following columns:
- **Age**
- **Gender**
- **Weight(kg)**
- **Height(m)**
- **max_BPM**
- **avg_BPM**
- *resting_Bpm**
- ** session Duration**
- **Calories Burned**
- **Workout Type** 
- **Intensity**
- **Fat Percentage**
- **Water_Intake (liters)**
- **Workout_Frequency (days/week)**
- **Experience_Level**
- **BMI**


## Libraries Used
- `Pandas`: For data manipulation and cleaning.
- `NumPy`: For numerical operations.
- `Matplotlib` and `Seaborn`: For data visualization.
- `Scikit-learn`: For building and evaluating the decision tree model.

## Results

The decision tree model performed well in predicting the number of calories burned, with an **R² score** of 0.7633 on the test data.
