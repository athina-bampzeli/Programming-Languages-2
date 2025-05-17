# Programming-Languages-2
This repository contains the code used for my second assignment on the elective course Programming Languages.
a) The project involves the implementation of Linear Regression, Decision Tree Regressor, Random Forest Regressor and K-Nearest Regressor algorithms and the calculation of performance metrics MSE, R2, MAE and MAPE for evaluating the dataset "Bioconcentration Factor Dataset".
b) Three different neural network architectures were developed and trained on the previous dataset. The models were evaluated using metrics on both training and test sets and a detailed hyperparameter tuning process was carried out.
c) Dimensionality reduction was performed using PCA and t-SNE and KMeans clustering was also applied to the reduced data.
d) A Random Forest surrogate model was developed to approximate the relationship between input features and BCF. The surrogate was used to perform input optimization, aiming to minimize the predicted BCF.

## a) Neural Network Modeling (Question 2 - 40%)

Three different neural network architectures were developed and trained on the **"Bioconcentration Factor Dataset"**:

- **Model 1**: A simple MLP with one hidden layer (64 neurons, ReLU).
- **Model 2**: A deeper network with three hidden layers (128, 64, 32 neurons) and dropout regularization (rate = 0.3).
- **Model 3**: A smaller network with two hidden layers (32 and 16 neurons) using `tanh` activations.

All models were trained using the Adam optimizer with **MSE** as the loss function and **MAE** as an evaluation metric. Performance was measured on both training and test sets, and model tuning was conducted using grid search. Evaluation included **R² scores**, **loss curves**, and **MAE plots** to assess generalization, overfitting, and convergence.

---

## b) Dimensionality Reduction and Clustering (Question 3 - 40%)

Dimensional
