# Bree Take Home Assignment

This project involves predicting the balance in a customer's account after a loan repayment for a cash-advance startup.

## Project Structure

- `data_exploration.ipynb`: contains the initial data exploration and analysis.
- `feature_engineering_non_sequential.ipynb`: focuses on feature engineering for non-sequential data.
- `feature_engineering_sequential.ipynb`: focuses on feature engineering for sequential data.
- `modelling_non_sequential.ipynb`: contains the modeling process for non-sequential data.
- `modelling_sequential.ipynb`: contains the modeling process for sequential data.

## Setup

1. Clone the repository.
2. Create a virtual environment and activate it:
   ```sh
   python -m venv env
   source env/bin/activate  # On Windows use `env\Scripts\activate`
   ```
3. Install the required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Start Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Open the desired notebook and run the cells.

## Notebooks Overview

### Data Exploration

- [data_exploration.ipynb]: This notebook provides an overview of the dataset, including summary statistics and visualizations.

### Feature Engineering

- [feature_engineering_non_sequential.ipynb]: This notebook includes functions to engineer features for non-sequential data, such as filtering transactions by date and calculating initial balances.
- [feature_engineering_sequential.ipynb]: This notebook includes functions to engineer features for sequential data.

### Modeling

- [modelling_non_sequential.ipynb]: This notebook contains the process of building and evaluating models for non-sequential data. Models: XGBoost (with PCA), Feed Forward Neural Network
- [modelling_sequential.ipynb]: This notebook contains the process of building and evaluating models for sequential data. Models: LSTM
