# Sparkify - User Churn Prediction

## Table of contents

- [Installation](#installation)
- [Project motivation](#project-motivation)
- [File descriptions](#file-descriptions)
- [Analysis](#analysis)
- [Results](#results)
- [Creator](#creator)
- [Thanks](#thanks)


## Installation
- Python 3 required.
- Spark
- Pyspark
- Pandas
- Matplotlib
- Jupyter Notebook


## Project motivation

This project is the capstone project for Udacity's Data Science Nanodegree. I wanted to complete this project to gain experience with 
Spark, which is one of the main big data frameworks utilized by companies today.

## File descriptions

- mini_sparkify_event_data.json -> Data on Sparkify, a fake music service, outlining user behavior on that platform.
- Sparkify.ipynb -> Jupyter Notebook with code used to analyze the dataset

## Analysis

This analysis is centered on determining the best ML model to predict user churn (i.e. users who cancelled their paid or free subscription).
Additionally, understanding the best predictors for user churn, will also be explored.

## Results

After creating models using both DecisionTree and GBT Classifiers, based on F1 score, I went with using the DecisionTree Classifier, 
given the F1 score was 1. This as abnormally high, mainly due to the small sample of users provided in the data.

The best predictor of user churn was the number of time the user did a Thumbs down to the song being played. This makes sense given the 
users who didn't like the recommendations provided to them by Sparkify, would lead them to ponder the benefit of subscribing,using a music
service that is not giving them the songs they want.

## Creator

**Matt Middleberg**


## Thank YOU

<a href="https://eu.udacity.com/">
  <img src="https://eu.udacity.com/assets/iridium/images/core/header/udacity-wordmark.svg" alt="Udacity Logo" width="490" height="106">
</a>
