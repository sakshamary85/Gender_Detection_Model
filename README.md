# 🧠 Gender Detection Using Deep Learning & OpenCV

## 📌 Project Overview

This project showcases a deep learning-based gender classification system using Convolutional Neural Networks (CNNs) trained on facial images. The system is capable of real-time gender prediction via webcam using a simple desktop GUI built with **Tkinter**. It is ideal for applications like surveillance systems, demographic studies, and healthcare automation.

**Technologies Used**:
- 🐍 Python  
- 📸 OpenCV  
- 🧠 TensorFlow / Keras  
- 🪟 Tkinter (for GUI)

---

## 🎯 Key Features

- 🧑‍🤝‍🧑 Classifies gender from facial images (Male/Female)
- 📷 Real-time detection using webcam
- 🪟 GUI-based interface using Tkinter
- 🧪 Data preprocessing, augmentation, and CNN training
- 💾 Saves and loads trained models easily

---

## 🗂️ Project Structure

Gender_Detection_Model/
├── dataset/
├── gender_detection.model
├── New_train.py.ipynb
├── gender_gui.py
├── requirements.txt
└── README.md

---

## 🧠 Model Architecture

- 2D Convolution layers with ReLU activation  
- MaxPooling layers for feature downsampling  
- Dropout layers to prevent overfitting  
- Fully connected Dense layer with Softmax for classification  
- Optimizer: Adam  
- Loss Function: Categorical Crossentropy  

---

## 📊 Results

| Metric             | Value              |
|--------------------|--------------------|
| Validation Accuracy| ~95%               |
| Inference Speed    | Real-time (Webcam) |

---

## 🚀 Getting Started

### 🔧 Requirements

Install all dependencies:

```bash
pip install -r requirements.txt

for jupyter notebook
- jupyter
- scikit-learn

for another ide
- tensorflow>=2.10.0
- opencv-python
- numpy
- Pillow
- matplotlib


