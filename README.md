# 🔢 Handwritten Digit Classifier (MNIST)

## 👩‍💻 Author
**Varshini**

---

## 🎯 Objective

To build a **Neural Network model** that accurately classifies handwritten digits (0–9) using the **MNIST dataset**.

---

## 📚 Project Overview

This project implements a **multi-class classification model** using **TensorFlow/Keras** to recognize handwritten digits.

The MNIST dataset contains **70,000 grayscale images (28×28 pixels)** of digits from 0 to 9.

---

## ⚙️ Workflow

- 📥 Load MNIST dataset  
- 🧹 Normalize pixel values (0–1 range)  
- 🔢 Convert labels using one-hot encoding  
- 🧠 Build neural network model  
- ⚙️ Train model with validation split  
- 📊 Evaluate model performance  
- 🔍 Predict and visualize results  

---

## 🧠 Model Architecture

- Flatten layer (28×28 → 784)  
- Dense (128 neurons) → ReLU  
- Dense (64 neurons) → ReLU  
- Output layer (10 neurons) → Softmax  

👉 The model predicts probabilities for each digit class (0–9).

---

```## 🗂️ Project Structure
Handwritten_Digit_Classifier/
├── Handwritten_Digit_Classifier.ipynb # Main notebook
└── README.md # Documentation
```

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - TensorFlow / Keras  
  - NumPy  
  - Matplotlib  

---

## 📊 Results

---

## 🛠️ Tech Stack

- **Language:** Python  
- **Libraries:**  
  - TensorFlow / Keras  
  - NumPy  
  - Matplotlib  

---

## 📊 Results

- ✅ Test Accuracy: **~97.5%**  
- 📈 High accuracy achieved with a simple neural network  
- 🔍 Model correctly predicts handwritten digits with strong performance  

---

## 📈 Outputs

- Training & validation accuracy  
- Loss curves  
- Predictions on test images  
- Visualization of classified digits  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone https://github.com/bvsvarshini/Handwritten_Digit_Classifier.git
