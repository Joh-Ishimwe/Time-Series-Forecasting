# Time-Series Forecasting: PM2.5 Prediction
Air pollution is a growing concern, particularly in rapidly developing urban areas. Among the various pollutants, PM2.5, a fine particulate matter, is one of the most harmful due to its ability to penetrate deep into the lungs and bloodstream.

In this project, I applied Long Short-Term Memory (LSTM) networks to forecast PM2.5 concentration levels using historical weather and air quality data provided in the Kaggle Beijing PM2.5 Forecasting Challenge.

## Dataset
The dataset includes timestamped records of:

1. PM2.5 concentration levels

2. Weather variables such as temperature, dew point, pressure, wind direction/speed, and cumulative hours of snow or rain

Available via:
Kaggle Competition Dataset

## Objective
The goal is to build a model that accurately predicts PM2.5 concentrations for future timestamps, using a time-series approach.

## Technologies Used
- Python 

- Pandas, NumPy (Data Processing)

- Matplotlib, Seaborn (Data Visualization)

- TensorFlow/Keras (Modeling with LSTM)

## Notebook Highlights
The notebook contains the full pipeline, including data cleaning, visualizations, model building, training, and evaluation.

## Key Steps in the Notebook
### 1. Exploratory Data Analysis
Initial inspection of the dataset, checking for missing values, patterns, and feature relevance.

### 2. Data Preprocessing

- Handling missing values

- Normalizing features

- Creating time sequences/sliding windows for LSTM input

### 3. Model Architecture
Designing an LSTM-based Recurrent Neural Network suitable for time-series forecasting.

### 4. Model Training
Training the model using historical data, tuning epochs and batch size for performance.

### 5. Model Evaluation
Assessing the model’s predictions using RMSE and comparing predicted vs actual PM2.5 values.

## Results
My model achieved a public score of 50091.8 RMSE on Kaggle. While this is a solid start, further improvements are planned through feature engineering, hyperparameter tuning, and model optimization.

Future Improvements
- Experimenting with additional features 

- Give the model enough time to learn deeper

- Trying other sequence models such as GRU or Transformer-based architectures

