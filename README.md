# Linear Regression Health Costs Calculator

A machine learning project that uses **linear regression** to predict healthcare expenses based on personal and health-related information.

This project was completed as part of the **freeCodeCamp Machine Learning with Python** curriculum.

## Project Overview

The model learns relationships between different personal attributes and healthcare costs. After training, it predicts the expected healthcare cost for new data.

## Technologies Used

- Python
- TensorFlow
- Keras
- Pandas
- NumPy
- Matplotlib

## Machine Learning Model

The project uses a **neural network with linear regression** to predict healthcare costs.

The model is trained using a healthcare cost dataset containing information such as:

- Age
- Sex
- BMI
- Number of children
- Smoking status
- Region
- Healthcare charges

Categorical data is converted into numerical values before training.

## Model Evaluation

The model is evaluated using **Mean Squared Error (MSE)** and **Mean Absolute Error (MAE)**.

The project successfully passed the **freeCodeCamp Health Costs Calculator** challenge.

## Project Structure

```text
health-costs-calculator/
├── health_costs_calculator.ipynb
├── requirements.txt
└── README.md
```

## How to Run

Clone the repository and install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook cells to train the model and predict healthcare costs.

## Result

The trained model successfully completed the freeCodeCamp **Linear Regression Health Costs Calculator** challenge.
