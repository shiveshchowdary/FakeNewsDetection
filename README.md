# Fake News Detection Models

This repository contains the code and results of three different models (LSTM, CNN, and ANN) for the task of fake news detection. The models were trained and tested on the "Fake and Real News Dataset" available on Kaggle.

## Model Results

| Model | Training Loss | Training Accuracy | Validation Loss | Validation Accuracy |
|-------|---------------|-------------------|-----------------|---------------------|
| LSTM  | 0.1962        | 91.42%            | 0.2691          | 88.49%              |
| CNN   | 0.0110        | 99.75%            | 0.2706          | 95.77%              |
| ANN   | 0.0924        | 97.29%            | 0.0769          | 97.89%              |

## Test Results

Here are the test results for each model:

| Model | Test Loss | Test Accuracy |
|-------|-----------|--------------|
| LSTM  | 0.2691    | 88.49%       |
| CNN   | 0.2706    | 95.77%       |
| ANN   | 0.0900    | 96.88%       |

## Usage

You can use the provided code to load and test the models on your own data or make predictions on fake news detection. Each model has been saved and can be loaded for further analysis.

## Acknowledgments

The models were trained and tested using the "Fake and Real News Dataset" from Kaggle, which is credited to Clément Bisaillon. We acknowledge the dataset creators for providing this valuable resource.