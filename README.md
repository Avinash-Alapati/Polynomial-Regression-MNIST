# 🧠 Polynomial Regression for Handwritten Digit Classification

This project demonstrates how **Polynomial Regression** with **Lasso regularization** can be used to classify handwritten digits from a reduced version of the **MNIST dataset**.

---

## 📌 Problem Statement

> Apply polynomial feature transformation and Lasso regression to classify digits from the MNIST dataset. The dataset is reduced by resizing each 28x28 image to 14x14 and limiting the sample size to 10,000 images.

---

## 🗂️ Project Overview

- 🔢 Dataset: [MNIST](http://yann.lecun.com/exdb/mnist/) (via `tensorflow.keras.datasets`)
- 🧮 Technique: Polynomial Features + Lasso Regression
- 📉 Model Type: Regression-based classification
- 🔍 Evaluation: Accuracy, Classification Report, Confusion Matrix
- 📊 Visualization: Ground truth vs. Predicted digit images

---

## 📊 Sample Output

🎯 Accuracy: 65.42%



📄 Classification Report:

       0       0.84      0.87      0.85       194
       1       0.75      0.92      0.83       217
       2       0.68      0.55      0.61       197
       3       0.59      0.61      0.60       212
       4       0.62      0.67      0.65       195
       5       0.59      0.44      0.50       187
       6       0.74      0.81      0.78       204
       7       0.74      0.72      0.73       209
       8       0.47      0.54      0.50       191
       9       0.54      0.52      0.53       194


> *(Accuracy and scores will vary slightly depending on data split and Lasso regularization strength)*

---

## 🧰 Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow (for MNIST dataset)
- Scikit-image (for resizing images)

---

## 📦 Installation

1. 🔧 Clone the repository:
   ```bash
   git clone https://github.com/your-username/mnist-polynomial-regression.git
   cd mnist-polynomial-regression

2. 🐍 Create a virtual environment (optional but recommended):

    python -m venv venv
    source venv/bin/activate  # or venv\Scripts\activate on Windows
3. 📥 Install dependencies:
     pip install -r requirements.txt
4. 🚀 Run the project:
   python main.py

📁 Directory Structure

  mnist-polynomial-regression/
├── main.py               # Main script
├── README.md             # Project description
├── requirements.txt      # Dependencies

