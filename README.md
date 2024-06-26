﻿# Traffic_Sign_Prediction

This project focuses on classifying traffic signs using a neural network. The dataset includes preprocessed traffic sign images, and the model is trained using TensorFlow and Keras.

## Project Structure

- `data_preprocessing.ipynb`: Jupyter notebook for data loading and preprocessing.
- `model_training.ipynb`: Jupyter notebook for model training and evaluation.
- `model_evaluation.ipynb`: Jupyter notebook for model evaluation and prediction.
- `model_weights_leaky_relu3.h5`: File containing the saved model weights.

## Dataset

The dataset used in this project is the Traffic Signs dataset, which is preprocessed and provided as pickled files and CSV files. The dataset includes training, testing, and validation sets.

- `data0.pickle`: Contains the preprocessed traffic sign images.
- `label_names.csv`: Contains the class labels and corresponding traffic sign names.

## Getting Started

### Prerequisites

Ensure you have the following packages installed:

- `numpy`
- `pandas`
- `matplotlib`
- `tensorflow`
- `scikit-learn`

You can install these packages using pip:

```sh
pip install numpy pandas matplotlib tensorflow scikit-learn

