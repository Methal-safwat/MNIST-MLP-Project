# Handwritten Digit Recognition using MLP

## 📌 Project Overview
This project implements a Multilayer Perceptron (MLP) neural network to classify handwritten digits using the MNIST dataset.  
Two experiments were conducted using different optimizers (Adam and SGD) to compare performance.

---

## 📊 Dataset
MNIST Handwritten Digit Dataset  
- 60,000 training images  
- 10,000 testing images  
- Image size: 28x28 grayscale

---

## 🧠 Model Architecture
- Input layer (28x28 flattened)
- Dense layer (128 neurons, ReLU)
- Dense layer (64 neurons, ReLU)
- Dropout (0.3)
- Output layer (10 classes, Softmax)

---

## ⚙️ Training Details
- Epochs: 7
- Batch size: 32
- Loss function: Categorical Crossentropy
- Optimizers:
  - Adam
  - SGD
- Validation split: 20%

---

## 🔬 Experiments

### Adam Optimizer
- Faster convergence  
- Higher accuracy  
- Lower loss  

### SGD Optimizer
- Slower convergence  
- Slightly lower accuracy  
- Stable performance  

---

## 📈 Results

| Model | Optimizer | Accuracy | Loss |
|------|----------|----------|------|
| Model 1 | Adam | 97.5% | 0.092 |
| Model 2 | SGD | 97.0% | 0.099 |

---

## 📉 Conclusion
Adam optimizer performed better than SGD in terms of accuracy and convergence speed.  
However, both models achieved good performance on the MNIST dataset.

---

## 🚀 How to Run
1. Open Google Colab  
2. Upload notebook  
3. Run all cells  
4. View results

---

## 👩‍💻 Author
Neural Networks Course Project