# Python Neural Network

> **Simple feed‑forward neural network implemented from scratch in Python.**

This repository contains a clean, minimal implementation of a feed‑forward neural network in pure Python—no deep learning libraries required. Ideal for learning and experimentation.

---

## 📘 What’s Inside

- 🧠 `firstnn.py`: A fully‑connected neural network with one hidden layer (ReLU activation), implemented from scratch.
- 📈 Training loop that manually performs forward pass, loss computation (MSE), backward propagation, and weight updates.
- 🎓 Educational, easy‑to‑follow code—perfect for understanding the core mechanics of neural networks.

---

## 🚀 Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/JustCh3cco-19/python-neural-network.git
    cd python-neural-network
    ```
2. Run the network:
    ```bash
    python3 firstnn.py
    ```
   This will train the neural network on a small dataset (e.g., XOR or regression toy data) and print learning progress.

---

## 🏗️ How It Works

- Implements a feed‑forward structure: input → hidden layer → output.
- Uses ReLU activation in the hidden layer and calculates Mean Squared Error (MSE) for loss.
- Applies backpropagation to compute gradients and updates weights via simple gradient descent.

---

## 🛠️ Why Use This?

- Educational tool: helps understand low‑level NN operations without relying on frameworks like PyTorch or TensorFlow.
- Lightweight and dependency‑free—pure Python only.
- Ideal starting point if you're learning how neural networks train internally.

---

## 📋 Requirements

- Python 3.x
- No external dependencies—everything is implemented manually!

---
