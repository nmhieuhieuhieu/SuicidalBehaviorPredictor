# Suicide Prediction on Social Media

This repository contains a project aimed at predicting suicidal behavior on social media using machine learning and deep learning algorithms, including Logistic Regression (LR), Convolutional Neural Networks (CNN), and Long Short-Term Memory networks (LSTM).

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to develop models that can predict suicidal behavior based on social media posts. By analyzing the text data, the models can help identify users at risk and provide timely interventions.

## Features

- Data preprocessing and cleaning
- Feature extraction and selection
- Implementation of Logistic Regression, CNN, and LSTM models
- Evaluation and comparison of model performance

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/your-username/suicide-prediction.git
    cd suicide-prediction
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```sh
    python -m venv venv
    source venv/bin/activate # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Preprocess the data:
    ```sh
    python preprocess.py
    ```

2. Train the models:
    - Logistic Regression:
      ```sh
      python train_lr.py
      ```

    - Convolutional Neural Network (CNN):
      ```sh
      python train_cnn.py
      ```

    - Long Short-Term Memory network (LSTM):
      ```sh
      python train_lstm.py
      ```

3. Evaluate the models:
    ```sh
    python evaluate.py
    ```

## Models

- **Logistic Regression (LR)**: A simple yet effective machine learning algorithm for binary classification.
- **Convolutional Neural Network (CNN)**: A deep learning model that excels at capturing spatial hierarchies in data.
- **Long Short-Term Memory (LSTM)**: A type of recurrent neural network (RNN) well-suited for sequence prediction problems.

## Dataset

The dataset used in this project consists of social media posts labeled as either indicating suicidal behavior or not. Due to privacy and ethical considerations, the dataset is not included in this repository. Researchers should use publicly available datasets or seek appropriate permissions to use relevant data.

## Results

The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Detailed results and comparisons are provided in the `results` directory.

## Contributing

We welcome contributions to this project. Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeature`).
5. Create a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
