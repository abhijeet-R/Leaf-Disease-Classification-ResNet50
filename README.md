# 🌿 Leaf Disease Classification using ResNet50

This project demonstrates how **Transfer Learning** can be used to classify plant leaf diseases using the **ResNet50** convolutional neural network. Instead of training a model from scratch, a pre-trained ResNet50 model is fine-tuned to recognize different leaf diseases, resulting in faster training and better accuracy.

The project is implemented as a Jupyter Notebook using **TensorFlow/Keras** and covers the complete workflow, from loading the dataset to training and evaluating the model.

---

## 📖 Overview

Early detection of plant diseases is important for improving crop health and reducing agricultural losses. In this project, a deep learning model is trained to identify diseases from leaf images.

The notebook includes:

* Dataset loading
* Image preprocessing
* Transfer learning with ResNet50
* Model training
* Performance evaluation
* Saving the trained model

---

## ✨ Features

* Image classification using **ResNet50**
* Transfer Learning with ImageNet weights
* Data preprocessing and normalization
* Training and validation pipeline
* Model evaluation
* Save the trained model for future predictions

---

## 🛠️ Tech Stack

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Jupyter Notebook

---
## 📊 Dataset

This project uses the **PlantVillage** dataset, which has been recreated using **offline data augmentation** from the original dataset.

### Dataset Overview

* Approximately **87,000 RGB images**
* **38 different classes** of healthy and diseased crop leaves
* Images are split into **80% training** and **20% validation** while preserving the original directory structure

The dataset covers multiple plant species and their corresponding diseases, making it suitable for training deep learning models for plant disease classification.


## 🧠 Model Architecture

The model is built using **ResNet50** as the feature extractor.

Architecture:

```text
Input Image
      │
      ▼
Preprocessing
      │
      ▼
ResNet50 (Pretrained on ImageNet)
      │
      ▼
Custom Classification Layers
      │
      ▼
Softmax Output Layer
      │
      ▼
Predicted Leaf Disease
```

---


Run the notebook cells sequentially to train the model.

---

## 📈 Training Pipeline

The notebook follows the following workflow:

1. Load the dataset
2. Preprocess the images
3. Load the pretrained ResNet50 model
4. Build a custom classification head
5. Train the model
6. Validate performance
7. Save the trained model

---

## 📦 Requirements

* Python 3.10+
* TensorFlow
* Keras
* NumPy
* Pandas
* Jupyter Notebook


