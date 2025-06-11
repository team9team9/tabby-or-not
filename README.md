# tabby-or-not

# TabbyCat Classifier & Location Predictor

This project aims to predict **whether a cat is a Tabby or not**, and **whether it's at home or not**, based on image data and environmental conditions.

## Project Overview

The system is divided into two main tasks:

1. **Tabby Classification (Image-based)**
2. **Location Prediction (Environment-based)**

---

## Models Used

### 1. **CNN + KNN for Tabby Classification**
- A **Convolutional Neural Network (CNN)** is used to **extract feature vectors** from cat images.
- These feature vectors are then passed to a **K-Nearest Neighbors (KNN)** classifier to decide **if the cat is a Tabby**.

### 2. **Random Forest for Location Prediction**
- A **Random Forest classifier** is trained to predict whether the Tabby is **at home or not**, using the following input features:
  - **Season**
  - **Time of day**
  - **Rainy day** (Yes/No)
  - **Noise level**

---

## PCA Visualization

To better understand the CNN feature space, we applied **Principal Component Analysis (PCA)** to reduce high-dimensional vectors into 2D for visualization. This helps visualize how external conditions seperate wether the Tabby is at home or not

---

## Technologies Used

- Python
- Google Colab
- Scikit-learn (KNN, Random Forest, PCA)
- PyTorch or TensorFlow (CNN)
- Matplotlib (visualization)


---

## How to Run

1. Preprocess the image dataset
2. Train the CNN to extract features
3. Use KNN to classify Tabby vs Not Tabby
4. Use Random Forest to predict location
5. Visualize results using PCA

---

## Results

- Achieved **100% accuracy** on test data for Tabby classification.
- Predict wether the Tabby is at home or not based on few conditions.
- PCA shows clear clustering between Tabby and non-Tabby images.

---

## Team Members

Mahirah, Intan, Hanbyeol

---


