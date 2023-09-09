# Customer Churn Prediction using TensorFlow

![TensorFlow Logo](path_to_tensorflow_logo.png)  <!-- Add the path to TensorFlow's logo or any other logo you want to show -->

Predict and visualize customer churn using deep learning with TensorFlow, Keras, and other Python libraries.

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This repository provides an end-to-end solution to predict customer churn from data preprocessing to model evaluation using deep learning.

## Prerequisites
- Python 3.10
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- TensorFlow
- Keras

## Setup & Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/Soham-Chaudhuri/customer-churn-prediction-tf.git
    cd customer-churn-prediction-tf
    ```

2. Create a virtual environment and activate it:
    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. Install necessary packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Place your dataset `WA_Fn-UseC_-Telco-Customer-Churn.csv` in the project directory.
2. Run the prediction script:
    ```bash
    python churn_prediction_tf.py
    ```

## Results
Check the generated plots and model performance metrics in the output directories. The confusion matrix and classification reports offer insights into the model's performance.
