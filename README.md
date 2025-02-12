# 🔍 Fingerprint Identity Detection Using Neural Networks  

## 📌 Overview  
This project implements a **fingerprint identity detection system** using deep learning techniques. The system classifies fingerprint images to identify **individuals (600 subject IDs)** and predict the **finger number (10 types, e.g., left index, right middle finger, etc.)**. Using **Convolutional Neural Networks (CNNs)**, the model achieves **high accuracy** in biometric authentication.  

## 🎯 Objectives  
- Identify individuals based on fingerprint images (**600 subject IDs**).  
- Predict the **finger number** associated with the fingerprint (**10 types**).  
- Utilize **deep learning (CNNs)** for fingerprint classification.  

## 📊 Dataset  
- **Source**: Labeled fingerprint dataset with subject IDs and finger numbers.  
- **Image Size**: 96x96 pixels (normalized between 0 and 1).  

## 🔬 Feature Extraction & Model Architecture  
The project uses **Convolutional Neural Networks (CNNs)** for feature extraction and classification:  

✅ **Model 0 (Subject ID Prediction)** – Classifies fingerprint images into **600 subject IDs**.  
✅ **Model 1 (Finger Number Prediction)** – Classifies fingerprint images into **10 finger types**.  
✅ **Conv2D Layers** – Extracts spatial fingerprint patterns.  
✅ **MaxPooling Layers** – Reduces dimensionality while preserving essential features.  
✅ **Dense Layers** – Fully connected layers for final classification.  
✅ **L2 Regularization & Dropout** – Prevents overfitting.  
✅ **Activation Functions** – **ReLU** (hidden layers) & **Softmax** (output classification).  
✅ **Optimizer** – **Adam**, with Cross-Entropy loss for training.  

## 🏗️ Methodology  
1️⃣ **Image Preprocessing** – Normalization & resizing of fingerprint images.  
2️⃣ **Feature Extraction** – CNN-based deep feature learning.  
3️⃣ **Classification Approaches**:  
   - **Model 0**: Identifies **subject ID (600 classes)**.  
   - **Model 1**: Predicts **finger number (10 classes)**.

## 📏 Evaluation Metrics  
📌 **Accuracy** – Overall correctness of the model.  
📌 **Confusion Matrix** – Visual representation of classification performance.  
