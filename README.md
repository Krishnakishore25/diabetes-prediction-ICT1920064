# diabetes-prediction-ICT1920064
# 🧠 Neural Network for Diabetes Prediction

This project aims to develop a neural network model using the **Pima Indian Diabetes Dataset** to predict whether a patient is diabetic or not. The model follows a complete machine learning pipeline including preprocessing, training, hyperparameter tuning, and evaluation.

---

## 📊 Project Description

The dataset contains diagnostic measurements for female patients of Pima Indian heritage, aged 21 or older. Features include glucose levels, insulin, BMI, number of pregnancies, and more.

The core objective is to build a **feedforward neural network** using **TensorFlow** and **Keras** to accurately classify patients as diabetic (`1`) or non-diabetic (`0`). The model is evaluated based on accuracy, precision, recall, F1-score, and AUC, and uses techniques such as **dropout**, **L2 regularization**, and **early stopping** to avoid overfitting.

---

## ⚙️ Setup Instructions

1. **Clone the Repository** (or download the files):
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
   cd diabetes-prediction

2.**Install Required Libraries**:
It is recommended to use a virtual environment.
pip install -r requirements.txt

3.**(Optional) Run in Google Colab(NB:I used Colab for my Experiments)**:
If you're using Google Colab, simply upload the .ipynb file and skip installation — Colab has most packages pre-installed.
