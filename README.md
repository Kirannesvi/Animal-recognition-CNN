
# 🧠 CNN-Based Image Classification

[![Python](https://img.shields.io/badge/Python-3.7%2B-blue.svg)](https://www.python.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange.svg)](https://www.tensorflow.org/)
[![Colab](https://img.shields.io/badge/Run%20in-Colab-blue?logo=google-colab)](https://colab.research.google.com/)

## 📌 Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Usage](#usage)
- [Results](#results)
- [Dependencies](#dependencies)
- [Author](#author)

---

## 📘 Overview

This project implements an image classification pipeline using **Convolutional Neural Networks (CNNs)** in TensorFlow/Keras. The notebook is designed to run in **Google Colab** and can classify images from a dataset into distinct categories.

---

## 🗂️ Dataset

The dataset is expected to be organized in the following directory structure:

```
/dataset/
    /train/
        /class_1/
        /class_2/
        ...
    /test/
        /class_1/
        /class_2/
        ...
```

- Images are automatically resized and normalized.
- Data is loaded using `ImageDataGenerator`.

---

## 🧠 Model Architecture

The CNN includes:
- Convolutional layers (`Conv2D`) with ReLU activation
- Max pooling layers (`MaxPooling2D`)
- Flatten and Dense layers
- Output layer with Softmax activation for multi-class classification

---

## 🚀 Usage

1. **Open in Colab**  
   Click here to open: [📓 ML_CNN.ipynb](https://colab.research.google.com/)

2. **Mount Google Drive** (if needed)
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
   ```

3. **Set dataset paths and run all cells**

4. **Evaluate the model**
   - Accuracy and loss plots
   - Confusion matrix (optional)

---

## 📊 Results

- The training and validation accuracy/loss graphs are plotted.
- Final model accuracy is displayed on the test set.
- Example predictions can also be visualized.

---

## 📦 Dependencies

- Python ≥ 3.7
- TensorFlow ≥ 2.x
- NumPy
- Keras
- Matplotlib
- OpenCV (optional)

Install via pip (if needed):
```bash
pip install tensorflow keras matplotlib opencv-python
```

---

## ✍️ Author

**Kiran Nesvi**  
📧 [kirannesvi3@gmail.com](mailto:kirannesvi3@gmail.com)  
🎓 Electronics Engineering Student

---
