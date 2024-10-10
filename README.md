# Oil Temperature Prediction using ET Dataset

## Project Overview
This project develops a predictive model using Deep learning networks to forecast oil temperatures in power transformers. Utilizing time-series data from the Electricity Transformer Dataset (ETDataset), this model aims to enhance predictive maintenance strategies, thereby increasing operational efficiency and safety in power distribution networks.

## Background
Power transformers are vital components in electrical grids, where oil temperature is a key indicator of transformer health. Traditional maintenance schedules often fail to prevent failures, as they are not condition-based. This project leverages advanced machine learning techniques to transition from reactive to proactive maintenance practices.

## Features
- **Time Series Forecasting**: Utilizes GRU networks to handle sequences and capture both short-term and long-term dependencies in oil temperature data.
- **Data Analysis**: Involves comprehensive exploratory data analysis (EDA) and feature engineering to prepare the dataset for effective model training.
- **Predictive Accuracy**: Employs Root Mean Squared Error (RMSE) for model evaluation, ensuring high predictive accuracy.

## Installation
To set up this project, follow the steps below:

``` bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost keras tensorflow statsmodels
```

```bash
git clone https://github.com/pointarcher02/Deepcraft-AI-Engineer.git

jupyter Deepcraft_Assignment_AI_Engineer_Shashank_Asthana.ipynb
```

Open the Deepcraft_Assignment_AI_Engineer_Shashank_Asthana.ipynb notebook and run the cells sequentially to replicate the analysis.

## Results
The project evaluates each model's performance using the Root Mean Squared Error (RMSE) metric. GRU outperformed other models with the lowest RMSE, demonstrating its effectiveness in predicting stock prices with high accuracy.
