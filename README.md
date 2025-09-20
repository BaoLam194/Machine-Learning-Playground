# Number classifying

A Python project for **handwritten digit classification** using the **MNIST dataset** and **TensorFlow**. This project demonstrates building, training, and saving neural network models for image classification tasks. It supports various model architectures, including **DNNs** (Dense Neural Networks) and **CNNs** (Convolutional Neural Networks).

---

## Features

- Classify handwritten digits (0-9) from MNIST dataset (~70,000 images)
- Flexible model architectures: DNN or CNN
- Easy-to-follow data preprocessing pipeline
- Model training with configurable optimizer and loss function
- Save trained models for future use

---

## Data Pipeline

The project follows these main steps:

1. **Load & Preprocess Data**

  - Load the MNIST dataset
  - Preprocess data to fit model requirements

2. **Build Model**

  - Choose model type (DNN or CNN)
  - Add appropriate layers and activation functions

3. **Compile Model**

  - Specify optimizer (e.g., Adam, SGD)
  - Choose loss function (e.g., categorical crossentropy)
  - Set evaluation metrics (e.g., accuracy)

4. **Train Model**

  - Fit the model on training data
  - Validate on test or validation set

5. **Save & Load Model**
  - Save trained models to disk
  - Load saved models for inference without retraining

---

## Requirements

- Python
- TensorFlow
- NumPy
- Matplotlib (optional, for visualization)
- Other python package(in requirement.txt)

Install dependencies using:

```bash
python -m venv venv
pip install requirement.txt
```
