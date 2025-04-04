# Bank Customer Churn Prediction Using Artificial Neural Networks (ANN)

## Overview

This project focuses on predicting customer churn in a banking context using an Artificial Neural Network (ANN). The dataset contains detailed information about bank customers, and the goal is to identify which customers are likely to stop using the bank's services. 

The final model achieved an **accuracy score of 86.3%**, indicating strong predictive capability for structured tabular data.

---

## Features

- **Data Preprocessing:** Handled categorical variables using encoding and performed feature scaling.
- **Model Architecture:**
  - Built using Keras with TensorFlow backend.
  - Two hidden layers, each with **11 neurons**.
  - **Sigmoid** activation function used for both hidden and output layers.
  - **One output neuron** for binary classification (churn or not).
- **Training & Evaluation:** Model trained on processed features and evaluated on a hold-out test set for accuracy.

---

## Tech Stack

- **Programming Language:** Python
- **Development Environment:** Google Colab
- **Libraries and Frameworks:**
  - `NumPy` – numerical computations
  - `Pandas` – data handling and preprocessing
  - `Matplotlib` – basic visualisation
  - `Scikit-learn` – preprocessing and model evaluation tools
  - `TensorFlow` (Keras) – building and training the ANN model

---

## Future Improvements

To enhance the model’s performance and flexibility, the following steps could be considered:

- **Switching to ReLU Activation:**  
  Using the **ReLU** (Rectified Linear Unit) activation function in the hidden layers can help avoid vanishing gradients and speed up training — potentially improving overall accuracy and convergence.

- **Hyperparameter Tuning:**  
  Adjusting parameters like batch size, learning rate, and number of neurons to optimise the model's learning efficiency.

- **Class Imbalance Techniques:**  
  Introducing SMOTE or class weight adjustments to handle any imbalance in the churn vs. non-churn data.


---