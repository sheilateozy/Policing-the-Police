# Predicting police killings
## Using Logistic Regression, Random Forest, Neural Network

This is a 2020 passion project inspired by the year's focus on police accountability.
<li>Topic analysis on text using Latent Dirichlet Allocation.
<li>Data analysis across time, state lines, and racial groups.

# About
Since the death of George Floyd in 2020, protests against police violence have resurfaced across the world. Inspired by this phenomenon, this project analyses all police killings between 2015 - 2020 by merging data from three of the largest databases of police violence in America: Mapping Police Violence, The Washington Post, and Deadspin.

This project offers 2 insights:
<li>Data Analysis & Visualisation: Analysis on how police violence has evolved over time and across state lines, how race plays a role, and text mining on the circumstances in which this violence takes place.
<li>Machine learning: Build a model that predicts if an individual will be killed when they encounter the police.

# Project Methodology
<b>Data Analysis & Visualisation</b>
1. Does race affect police violence?
2. Rate of police violence per state
3. Why do states differ in police violence?
4. Topic analysis on descriptions of police violence deaths: Latent Dirichlet Allocation

<b>Machine Learning</b>
1. Impute missing data using KNN algorithm
2. Scale features
3. Handle class imbalance in target by oversampling minority class
4. Choose model performance metrics: F-Score
5. Train & tune model hyperparameters using Random Search
6. Feature importances
7. Future improvements
