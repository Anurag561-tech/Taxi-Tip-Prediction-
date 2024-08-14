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
   
scikit-learn
snapml
pandas
numpy



## Results

After training the Decision Tree Regressor models using both Scikit-Learn and Snap ML, the following key results were observed:

- **Model Performance**: The models were evaluated using the Mean Squared Error (MSE) metric. The Snap ML model demonstrated comparable accuracy to the Scikit-Learn model but was significantly faster in training, especially on larger datasets.

- **Inference Speed**: The Snap ML model also exhibited faster inference times, making it a more suitable choice for real-time or large-scale applications.

- **Visualizations**: Various plots, such as feature importance and model predictions vs. actual tips, were generated to better understand the model's behavior. These visualizations can be found in the `results/` directory, along with the evaluation metrics.

- **Comparison of Libraries**: The comparison between Scikit-Learn and Snap ML highlighted the performance benefits of using Snap ML for large datasets and high-performance computing environments.

These results provide valuable insights into the effectiveness and efficiency of different machine learning libraries in handling regression tasks like taxi tip prediction.

## Acknowledgments

We would like to express our gratitude to the following:

- **NYC Taxi and Limousine Commission (TLC)**: For providing the comprehensive dataset used in this project, which made it possible to explore and model real-world data.

- **IBM Snap ML Team**: For developing and providing access to the high-performance Snap ML library, which allowed us to experiment with accelerated machine learning techniques.

- **Scikit-Learn Community**: For maintaining and constantly improving one of the most popular machine learning libraries, which served as the foundation for this project's initial modeling efforts.

For more information about Snap ML, please visit the [official website](https://www.zurich.ibm.com/snapml/).

