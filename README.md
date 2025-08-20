# Heart Disease Prediction using Machine Learning

This project utilizes machine learning algorithms to predict the likelihood of heart disease based on patient data. It includes preprocessing, feature extraction, and model training with algorithms such as **SVM** and **KNN**.

## Overview

The project analyzes a dataset containing various medical attributes like cholesterol levels, age, blood pressure, and more. Using **Support Vector Machine (SVM)** and **K-Nearest Neighbors (KNN)**, the system predicts whether a person is at risk of heart disease.

## Features

- **Data Preprocessing**: Handles missing values, encoding categorical variables, and transforming data types for model compatibility.
- **Feature Engineering**: Extracts and analyzes relevant features from the dataset (e.g., age, cholesterol, resting blood pressure).
- **Model Training**: Uses **SVM** with hyperparameter tuning and **KNN** with cross-validation for accuracy improvement.
- **Performance Metrics**: Evaluates the model using **accuracy, confusion matrix**, and **classification report**.

## Technologies Used

- **Python** 3.x
- **NumPy**, **Pandas** for data manipulation
- **Scikit-learn** for machine learning models and metrics
- **Matplotlib**, **Seaborn** for data visualization
- **Jupyter Notebook** for interactive development

## Project Structure

- `ai_app.ipynb`: Main Jupyter Notebook file containing all the code for data preprocessing, model training, and evaluation.
- `requirements.txt`: Lists the necessary libraries and dependencies.
- `README.md`: Project documentation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Heart-Disease-Prediction
   cd Heart-Disease-Prediction

2. Install dependencies:

pip install -r requirements.txt

3. Open the Jupyter Notebook and run the code:

jupyter notebook ai_app.ipynb


## Results

SVM Model:

Accuracy after hyperparameter tuning: ~99%

Classification Report and Confusion Matrix are provided for better evaluation.

KNN Model:

Accuracy after hyperparameter tuning: ~98%

Classification Report and Confusion Matrix are provided for performance analysis.

## Future Work

Real-time Prediction: Implement real-time prediction using live medical data.

Model Optimization: Further fine-tuning models with more data and advanced algorithms like Random Forest or XGBoost.

Web/Mobile Application: Develop a user-friendly application for medical practitioners to input data and get predictions.

## Authors

Muhammed Ahmed – MoAhmed229

Youssef Abdelazeem - Youssef-Abdelazeem
