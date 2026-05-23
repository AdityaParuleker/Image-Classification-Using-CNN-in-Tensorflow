

# 👕 Fashion MNIST Image Classification using CNN and TensorFlow

A Deep Learning based Image Classification project built using Convolutional Neural Networks (CNN) with TensorFlow and Keras.  
This project classifies Fashion MNIST clothing images into 10 different categories and deploys the trained model as an interactive Streamlit web application.

---

# 🚀 Project Overview

This project demonstrates:

- Image classification using CNN
- Deep Learning model training with TensorFlow/Keras
- Data preprocessing and normalization
- Model evaluation and prediction
- Model deployment using Streamlit
- Public deployment from Google Colab using Ngrok

The model is trained on the Fashion MNIST dataset containing grayscale images of clothing items.

---

# 📂 Dataset

Dataset Used: Fashion MNIST

Fashion MNIST contains 70,000 grayscale images (28x28 pixels) across 10 clothing categories.

Classes:

| Label | Category |
|------|------|
| 0 | T-shirt/top |
| 1 | Trouser |
| 2 | Pullover |
| 3 | Dress |
| 4 | Coat |
| 5 | Sandal |
| 6 | Shirt |
| 7 | Sneaker |
| 8 | Bag |
| 9 | Ankle boot |

---

# 🧠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL (Python Imaging Library)
- Streamlit
- Ngrok
- Google Colab

---

# 🏗️ CNN Architecture

The Convolutional Neural Network includes:

- Convolution Layers
- MaxPooling Layers
- Flatten Layer
- Dense Fully Connected Layers
- Softmax Output Layer

The model is trained using:

- Adam Optimizer
- Sparse Categorical Crossentropy Loss
- Accuracy Evaluation Metric

---

# 📊 Features

✅ CNN-based image classification  
✅ Real-time image prediction  
✅ Streamlit web application  
✅ TensorFlow/Keras model saving  
✅ Public deployment support using Ngrok  
✅ Interactive prediction interface  

---

# 📁 Project Structure
```bash
├── cnn_model.keras
├── Image_Classification_CNN.ipynb
└── README.md
```

---


# 🌐 Streamlit Deployment using Google Colab

This project also supports deployment directly from Google Colab using:

- Streamlit
- Pyngrok

Deployment Steps:

1. Train and save the model
2. Run deployment section code at end of file
3. Start Streamlit server
4. Create public URL using Ngrok

---

# 💾 Save Trained Model

```python
model.save("cnn_model.keras")
```

---

# 📥 Download Trained Model

```python
from google.colab import files

files.download("cnn_model.keras")
```

---

# 📸 Application Preview

The web application allows users to:

- Upload clothing images
- Predict clothing category
- View prediction confidence scores
- Display class probabilities

---


# 🎯 Learning Outcomes

Through this project, you can learn:

- CNN fundamentals
- TensorFlow/Keras workflow
- Image preprocessing
- Model training and evaluation
- Streamlit deployment
- Real-time AI application deployment

---

