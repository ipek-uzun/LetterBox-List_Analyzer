
# Letterboxd List Analyzer and Movie Preferences Prediction 

## Overview

This project aims to predict movie preferences using machine learning techniques. The dataset includes information about various movies, such as ratings, genres, and runtime. The goal is to build models that can predict whether a user will like or dislike a movie based on specific features.

## Data Extraction

The dataset was collected from Letterboxd using web scraping techniques. The collected data includes information such as film title, release year, director, genres, owner rating, average rating, runtime, countries, original language, spoken languages, watches, list appearances, likes, cast, studios, and Letterboxd URL.

## Exploratory Data Analysis (EDA)

The EDA process involved cleaning and preprocessing the data, exploring temporal trends in ratings, analyzing genre distributions, examining the relationship between owner and average ratings, and investigating film runtimes. Visualizations, such as histograms, scatter plots, and bar charts, were utilized to gain insights into the dataset.

## Hypothesis Testing

Hypothesis testing was conducted to determine whether there is a preference for watching popular films. The null hypothesis suggested no preference, while the alternative hypothesis proposed a tendency to watch more popular films. Statistical tests were performed, and the results were interpreted.

## Machine Learning

Machine learning models, including Random Forest and Decision Tree classifiers, were trained to predict movie preferences. Hyperparameter tuning was performed, and the models were evaluated on a test set. The trained models were then used to predict preferences for a separate dataset of top 500 films.

## Results

The accuracy of the Decision Tree model on the test set was found to be 73.91%. The results were interpreted, and a confusion matrix was visualized to provide a comprehensive understanding of the model's performance.

## Repository Structure

- `data/`: Contains the dataset used in the project.
- `notebooks/`: Jupyter notebooks for data exploration, machine learning, and hypothesis testing.
- `images/`: Images and visualizations generated during the analysis.
- `README.md`: This file, providing an overview of the project.

## Requirements

- Python 3.x
- Jupyter Notebooks
- Required Python packages (specified in `requirements.txt`)

