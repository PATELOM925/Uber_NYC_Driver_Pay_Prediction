# Uber NYC Driver Pay Prediction

This repository contains the implementation of predicting Uber NYC driver pay using various machine learning and deep learning models: Artificial Neural Network (ANN), Random Forest, Long Short-Term Memory (LSTM), Bidirectional LSTM, and LSTM with Gated Recurrent Unit (GRU). The project utilizes the [Uber NYC for-hire vehicles trip data](https://www.kaggle.com/datasets/shuhengmo/uber-nyc-forhire-vehicles-trip-data-2021) dataset from Kaggle for training and evaluation.

## Introduction

Predicting Uber NYC driver pay is crucial for understanding earnings patterns and optimizing driver schedules. This project explores multiple machine learning models to predict pay based on various factors such as date, time, location, and other relevant features from the dataset.

## Models Implemented

- **Artificial Neural Network (ANN)**: A deep learning model suitable for learning complex patterns in data.
- **Random Forest**: A versatile ensemble learning method known for handling large datasets with high dimensionality.
- **Long Short-Term Memory (LSTM)**: A type of recurrent neural network (RNN) capable of learning long-term dependencies.
- **Bidirectional LSTM**: Enhances the standard LSTM by processing the input sequence in both forward and backward directions.
- **LSTM with Gated Recurrent Unit (GRU)**: Combines LSTM's capability of learning long-term dependencies with GRU's simpler gating mechanism.

## Dataset

The Uber NYC dataset from Kaggle includes information on Uber rides in New York City, comprising various features like date, time, location, fare details, and driver earnings. These attributes are used to train and evaluate the predictive models.
