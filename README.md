# Student Performance Prediction using Neural Networks

## Overview
Built a Backpropagation Neural Network to predict student pass/fail outcomes using the UCI Student Performance dataset.

---

## Dataset
- 395 records
- 33 features
- Binary Target: Pass / Fail

---

## Preprocessing

- One-hot encoding of categorical features
- StandardScaler normalization
- Train-test split (70-30)

---

## Neural Network Architecture

- Input Layer
- 2 Hidden Layers (ReLU)
- Output Layer (Sigmoid)
- Optimizer: Adam
- Loss: Binary Cross-Entropy

---

## Results

- Test Accuracy: 89%
- Evaluated using confusion matrix and classification report.

---

## Key Learnings

- Importance of feature scaling
- Overfitting control in neural networks
- Model evaluation beyond accuracy
