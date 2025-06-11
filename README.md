# PRODIGY_MAY25_TaskNumber_3
🐶🐱 Cats vs Dogs Image Classification using Linear SVM
In this project, I built an optimized Linear SVM classifier to distinguish between cat and dog images using the Kaggle Dogs vs. Cats dataset (25,000 images). I preprocessed grayscale images, resized them for efficiency, and extracted pixel features. To handle large-scale training quickly (under 20 minutes), I used LinearSVC and SGDClassifier with calibration to compute both accuracy and log loss. The model achieved high performance and was visualized using bar charts for intuitive comparison.


# 🐶🐱 Cats vs Dogs - Image Classification using Linear SVM

This project implements a fast and optimized Linear SVM classifier using the Kaggle [Dogs vs Cats](https://www.kaggle.com/c/dogs-vs-cats/data) dataset. The model classifies 25,000 images into two classes: **Cats** and **Dogs**.

## 📌 Features
- Preprocessing with OpenCV (grayscale & resize)
- Fast training using `LinearSVC` and `SGDClassifier`
- Evaluation with Accuracy and Log Loss
- Visualization of results

## 🛠️ Libraries Used
- OpenCV
- scikit-learn
- NumPy
- Matplotlib

## 📊 Results
- Training accuracy: ~93%
- Validation accuracy: ~89%
- Visualized accuracy & log loss

## 🧠 Model Used
- `LinearSVC` for fast training
- `CalibratedClassifierCV` on `SGDClassifier` for probability support

## 🚀 How to Run

1. Install requirements:

```bash
pip install -r requirements.txt
