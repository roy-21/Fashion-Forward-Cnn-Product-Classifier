# 👗 Fashion Forward: CNN Product Classifier

An AI-powered image classification system that automatically categorizes clothing items using Convolutional Neural Networks (CNNs).

---

## 📌 Project Overview

Fashion Forward is an AI-based e-commerce platform aiming to automate product tagging.
This project builds a CNN model to classify clothing images into categories such as:

* T-shirt / Top
* Trouser
* Pullover
* Dress
* Coat
* Sandal
* Shirt
* Sneaker
* Bag
* Ankle boot

Dataset used: **FashionMNIST**

---

## ⚙️ Features

### 🧠 CNN Model

* 1 Convolutional layer
* ReLU activation
* MaxPooling
* Fully connected layer for classification

---

### 🏋️ Training

* Optimizer: Adam
* Loss Function: CrossEntropyLoss
* Epochs: 1 (fast prototyping)

---

### 📊 Evaluation Metrics

* Accuracy
* Precision (per class)
* Recall (per class)

---

## 📊 Technologies Used

* Python 🐍
* PyTorch 🔥
* Torchvision 👁️
* TorchMetrics 📏

---

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/fashion-forward-cnn-product-classifier.git
cd fashion-forward-cnn-product-classifier
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run training & evaluation

```bash
python src/train.py
python src/evaluate.py
```

---

## 📈 Output

The model will generate:

* ✅ Predictions on test dataset
* ✅ Accuracy score
* ✅ Precision (per class list)
* ✅ Recall (per class list)

Example:

```
Accuracy: 0.83
Precision: [0.80, 0.91, ...]
Recall: [0.78, 0.89, ...]
```

---

## 📁 Project Workflow

1️⃣ Load dataset (FashionMNIST)
2️⃣ Define CNN model
3️⃣ Train model (1 epoch)
4️⃣ Predict on test data
5️⃣ Evaluate performance

---

## 🎯 Future Improvements

* Add deeper CNN architecture
* Train for more epochs
* Use GPU acceleration
* Deploy as an API or web app
* Add real product images instead of FashionMNIST

---

## ⭐ If you like this project

Give it a ⭐ on GitHub and share it!

---



## 👨‍💻 Author

**Sojib Chandra Roy**
📧 [rcsojib.cse1@gmail.com](mailto:rcsojib.cse1@gmail.com)

---
