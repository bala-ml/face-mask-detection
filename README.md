# 😷 Face Mask Detection using Deep Learning

## 📌 Project Overview

This project focuses on automatically detecting whether a person is wearing a face mask or not using Deep Learning and Computer Vision techniques.

Face mask detection became an important real-world application during the COVID-19 pandemic, helping enforce public health safety rules in public spaces such as airports, offices, hospitals, and transportation systems.

The model is trained on a dataset of labeled images and learns to classify faces into two categories:

- With Mask
- Without Mask

The system uses a Convolutional Neural Network (CNN) to extract features from images and perform classification.

---

## 🎯 Problem Statement

Build a machine learning model that can classify images of faces as:

0 = With Mask  
1 = Without Mask

The goal is to assist automated monitoring systems that ensure people follow mask safety protocols.

---

## 📊 Dataset Description

Dataset: Face Mask Dataset

The dataset contains images of human faces categorized into two classes:

- Faces with masks
- Faces without masks

Dataset Source  
https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

---

## 🧾 Attribute Information

### Dataset Classes

1. With Mask (0)
2. Without Mask (1)

Each image represents a human face and is processed before feeding into the deep learning model.

---

## 📈 Dataset Insights

- Image dataset with two classification categories
- Images resized for model training
- Data converted into numerical arrays
- Labels encoded for classification
- Suitable for binary image classification problems

---

## ⚙️ Tech Stack

Python  
NumPy  
Matplotlib  
OpenCV  
TensorFlow  
Keras  
Scikit-learn  

---

## 🔄 Machine Learning / Deep Learning Pipeline

1. Import required libraries
2. Load the face mask image dataset
3. Create labels for image classes
4. Preprocess images (resize & normalize)
5. Convert images into NumPy arrays
6. Split dataset into training and testing sets
7. Build CNN model using Keras
8. Train the deep learning model
9. Evaluate model performance
10. Predict mask vs no-mask images

---

## 🧠 Model Architecture

The project uses a Convolutional Neural Network (CNN) including:

- Convolution Layers (Conv2D)
- Activation Functions (ReLU)
- Pooling Layers
- Flatten Layer
- Dense Fully Connected Layers
- Output Layer for Binary Classification

---

## 📊 Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Loss
- Training vs Validation Performance
- Prediction results on test images

---

## 📂 Project Structure

```
face-mask-detection/
│
├── data/
│   └── with_mask
│   └── without_mask
│
├── notebook/
│   └── face_mask_detection.ipynb
│
├── requirements.txt
└── README.md
```

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/bala-ml/face-mask-detection.git

---

### 2️⃣ Install Dependencies

pip install -r requirements.txt

---

### 3️⃣ Run the Notebook

Open Jupyter Notebook and run:

face_mask_detection.ipynb

---

## 💡 Future Improvements

- Real-time mask detection using Webcam
- Deploy model using Flask / FastAPI
- Improve accuracy using Transfer Learning (MobileNet, ResNet)
- Deploy as web application
- Integrate with CCTV surveillance systems

---

## 👤 Author

Balaji I  
Aspiring Machine Learning Engineer  
India

---

This project demonstrates the practical application of Deep Learning and Computer Vision for public health safety and automated monitoring systems.