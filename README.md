# IMDb Sentiment Analysis with XGBoost

## Overview
This repository contains the implementation of a sentiment analysis project focusing on classifying IMDb movie reviews as positive or negative using machine learning techniques. The project originally started as a course project for AIDI1002 Machine Learning Programming at Georgian College in 2023.

## Project Goals
- Implement and replicate existing methodology for IMDb sentiment analysis.
- Integrate XGBoost as an additional machine learning model to explore its impact on performance.
- Evaluate and compare the results with other models implemented in the project.

## Key Features
- Utilizes Python, Tensorflow, Keras, and Scikit-learn.
- Preprocesses data using lemmatization and vectorization techniques (binary, count, tfidf).
- Models include logistic regression, random forest, gradient boosting, MLP classifier, and now XGBoost.
- Three embedding methods: NNLM 50, NNLM 128, NNLM 128 with normalization, universal encoder, and Long Short Term Memory (LSTM).

## Dataset
The project uses a dataset of 50,000 IMDb movie reviews split evenly for training and testing. The data is labeled as positive or negative based on IMDb star ratings.

## Significant Contribution
The primary addition to the methodology is the implementation of XGBoost as an ensemble model to enhance classification accuracy.

## How to Run
There will be two jupyter notebooks one is for existing methodology reproducibility and second jupyter notebook is for our new implemented methodology to run both require train data and test data should be located in the same path as these notebooks folder and the data needed to be extracted from movie_data.tar.gz available in this repo. It has two txt files 1 full_train.txt and full_test.txt one is for training data and another is to evaluate the model.

## Results
The results of various models, including XGBoost, are discussed and compared in terms of accuracy and other relevant metrics in the jupyter notebooks itself.

## Future Work
Suggestions for potential improvements and variations are provided for future exploration.

## Contributors
- Vishal Patel
- Harshilkumar Patel
