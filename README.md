# 🧠 MNIST Digit Recognition using Neural Network

## 📌 Project Description
This project implements a **feedforward neural network** using TensorFlow to classify handwritten digits from the MNIST dataset.

The model is trained on 60,000 images and tested on 10,000 images of digits (0–9).

---

## ⚙️ Workflow

1. Load MNIST dataset using TensorFlow
2. Preprocess data (reshape + one-hot encoding)
3. Build a neural network using Keras (Sequential API)
4. Train the model using SGD optimizer
5. Evaluate performance on test data
6. Visualize accuracy and loss over epochs
7. Experiment with hyperparameters (layers, neurons, activation functions)

---

## 🧱 Model Architecture

- Input Layer: 784 neurons (28x28 flattened image)
- Hidden Layer 1: 256 neurons (ReLU activation)
- Hidden Layer 2: 256 neurons (ReLU activation)
- Output Layer: 10 neurons (Softmax activation)

---

## ⚙️ Hyperparameters Used

- Optimizer: SGD
- Learning Rate: 0.001
- Loss Function: Categorical Crossentropy
- Activation Function: ReLU (hidden layers)
- Epochs: 10
- Batch size: default (32)

---

## 📊 Results

- Training Accuracy: ~99%
- Validation Accuracy: ~95%

The model shows good performance with minor overfitting, improved using techniques like Dropout.

---

## 📈 Improvements Tested

- Increased number of layers → no major improvement
- Increased neurons (128 → 512) → slower training, small gains
- Changed activation to ReLU → improved performance
- Increased epochs → better accuracy but risk of overfitting
- Added Dropout → reduced overfitting and improved generalization

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirementSC.txt
