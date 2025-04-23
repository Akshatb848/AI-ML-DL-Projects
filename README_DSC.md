# Degraded Script Classifier

This project focuses on the **identification of degraded Devanagari and Bangla script characters** using Convolutional Neural Network (CNN) frameworks. It is part of a broader effort in OCR and document digitization systems for Indian languages.

## 🔍 Problem Statement

Accurately identifying handwritten or degraded texts in Indic languages is challenging due to variations in style, noise, and distortion. This project addresses that by building a robust classifier using deep learning techniques.

## 📦 Dataset

- **Dataset Used**: Ekush dataset (nested zip archives with over 600k images).
- Scripts: Bangla and Devanagari.
- Classes: Multiple characters per script with varying levels of degradation.

## 🧠 Models Used

- **VGG-16** (Best Accuracy: 99.34%)
- **DenseNet-121**
- **AlexNet**
- **ResNet-50**

## 🛠️ Tools & Libraries

- Python
- TensorFlow / Keras
- Google Colab
- OpenCV, NumPy, Matplotlib
- Git for version control

## 🚀 Features

- Preprocessing of large nested zip datasets
- Custom image loading pipeline
- Training CNN models for multi-class script classification
- Accuracy comparison across architectures

## 📈 Results

| Model      | Accuracy  |
|------------|-----------|
| VGG-16     | **99.34%** |
| DenseNet-121 | 98.89% |
| AlexNet    | 97.75% |
| ResNet-50  | 98.60% |

## 📂 File Structure

