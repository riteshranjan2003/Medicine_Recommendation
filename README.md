# Medical-Recommendation-System
## Project Overview
This project involves building a machine learning model to predict the disease based on symptom. The system is deployed using Flask, providing an interactive and user-friendly interface for predictions.
## Features
* Data Preprocessing: Handling missing values, encoding categorical data, and scaling features.

* Model Training: Using a Support Vector Classifier for accurate predictions.

* Deployment: Implemented with Flask for an interactive interface.

## Technology Used
* Python

* Jupyter Notebook

* NumPy

* Pandas

* Scikit-learn

* Flask
## Model Training
A Support Vector Classifier is used for training the model. The dataset is split into training and testing sets with a ratio of 70:30.
## Deployment With Flask
Flask is used to create an interactive interface where users can input symptoms and receive predictions about the diseases they might have. The application takes inputs for
* Symptoms
## How to Run the Project
#### 1. Clone the Repository:
```bash
  git clone https://github.com/riteshranjan2003/Medicine_Recommendation.git
```
#### 2. Install the Required Libraries:
```bash
  pip install pandas numpy scikit-learn Flask
```
#### 3. Run the Flask App:
```bash
  python main.py
```
## Usage
1. Open the Flask app in your browser.
2. Enter the required feature values.
3. Click the 'Predict' button to get the predicted disease, a description of the disease, and suggestions for precautions, medications, workouts, and diets.

## Code Structure
* medicine_recommendation.ipynb: Contains the code for data preprocessing and exploratory data analysis.
* main.py: Contains the Flask application code.



