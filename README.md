# Vehicle classifying

A Python project for **vehicle classification** using the vehicle dataset from OPENML. This project demonstrates data preprocessing, preparing and training the model under classic learning. It trains two models/methods including Polynomial Regression for Classification and Multinomial Logistic Regression.

---

## Features

- Classify vehicle (bus, opel, saab, van) from OPENML vehicle dataset (846 samples, 18 features)
- Easy-to-follow data preprocessing pipeline
- Training the model using classical matrix and gradient descent learning

---

## Data Pipeline

The project follows these main steps:

1. **Load & Preprocess Data**

- Load the OPENML dataset
- Perform one-hot encoding for the data
- Feature selection through Pearson Correlation to reduce high relation feature(less bias)

2. **Train Model**

- Method: Polynomial Regression for Classification and Multinomial Logistic Regression
- Add appropriate layers and activation functions

3. **Choose best learning rate and conclusion**

- Choose the best model with different learning rate for Multinomial Logistic Regression.
- Graph the result to understand the effect of standardization.

---

## Requirements

- Python
- Pandas
- NumPy
- Matplotlib (optional, for visualization)
- Scikit learn
- Other python package(in requirement.txt)
- OPENML dataset (Take from fetch_openml of scikit learn)

Install dependencies using:

```bash
python -m venv venv
pip install requirement.txt
```

And run the notebook locally to understand more

---

## Info

This project is done under EE2213 Introduction to AI of National University of Singapore in AY25/26 S1.
