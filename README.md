🧠 CIFAR-10 Image Recognition using Convolutional Neural Networks (CNN)

This project demonstrates an end-to-end **image recognition system** using the **CIFAR-10 dataset**, which contains 60,000 32x32 color images in 10 different classes.

📌 Objective

To build and train a Convolutional Neural Network (CNN) that classifies images into one of the 10 predefined categories:
- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

🧾 Dataset

- 📦 Dataset: CIFAR-10
- 🖼️ Total Images: 60,000
- 🔍 Image Size: 32x32 pixels (RGB)
- 📚 Classes: 10
- 📂 Training Samples: 50,000
- 📂 Testing Samples: 10,000


🔧 Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib

---

 🚀 How It Works

 1. 📥 Load Dataset
```python
from tensorflow.keras.datasets import cifar10
(X_train, y_train), (X_test, y_test) = cifar10.load_data()
