# ✍️ Handwritten Digit Classification using CNN & RNN

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Deep Learning](https://img.shields.io/badge/DeepLearning-CNN%20%7C%20RNN-green)
![Dataset](https://img.shields.io/badge/Dataset-MNIST-orange)

---

## 📌 Project Description
This project implements a deep learning-based solution for recognizing handwritten digits (0–9) using two different approaches: **Convolutional Neural Networks (CNN)** and **Recurrent Neural Networks (RNN)**.

The main objective is to understand how different neural network architectures perform on image classification tasks. CNN is used to capture spatial features, while RNN processes the image as a sequence to explore an alternative approach.

The project covers the complete pipeline including data preprocessing, model building, training, and evaluation. A comparison between CNN and RNN is also performed to analyze performance differences.

**Key highlights:**
- Built CNN and RNN models from scratch  
- Used MNIST dataset for training and testing  
- Achieved high accuracy with CNN (~98–99%)  
- Compared sequential vs spatial learning approaches  

---

## 📌 Project Overview
This project focuses on **classifying handwritten digits (0–9)** using deep learning models.

Dataset details:
- 60,000 training images  
- 10,000 testing images  
- Image size: **28×28 grayscale**

---

## 🧠 Model Architectures

### 🔹 CNN Architecture
![CNN Architecture](https://github.com/Ishu335/Handwritten-Digit-Classification-using-CNN-RNN/blob/5f27a9ddf7a6fa67d325ff65505f78b2f1b82344/img/cnn_architecture.gif)

**Components:**
- Convolution layers  
- ReLU activation  
- Max pooling  
- Fully connected layers  
- Softmax output  

---

### 🔹 RNN Architecture
![RNN Architecture](https://github.com/Ishu335/Handwritten-Digit-Classification-using-CNN-RNN/blob/5f27a9ddf7a6fa67d325ff65505f78b2f1b82344/img/rnn_architecture_anim.gif)

**Components:**
- Sequential input (row-wise image)  
- Hidden state learning  
- Dense output layer  

---

## ⚙️ Technologies Used
- Python  
- PyTorch / TensorFlow  
- NumPy  
- Matplotlib  

---

## 📊 Workflow
1. Load MNIST dataset  
2. Preprocess data  
3. Build CNN & RNN models  
4. Train models  
5. Evaluate performance  
6. Compare results  

---

## 📈 Results

| Model | Accuracy |
|------|--------|
| CNN  | ~98–99% |
| RNN  | ~90–92% |

CNN outperforms RNN due to better spatial feature extraction.

---
## 📌 Applications
- Handwritten digit recognition
- OCR systems
- Bank cheque processing
- Postal code detection

## 💡 Key Learnings
- CNN vs RNN comparison
- Image vs sequential data handling
- Model optimization techniques
- End-to-end deep learning workflow
