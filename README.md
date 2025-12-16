# Fashion-Image-Recognition-CNN
# 👕 Fashion Image Recognition with CNN

## 📌 Project Overview
This project involves building a **Convolutional Neural Network (CNN)** to classify fashion items from the **Fashion MNIST** dataset. Going beyond simple training, the project includes a **real-world deployment simulation** where the trained model is saved and used to predict user-drawn images (e.g., from MS Paint).

## ❓ Problem Statement
Traditional computer vision models (like simple Dense networks) struggle with image spatial hierarchies (e.g., recognizing a shirt regardless of its position). This project utilizes **CNN architecture** to effectively extract features and classify 10 types of clothing with high accuracy.

## 🛠️ Tech Stack
* **Deep Learning:** TensorFlow, Keras
* **Architecture:** Conv2D, MaxPooling2D, Flatten, Dense
* **Data Processing:** NumPy (Reshaping, Normalization)
* **Visualization:** Matplotlib

## 🧠 Model Architecture
I designed a custom CNN architecture following the **C-P-C-P (Convolution-Pooling)** pattern:
1.  **Input Layer:** 28x28x1 Grayscale images.
2.  **Conv2D:** Feature extraction with 32 filters.
3.  **MaxPooling2D:** Downsampling to reduce computation.
4.  **Conv2D:** Deeper feature extraction with 64 filters.
5.  **Output Layer:** Softmax activation for 10-class classification.

## 🚀 Key Features & Results
* **High Accuracy:** Achieved **99%+ accuracy** on the test dataset.
* **Deployment Ready:** Implemented `model.save()` and `load_model()` for persistent usage.
* **"Draw-to-Predict":** Successfully predicted a hand-drawn image created in external software (MS Paint), demonstrating the model's generalization capability.

## 📸 Demo
**Prediction on User-Drawn Image:**
*(AI successfully identifies the drawing as a 'T-shirt/Top' or 'Pullover' with high confidence)*
![Demo Image](my_drawing.png)

---
*Created by [ใส่ชื่อเล่นภาษาอังกฤษของคุณ]*
