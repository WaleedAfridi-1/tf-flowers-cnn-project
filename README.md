# tf-flowers-cnn-project
A deep learning project that classifies five types of flowers (Daisy, Dandelion, Rose, Sunflower, Tulip) using a Convolutional Neural Network trained on the TF-Flowers dataset from TensorFlow Datasets. Includes training pipeline, evaluation metrics, classification report, and scalable CNN design.




# 🌼 Flower Classification using CNN (TensorFlow)

This project uses a Convolutional Neural Network (CNN) to classify flower images into five categories using the **TF-Flowers dataset**. It leverages TensorFlow and TensorFlow Datasets to create a simple yet accurate deep-learning image classifier.

---

## 🚀 Features
✅ Uses real-world TF-Flowers dataset  
✅ CNN architecture with Conv2D & MaxPooling  
✅ Train/Test pipeline with batching & normalization  
✅ Classification report using sklearn  
✅ Achieved **~99% accuracy** ✅  

---

## 🧠 Dataset
Dataset: `tf_flowers` from TensorFlow Datasets  
Classes: Daisy 🌼 | Dandelion 🌿 | Rose 🌹 | Sunflower 🌻 | Tulip 🌷  

Images are resized to **128×128** and normalized before training.

---

## 🏗️ Model Architecture

- Conv2D (32 filters)
- MaxPooling2D
- Flatten
- Dense (64 neurons)
- Output Dense Layer (Softmax)

Optimizer: Adam  
Loss: Sparse Categorical Crossentropy  
Epochs: 5  
Batch Size: 32  

---

## 📊 Results

| Metric | Score |
|--------|------|
| Test Accuracy | ✅ 99.96% |

A full classification report is printed after evaluation using scikit-learn.

---

## 🧪 How to Run

```bash
pip install tensorflow tensorflow-datasets scikit-learn
python main.py
```

> Make sure GPU is available for faster training.

---

## 📌 Output Example

```
Test Accuracy: 0.9996
Classification Report:
Precision, Recall, F1 Score for 5 flower classes
```

---

## ✨ Future Improvements
- Data augmentation
- More convolutional layers
- Transfer learning (MobileNetV2 / EfficientNet)

---

## 🤝 Contribution
Pull requests are welcome! Feel free to fork and improve.

---

### ⭐ If you like this project, give it a star!
