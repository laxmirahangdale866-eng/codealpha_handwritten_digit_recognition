# ✍️ Handwritten Character Recognition (MNIST)

## 📌 Project Overview
This project is a Machine Learning model that recognizes handwritten digits (0–9) using the MNIST dataset. It is built using TensorFlow and Keras with a simple Neural Network architecture.

## 🚀 Features
- Recognizes handwritten digits accurately
- Uses MNIST dataset for training and testing
- Simple and efficient Neural Network model
- Visualization of input images
- Model evaluation using accuracy score

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

## 📊 Dataset
- MNIST dataset (60,000 training images + 10,000 testing images)
- Each image size: 28 × 28 pixels

## 🧠 Model Architecture
- Input Layer (Flatten 28×28)
- Dense Layer (128 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

## ⚙️ How It Works
1. Load MNIST dataset
2. Normalize pixel values
3. Build Sequential Neural Network
4. Train model with training data
5. Predict test data
6. Evaluate accuracy

## 📈 Output
- Model predicts digits from test images
- Accuracy score calculated using sklearn

## 📷 Sample Output
Displays handwritten digit image and predicted value.

## ▶️ How to Run
pip install tensorflow numpy matplotlib scikit-learn
