# Emotion Classification using BiLSTM

This project aims to build an emotion classification model using a Bidirectional Long Short-Term Memory (BiLSTM) neural network. The model takes text input and predicts the emotion associated with the text.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Model Architecture](#model-architecture)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Evaluation Results](#evaluation-results)
- [Setup and Installation](#setup-and-installation)
- [Running the Project](#running-the-project)
- [Making Predictions](#making-predictions)

## Introduction

The goal of this project is to classify text into different emotions using a deep learning model. This project uses a BiLSTM model to achieve this.

## Methodology

1. **Data Preprocessing**: Tokenizing and padding the text data.
2. **Model Building**: Creating a BiLSTM model with specific layers and configurations.
3. **Training**: Compiling and training the model on the training data.
4. **Evaluation**: Evaluating the model on test and validation data.
5. **Prediction**: Making predictions on new text data.

## Model Architecture

- **Embedding Layer**: Converts input sequences into dense vectors.
- **Spatial Dropout Layer**: Applies dropout to the embedded input.
- **First BiLSTM Layer**: Captures temporal dependencies in both directions.
- **Second BiLSTM Layer**: Further captures temporal dependencies.
- **Dense Layer**: Applies a fully connected layer with ReLU activation.
- **Dropout Layer**: Applies dropout to prevent overfitting.
- **Output Layer**: Produces the final output with the appropriate activation function.

## Hyperparameter Tuning

- **Embedding Dimension**: 128
- **LSTM Units**: 128 and 64
- **Dropout Rate**: 0.3
- **Output Dimension**: 7
- **Output Activation**: Sigmoid

## Evaluation Results

The model's performance is evaluated on test and validation datasets.

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/bhuvi-ai/sentiment-analysis-model.git
   cd emotion-classification-bilstm
2. Extract the Data:

Ensure you have unrar installed. If not, install it using :
```bash
unrar x data.rar
```
3. Create a Virtual Environment:
   ```BASH
   python -m venv venv
   ```
4. Activate the Virtual Environment:
   ```bash
   .\venv\Scripts\activate
    ```
5. Install Dependencies:
   ```bash
   pip install -r requirements.txt
   ```
## Running the Project
1. Change Directory to the Project Folder:
   ```bash
   cd /path/to/project
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook main.ipynb
    ```
   
