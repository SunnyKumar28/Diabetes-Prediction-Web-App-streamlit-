# Diabetes Prediction Web App

This web application predicts the likelihood of diabetes based on several health metrics. It uses a Support Vector Classifier (SVC) machine learning model trained on a dataset with relevant features.

## Features

The prediction is based on the following features:
- **Number of Pregnancies**: The number of times the patient has been pregnant.
- **Glucose Level**: Plasma glucose concentration a few hours after a meal.
- **Blood Pressure Value**: Diastolic blood pressure (mm Hg).
- **Skin Thickness**: Triceps skinfold thickness (mm).
- **Insulin Level**: 2-Hour serum insulin (mu U/ml).
- **BMI Value**: Body mass index (weight in kg/(height in m)^2).
- **Diabetes Pedigree Function**: A function that scores the likelihood of diabetes based on family history.
- **Age**: The age of the patient.

## How to Use

1. Go to the [Diabetes Prediction Web App](https://zscdn5cwzjmhmxjntf62si.streamlit.app/).
2. Enter the required values for each feature in the provided input fields.
3. Click on the **Predict** button.
4. The app will display the prediction result indicating whether the patient is likely to have diabetes or not.

## Technical Details

- **Model**: The prediction is made using a Support Vector Classifier (SVC) model.
- **Framework**: The web app is built using Streamlit, an open-source app framework for Machine Learning and Data Science projects.

## Installation (for local development)

To run the app locally, follow these steps:

1. Clone the repository:

```sh
git clone https://github.com/yourusername/diabetes-prediction-app.git
