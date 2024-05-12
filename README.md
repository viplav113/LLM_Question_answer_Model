# Question Answer LLM Model Prediction

## Overview
This project aims to develop a Language Model (LLM) capable of predicting top 3 answers for multiple-choice questions. The model is trained using a custom training file and evaluated using a testing file. Additionally, the project utilizes pre-trained LLM models and a Wikipedia parquets file for enhanced prediction accuracy.

## Introduction
In this project, we leverage Language Models (LMs) to predict the top 3 answers for multiple-choice questions. The approach involves training our own LLM model using a custom training file and combining it with pre-trained LLM models for improved performance. The testing phase utilizes the combined models along with a Wikipedia parquets file to predict answers for given questions.

## Files
- `training.py`: Python script for training the custom LLM model.
- `testing.py`: Python script for testing the combined LLM models and predicting answers.
- `README.md`: This file providing an overview of the project.

## Training
The `training.py` script is responsible for training our own LLM model. This model is trained using a custom training file containing relevant text data. The training process involves fine-tuning the model parameters to optimize performance for predicting answers to multiple-choice questions.

## Testing
The `testing.py` script combines the custom-trained LLM model with pre-trained LLM models. It utilizes a Wikipedia parquets file to enhance the prediction accuracy. The testing phase evaluates the combined models' performance by predicting the top 3 answers for given multiple-choice questions.

## Usage
To use this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the necessary dependencies.
3. Run `training.py` to train the custom LLM model.
4. Run `testing.py` to test the combined LLM models and predict answers.

## Dependencies
- Python 3.x
  


