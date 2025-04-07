# Brain Tumor Detection using CNN 🧠🔬

This project uses a custom-built Convolutional Neural Network (CNN) to detect brain tumors from MRI images. Built using TensorFlow and Keras, the model classifies MRI scans as either `Tumor` or `No Tumor`.

## 🗂 Dataset
Dataset used: [Kaggle Brain Tumor Detection MRI](https://www.kaggle.com/datasets/abhranta/brain-tumor-detection-mri)

It contains two folders:
- `yes/` – MRI images with tumor
- `no/` – MRI images without tumor

## 🧠 Model
A custom CNN with:
- 3 Convolutional blocks
- BatchNormalization & MaxPooling
- Dense + Dropout for classification

## 🔍 Features
- Train/validation split
- Image augmentation
- Evaluation with classification report & confusion matrix
- Predict on a single custom image
