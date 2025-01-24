# **Character Classification using CNN (PyTorch)**

## **Overview**
This project involves building and training a convolutional neural network (CNN) using PyTorch to classify 36 characters (digits 0-9 and uppercase letters A-Z). The dataset is provided in the `CNN_dataset` folder, and the model is trained to achieve high classification accuracy.

---


### ** 1: Standard Classification Model **
- Implement a PyTorch-based CNN model to classify 36 characters.
- Use convolutional and fully connected layers for feature extraction and classification.
- Train and validate the model using the provided dataset.
- Evaluate performance and save trained models after each epoch.

### ** 2: Lightweight Model **
- Redesign the CNN architecture to have fewer than 1 million trainable parameters.
- Maintain classification accuracy while reducing model complexity.
- Train and validate the optimized model and compare it with Task 1.

---

## **Dataset**
The dataset consists of grayscale images resized to **28x28 pixels**. It is structured into:
- **`train/`** - Training images  
- **`val/`** - Validation images  

---

## **Model Architecture**

### **Standard Model**
- Two convolutional layers with ReLU activation and max pooling.
- Two fully connected layers for classification.
- Softmax output layer with 36 classes.

### **Lightweight Model**
- Reduced number of filters in convolutional layers.
- Fewer neurons in fully connected layers.
- Optimized for efficiency while maintaining accuracy.
