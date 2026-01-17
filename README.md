# Mental-health-and-screen-use
Analysis of how screen usage affects stress and happiness levels. Performed in RStudio. Dataset from kaggle: https://www.kaggle.com/code/ahmadindragiri/mental-health-and-social-media-balance/input

This repository contains an R script that explores the relationship between daily screen time and key mental health indicators, using the Mental Health and Social Media Balance dataset.

# This script performs the following:

- Loads the dataset from a CSV file
- Calculates overall averages for:
Daily screen time (hours/day)
Stress level
Sleep quality
- Groups individuals into predefined screen time bands
- Computes average happiness levels within each screen time band
- Produces visualisations to examine relationships between variables
- Fits the linear regression model (note: First, I wrote a script where I simply used abline to add linear trend line to scatter plots in script named: Mental health and screen time.R, however I wanted to improve my work so I fitted the linear regression model in the improved script named: analysis-with-regression.R)

# Visualisations created

- Bar chart showing average happiness level by screen time band
  <img width="862" height="512" alt="Avg Happiness Level by Screen Time Band" src="https://github.com/user-attachments/assets/ba941531-f508-4e81-b444-022cae635812" />

- Scatter plot with trendline: stress level vs daily screen time
  <img width="862" height="512" alt="Stress Level vs Screen Time" src="https://github.com/user-attachments/assets/d7a533b3-ee24-430e-81a1-28bdaf3d8c3b" />

- Scatter plot with trendline: happiness level vs daily screen time
  <img width="862" height="512" alt="Happiness Level vs Screen Time" src="https://github.com/user-attachments/assets/034a2979-8ced-4fe8-8503-6a39a9e78ed9" />

## Fitting the linear regression model (stress level vs screen time)
<img width="580" height="330" alt="image" src="https://github.com/user-attachments/assets/0d25047f-d2c5-4924-bbc1-abc96bc9c2ed" />

## Fitting the linear regression model (happiness level vs screen time)
<img width="583" height="325" alt="image" src="https://github.com/user-attachments/assets/1cf38fe1-2d6f-4e49-9dc9-99e31e7d71dc" />

# Tools and methods

Written in base R (no additional packages required)
Uses standard statistical summaries and linear regression trendlines

## Dataset

The script expects the dataset file:

Mental_Health_and_Social_Media_Balance_Dataset.csv to be available locally. This dataset can be downloaded from Kaggle: https://www.kaggle.com/datasets/prince7489/mental-health-and-social-media-balance-dataset and file path will need updating in R studio.

## Purpose

This project was created for educational and analytical purposes only, demonstrating basic data processing, grouping, and visualisation techniques in R when analysing mental health and behavioural data.
