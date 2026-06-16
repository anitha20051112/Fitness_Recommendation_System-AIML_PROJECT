# Fitness_Recommendation_System-AIML_PROJECT
Machine Learning based Fitness Recommendation System using KNN to suggest personalized workout plans based on user fitness and health data.

# Fitness Recommendation System

## Project Overview

The Fitness Recommendation System is a Machine Learning-based application that recommends suitable workout types based on a user's fitness and health-related information. The system analyzes factors such as age, gender, body measurements, heart rate data, calorie expenditure, and workout habits to provide personalized fitness recommendations.

The project uses the K-Nearest Neighbors (KNN) algorithm to identify patterns in fitness data and suggest the most appropriate workout category.

---

## Features

* Personalized workout recommendations
* User fitness profile analysis
* Machine Learning-based prediction
* K-Nearest Neighbors (KNN) algorithm
* Data preprocessing and feature encoding
* Easy-to-use recommendation system
* Supports multiple workout categories

---

## Technologies Used

### Programming Language

* Python

### Libraries and Frameworks

* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

### Machine Learning Algorithm

* K-Nearest Neighbors (KNN)

---

## Dataset

This project uses the Gym Members Exercise Tracking Dataset containing fitness and health-related information of gym members.

### Features Used

* Age
* Gender
* Weight (kg)
* Height (m)
* Max BPM
* Avg BPM
* Resting BPM
* Session Duration (hours)
* Calories Burned
* Fat Percentage
* Water Intake (liters)
* Workout Frequency (days/week)

### Target Variable

* Workout_Type

The model predicts the most suitable workout type based on the user's fitness profile.

---

## Project Workflow

1. Load the fitness dataset.
2. Preprocess and clean the data.
3. Encode categorical features such as Gender and Workout Type.
4. Split the dataset into training and testing sets.
5. Train the KNN model.
6. Accept user fitness information as input.
7. Generate a workout recommendation.
8. Display the recommended workout type.

---

## Example Prediction

Input:

```python
example_user = {
    "Age": 28,
    "Gender": "Male",
    "Weight (kg)": 72,
    "Height (m)": 1.75,
    "Max_BPM": 190,
    "Avg_BPM": 140,
    "Resting_BPM": 65,
    "Session_Duration (hours)": 1.0,
    "Calories_Burned": 500,
    "Fat_Percentage": 18,
    "Water_Intake (liters)": 2.5,
    "Workout_Frequency (days/week)": 4
}
```

Output:

```text
Recommended Workout: Flexibility
```

---

## Files Included

* Fitness Recommendation System.ipynb – Main project notebook
* requirements.txt – Required Python libraries
* README.md – Project documentation
* gym_members_exercise_tracking_synthetic_data.csv – Dataset used for training and testing

---

## Applications

* Personalized Fitness Planning
* Gym Recommendation Systems
* Health Monitoring Platforms
* Wellness and Lifestyle Applications

---

## Conclusion

This project demonstrates how Machine Learning can be used to provide personalized workout recommendations based on an individual's fitness profile. By leveraging the KNN algorithm, the system helps users identify suitable workout routines that align with their health and fitness characteristics.

