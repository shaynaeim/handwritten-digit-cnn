# 🧠 Convolutional Neural Network for Handwritten Digit Recognition

This project implements a **Convolutional Neural Network (CNN)** from scratch to classify handwritten digits from the **MNIST dataset**.  
It’s designed as a **code-along tutorial** to help understand the core concepts of building, training, and evaluating CNNs using **PyTorch**.

---

## 📘 Project Overview

The MNIST dataset contains **70,000 grayscale images** of handwritten digits (0–9).  
This project demonstrates how to:
- Build a CNN architecture from scratch with PyTorch  
- Train the model using gradient descent and backpropagation  
- Evaluate its accuracy and visualize predictions
- 
---

## 🧩 Technologies Used

- **Python 3.10+**  
- **PyTorch**  
- **torchvision**  
- **NumPy**  
- **Matplotlib**  
- **Jupyter Notebook**

---

## 🚀 Project Workflow

1. **Data Loading & Preprocessing**  
   - Load the MNIST dataset using `torchvision.datasets`.  
   - Normalize image pixel values to improve model convergence.

2. **Model Architecture**  
   - Create a CNN using `torch.nn` modules.  
   - Include convolutional, pooling, and fully connected layers.

3. **Model Training**  
   - Define loss function (`CrossEntropyLoss`) and optimizer (`Adam`).  
   - Train the network for several epochs and track training/validation loss.

4. **Evaluation & Visualization**  
   - Test model accuracy on unseen data.  
   - Visualize predictions and feature maps.

---

