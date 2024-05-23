# Last.fm Music Recommendation System

This project implements a music recommendation system using the Last.fm dataset. The system leverages collaborative filtering and matrix factorization techniques, specifically using Alternating Least Squares (ALS) with regularization, to provide personalized music recommendations to users. The model's performance is evaluated using cross-validation.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Results](#results)
- [Contributing](#contributing) 

## Introduction
This project aims to build a recommendation system for music based on user interactions with artists in the Last.fm dataset. By applying collaborative filtering and matrix factorization, the system can predict user preferences and suggest new artists.

## Dataset
The dataset used in this project is the Last.fm dataset, which includes user-artist interactions. You can download the dataset from [Grouplens](https://grouplens.org/datasets/hetrec-2011/).

### Files
- `user_artists.dat`: Contains user-artist interaction data.
- `artists.dat`: Contains artist information.

## Installation
To run this project, you need to have Python installed along with several libraries. You can install the required libraries using the following command:

```bash
pip install pandas numpy scipy scikit-learn implicit
```

## Model Training and Evalulation
The model is trained using the ALS algorithm with regularization to prevent overfitting. Cross-validation is used to evaluate the model's performance. The Mean Squared Error (MSE) metric is used to measure the accuracy of the predictions.

## Results

The model's performance is evaluated using 5-fold cross-validation. The average Mean Squared Error (MSE) across all folds is printed as the final result.

## Contributing

Contributions are welcome! If you have any suggestions or improvements, please open an issue or create a pull request.
