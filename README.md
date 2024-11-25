# Customer Churn Prediction

This project implements a **Customer Churn Prediction** model using machine learning techniques. The model predicts whether a customer will churn (exit) based on features like credit score, age, balance, and other personal information from the provided dataset.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Model Details](#model-details)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project uses the `Churn_Modelling.csv` dataset to build a machine learning model that predicts customer churn (exit status). The model follows these steps:
- Data preprocessing, including encoding categorical variables.
- Feature scaling using `StandardScaler`.
- Building and training a deep neural network using `Keras` with `TensorFlow`.

## Dataset
The dataset used for training the model is `Churn_Modelling.csv`. It contains the following columns:
- `CreditScore`: Credit score of the customer.
- `Geography`: The customer's country (France, Germany, Spain).
- `Gender`: The gender of the customer.
- `Age`: Age of the customer.
- `Tenure`: Number of years the customer has been with the company.
- `Balance`: The balance of the customer's account.
- `NumOfProducts`: Number of products the customer is subscribed to.
- `HasCrCard`: Whether the customer has a credit card (1 for yes, 0 for no).
- `IsActiveMember`: Whether the customer is an active member (1 for yes, 0 for no).
- `EstimatedSalary`: The estimated salary of the customer.
- `Exited`: Target variable (1 if the customer exited, 0 if not).

## Technologies Used
- **Python**
- **Pandas** for data manipulation
- **Matplotlib** for data visualization
- **TensorFlow** and **Keras** for building and training the neural network
- **Scikit-learn** for machine learning utilities like splitting data and evaluating the model
- **Jupyter Notebook** (if you're running the code interactively)

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/utsab345/Customer-Churn-Prediction.git
