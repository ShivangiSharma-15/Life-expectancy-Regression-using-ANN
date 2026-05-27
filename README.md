Life Expectancy Prediction using ANN

This project predicts the life expectancy of a country using an Artificial Neural Network (ANN) model based on healthcare, economic, and social indicators.

## Project Overview
Life expectancy is influenced by multiple factors such as healthcare quality, GDP, alcohol consumption, immunization rates, and schooling.  
The goal of this project is to build a deep learning regression model that can accurately predict life expectancy values.

## Technologies Used
- Python
- TensorFlow / Keras
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Dataset
Dataset contains features like:

- Country
- GDP
- Schooling
- Adult Mortality
- Alcohol Consumption
- BMI
- Immunization Rates
- Income Composition of Resources

Target Variable:
- Life Expectancy

## Data Preprocessing
- Missing value handling
- Label encoding
- Feature scaling using StandardScaler
- Train-test split

## ANN Model Architecture

Input Layer  
↓  
Dense Layer (128 neurons, ReLU)  
↓  
Dense Layer (64 neurons, ReLU)  
↓  
Dense Layer (32 neurons, ReLU)  
↓  
Output Layer (1 neuron)

## Model Performance

- Loss Function: Mean Squared Error (MSE)
- Optimizer: Adam
- Evaluation Metrics:
  - MAE
  - RMSE
  - R² Score

## Features

EDA< Data Visualization, Data Cleaning, Feature Scaling, 
- Predict life expectancy using custom inputs
- Deep learning regression model


## How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/life-expectancy-prediction-ann.git
