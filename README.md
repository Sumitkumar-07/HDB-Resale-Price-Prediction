# HDB-Resale-Price-Prediction

## Overview

This project is a prediction tool for forecasting Singapore's HDB resale prices. It is built using Streamlit and employs classic regression techniques such as linear regression, tree-based regression, support vector regression, and artificial neural networks. The models are trained on historical prices from 2017 to 2022, retrieved from [Data.gov.sg](https://data.gov.sg/dataset/resale-flat-prices "Historical Resale Flat Prices").

## Features

- **Data Preprocessing:** The dataset is preprocessed to handle missing values and irrelevant columns. Features are also scaled for better model performance.

- **Randomized Input:** Users can randomize input parameters such as month, town, flat type, storey range, flat model, floor area, and lease commencement date for HDB resale price prediction.

- **Model Selection:** Users can choose from various regression models, including linear regression, ridge regression, lasso regression, decision tree regression, XGBoost, support vector regression, and artificial neural networks.

- **Model Pipeline:** The application uses a model pipeline with preprocessing steps such as imputation, scaling, and one-hot encoding.

- **Real-time Prediction:** Users can get real-time predictions based on their input parameters.

- **Dashboard:** The Streamlit dashboard provides an intuitive interface for users to interact with the prediction tool.

## Setup
1. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Run the Streamlit app:

    ```bash
    streamlit run streamlit_app.py
    ```

## Usage

1. Access the Streamlit app at [http://localhost:8501](http://localhost:8501) in your web browser.

2. Use the sidebar to choose the scaling method, select a regression model, and input HDB parameters.

3. Click the "Randomize!" button for a random set of parameters.

4. View predictions and previous results in real-time.

## Dependencies

- Python 3.8+
- Streamlit
- Scikit-learn
- XGBoost
- TensorFlow (for artificial neural network model)
- Other dependencies specified in `requirements.txt`


## Acknowledgments

- Data source: [Data.gov.sg](https://data.gov.sg/dataset/resale-flat-prices "Historical Resale Flat Prices")

