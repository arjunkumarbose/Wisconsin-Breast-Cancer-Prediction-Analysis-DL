# Wisconsin Breast Cancer (Diagnostic) Analysis | Deep Learning

This code utilizes deep learning models to classify breast cancer using the Wisconsin Breast Cancer dataset. Four different types of models are trained and evaluated: Feedforward Neural Network (FNN), Convolutional Neural Network (CNN), Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU).

## Overview

- Data preprocessing and standardization
- Training and evaluation based on the 80/20 ratio of four deep learning models
- Visualization of model performance (confusion matrices, ROC curves, precision-recall curves, and learning curves)
- Displaying results in a table

## Results

Below are the results for each model:

| Model                               | Test Loss | Test Accuracy | F1 Score | Recall | Precision |
|-------------------------------------|-----------|---------------|----------|--------|-----------|
| Feedforward Neural Network (FNN)    | 0.0940    | 0.9649        | 0.9718   | 0.9718 | 0.9718    |
| Convolutional Neural Network (CNN)  | 0.1104    | 0.9649        | 0.9722   | 0.9859 | 0.9589    |
| Long Short-Term Memory (LSTM)       | 0.1181    | 0.9474        | 0.9565   | 0.9296 | 0.9851    |
| Gated Recurrent Unit (GRU)          | 0.1571    | 0.9298        | 0.9444   | 0.9577 | 0.9315    |

## Reference

Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
