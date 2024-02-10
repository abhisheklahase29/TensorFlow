# Neural Network For Handwritten Digits Classification

This repository contains a Python script for implementing a neural network to classify handwritten digits using the MNIST dataset.

## Requirements
- Python (>= 3.6)
- TensorFlow (>= 2.0)
- NumPy
- Matplotlib
- Seaborn

## Installation
You can install the required packages using pip:

```bash
pip install tensorflow numpy matplotlib seaborn
```

## Usage
1. Clone this repository to your local machine:

```bash
git clone https://github.com/your-username/neural-network-handwritten-digits.git
```

2. Navigate to the project directory:

```bash
cd neural-network-handwritten-digits
```

3. Run the Python script:

```bash
python neural_network_handwritten_digits.py
```

## Description
The script `neural_network_handwritten_digits.py` implements a neural network using TensorFlow and Keras to classify handwritten digits from the MNIST dataset. The neural network architecture consists of a single hidden layer with 200 neurons and an output layer with 10 neurons. The script performs the following steps:

1. Load the MNIST dataset.
2. Preprocess the data by normalizing pixel values.
3. Train the neural network model using the training data.
4. Evaluate the model's performance on the test data.
5. Visualize sample predictions and the confusion matrix.

## Results
The trained neural network achieves an accuracy of approximately 97% on the test dataset. The confusion matrix provides insights into the model's performance across different classes of digits.


