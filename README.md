# Iris-Flower-Classification-with-PyTorch
# 🌸 Iris Flower Classification with PyTorch

This beginner-level machine learning project builds a simple **feedforward neural network from scratch using PyTorch** to classify iris flower species based on petal and sepal measurements.

---

## 🚀 Project Overview

- **Objective:** Classify iris flowers into 3 species — *Setosa, Versicolor, Virginica*
- **Model Type:** Neural Network (1 hidden layer)
- **Framework:** PyTorch (low-level API)
- **Dataset:** [Iris dataset](https://archive.ics.uci.edu/ml/datasets/iris) from scikit-learn

---

## 🧠 Learning Goals

- Understand the basics of neural networks (layers, activation, softmax)
- Learn how to build a training loop manually in PyTorch
- Practice preprocessing structured data for ML
- Evaluate model accuracy with class predictions

---

## 📁 Project Structure

├── iris_classification.ipynb # Google Colab notebook with code and outputs
├── README.md # Project documentation

---

## 📊 Dataset Description

The Iris dataset contains **150 records** with 4 input features:

- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

Target variable:  
- 0: Setosa  
- 1: Versicolor  
- 2: Virginica

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - `PyTorch` – Neural network implementation  
  - `scikit-learn` – Dataset loading, preprocessing  
  - `NumPy`, `Matplotlib`, `Seaborn` – Data manipulation and visualization  
  - `Google Colab` – Execution environment

---

## ✅ Key Steps

1. **Load & preprocess data**
   - Standardize inputs
   - One-hot encode targets
2. **Define the model**
   - `4 → 10 → 3` layer architecture with ReLU and softmax
3. **Train using custom loop**
   - CrossEntropyLoss + Adam optimizer
4. **Evaluate performance**
   - Accuracy on test set

---

## 📈 Results

- Achieved **~95% accuracy** on the test dataset.
- Demonstrated correct classification using manually built neural network layers and PyTorch training loop.

---

