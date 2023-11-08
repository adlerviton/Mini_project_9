# Mini project 9: Cloud Hosted Notebook Data Manipulation (Google Colab)

## Link to Cloud Notebook:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/adlerviton/Mini_project_9/blob/main/Main.ipynb)

## Data Manipulation Performed:
#### Read and Clean Data
- Read CSV dataset of S&P 500 historical
- Clean datetime data, create some new columns: Change over the day, Was this change positive?, and Magnitude of Change
- Add columns for data from the day before
#### EDA
- Look at Open prices time series from 2020
- Look at correlation between volume and change for each day
#### Modeling
- Try model from all data and all lag columns
- Try model trained on just 2009-2019 years, test on 2020
- Try logistic increase prediction model trained on just 2009-2019 years, test on 2020 (all ones for some reason)
- Try modeling change magnitude from last 10 years, use first model's prediction for sign to scale either negative or positive
