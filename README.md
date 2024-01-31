# Energy Consumption Forecasting Model

## Project Overview

This project develops a machine learning model to forecast renewable and fossil fuel consumption for various countries based on GDP, population, and year data. The RandomForestRegressor algorithm 
is used to analyze historical energy consumption trends and make accurate predictions.

## User Guide
### Installation:
1.	Download and install Miniconda from the official website. Choose the installer appropriate for your operating system (Windows or MacOSX).
2.	Create a dedicated project folder on your local machine for the application files.
3.	Open a terminal window (or Command Prompt in Windows) and use the cd command to navigate to your project folder.
4.	Create a new Conda environment with the required libraries by running the following command: conda create --prefix ./env pandas numpy matplotlib scikit-learn ipywidgets jupyter
5.	Once the environment is created, activate it using: conda activate ./env (Replace ./env with the full path to your environment if you are not in the project directory.)
6.	Place the capstone-final.ipynb Jupyter Notebook file and the world-consumption.csv dataset into the project folder.
7.	Start Jupyter Notebook by executing: jupyter notebook\
### Using the Application:
1.	In the Jupyter Notebook dashboard that opens in your web browser, navigate to the capstone-final.ipynb file and open it.
2.	Run all the cells in the notebook to initialize the application by clicking on "Cell" > "Run All" in the Jupyter Notebook menu.
3.	Scroll to the bottom of the notebook to find the input widgets.
4.	Input the desired country name, year, population, and GDP values into the corresponding fields.
5.	Click the "Predict" button to generate renewable and fossil fuel consumption forecasts based on your inputs.
### Example Usage
For instance, to predict Brazil's renewable energy consumption in the year 2025, with a population of 215 million and a GDP of $2.965 trillion:
•	Enter "Brazil" in the 'Country' field of the dropdown menu.
•	Input "2025" in the 'Year' field.
•	Enter "215,000,000" for the population.
•	Type "2,965,000,000,000" for the GDP.
•	Click the "Predict" button.

## Features

- Historical data analysis from 1965 to 2022.
- Machine learning model with a user-friendly interactive interface for predictions.
- Detailed visualizations of data and predictions.

## Model Evaluation

The model's performance can be evaluated using the provided evaluation metrics in the notebook, including MAE, RMSLE, and R^2.
