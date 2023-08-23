# Deep Learning Regression for Car Sales Price Prediction

## * Overview
This repository contains the implementation of a Deep Learning Regression model using an Artificial Neural Network (ANN) for predicting car sales prices. The goal of this project is to develop a robust regression model that accurately predicts the prices of cars based on their features.
![dataset-cover](https://github.com/meyush0/Deep-Learning-Regression-for-Car-Sales-Price-Prediction/assets/112842527/c23adbdd-4298-467f-9e97-d37b71f78677)

## * Table of Contents
### 1. Introduction
### 2. Dataset
### 3. Project Structure
### 4. Installation
### 5. Usage
### 6. Model Architecture
### 7. Preprocessing
### 8. Training
### 9. Evaluation
### 10. Results
### 11.Future Improvements
### 12. Contributing
### 13. License

## *Introduction
In this project, we leverage the power of Deep Learning and Artificial Neural Networks to predict car sales prices. The model architecture includes 2 hidden layers along with dropout regularization to prevent overfitting. The data is preprocessed using scaling techniques to ensure optimal convergence during training.

## *Dataset
The dataset used for this project is sourced from (https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction). 

## *Installation
Clone this repository: git clone https://github.com/your-username/your-repo.git
Install the required dependencies: pip install -r requirements.txt

## *Usage
#### Navigate to the src directory: cd src
#### Open the Jupyter Notebook car_sales_prediction.ipynb
Run each cell to follow along with the implementation and analysis

## *Model Architecture
The Neural Network model architecture consists of the following layers:

### Input Layer

#### 1st Hidden Layer (Dense with ReLU activation)
  Dropout Layer (Regularization)

#### 2nd Hidden Layer (Dense with ReLU activation)
  Output Layer (Dense with Linear activation)

#### Preprocessing

Feature scaling: StandardScaler is applied to standardize the feature values.
Target variable scaling: The target variable is also scaled using StandardScaler.
Train-Test Split: The dataset is split into training and testing subsets.

#### Training

Loss function: Mean Squared Error (MSE)
Optimizer: Adam optimizer
Early Stopping: Monitors validation loss and stops training to prevent overfitting.

#### Evaluation
The model is evaluated on the testing dataset using various evaluation metrics, including Mean Absolute Error (MAE) and R-squared.

## Results
[Include any relevant graphs, charts, or tables showcasing the model's performance.]

Future Improvements
[List potential improvements or enhancements that can be made in the future.]
Contributing
Contributions are welcome! Feel free to open a pull request.

