# Deep Learning Breast Cancer Detection

This project utilizes deep learning models to classify breast cancer using the Wisconsin Breast Cancer dataset. Four different types of models are trained and evaluated: Feedforward Neural Network, Convolutional Neural Network, Long Short-Term Memory (LSTM), and Gated Recurrent Unit (GRU).

## Project Overview

In this project, we perform the following tasks:

- Data preprocessing and standardization
- Training and evaluation of four deep learning models
- Visualization of model performance (confusion matrices, ROC curves, precision-recall curves, and learning curves)
- Displaying results in a table

## Usage

Follow these steps to run the project:

1. Clone the repository to your local machine.
2. Install the necessary Python libraries using pip:

```bash
pip install numpy pandas scikit-learn tensorflow matplotlib seaborn
```

3. Run the Python script to train and evaluate the models:

```bash
python breast_cancer_deep_learning.py
```

## Results

Below are the results for each model:

| Model                          | Test Loss | Test Accuracy | F1 Score | Recall | Precision |
|--------------------------------|-----------|---------------|----------|--------|-----------|
| Feedforward Neural Network     | 0.0723    | 0.9649        | 0.9723   | 0.9630 | 0.9818    |
| Convolutional Neural Network   | 0.0587    | 0.9781        | 0.9828   | 0.9747 | 0.9911    |
| Long Short-Term Memory (LSTM)  | 0.0696    | 0.9670        | 0.9739   | 0.9648 | 0.9831    |
| Gated Recurrent Unit (GRU)     | 0.0652    | 0.9725        | 0.9787   | 0.9699 | 0.9879    |

## Visualizations

Visualizations of model performance are available in the project folder:

- Confusion matrices
- ROC curves
- Precision-recall curves
- Learning curves

## Reference

Wolberg,William, Mangasarian,Olvi, Street,Nick, and Street,W.. (1995). Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. https://doi.org/10.24432/C5DW2B.
