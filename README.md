# NYC Taxi Tip Prediction

## Overview

This project demonstrates the application of machine learning techniques, specifically Decision Tree regression, to predict taxi tip amounts using a real-world dataset. The dataset contains information about taxi rides in New York City, including details like trip distance, fare amount, and the tip paid. The data was collected by technology providers authorized by the NYC Taxi and Limousine Commission (TLC) under the Taxicab & Livery Passenger Enhancement Programs (TPEP/LPEP).

In addition to using the popular Scikit-Learn library, this project also leverages the high-performance Snap Machine Learning (Snap ML) library from IBM. Snap ML provides optimized implementations of machine learning algorithms, capable of accelerating model training on both CPU and GPU.

## Objectives

The primary objectives of this project are:
1. **Data Preprocessing**: Perform basic data preprocessing steps using Scikit-Learn.
2. **Modeling**: Implement a regression model to predict the taxi tip amount using both Scikit-Learn and Snap ML Python APIs.
3. **Training**: Train a Decision Tree Regressor model with both Scikit-Learn and Snap ML.
4. **Inference & Evaluation**: Run predictions (inference) on the trained models and assess their performance.

## Dataset

The dataset used in this project includes various features such as:
- **Trip Distance**
- **Fare Amount**
- **Payment Type**
- **Tip Amount** (target variable)

The dataset is available publicly through the NYC Taxi and Limousine Commission (TLC).

## Libraries and Tools

This project makes use of the following libraries:
- **Scikit-Learn**: A widely-used library for machine learning in Python.
- **Snap ML**: IBM's high-performance machine learning library that provides optimized implementations of various algorithms, particularly beneficial for large datasets and environments requiring accelerated training.

## Installation

To run this project, you'll need Python installed on your machine, along with the required Python libraries. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt

