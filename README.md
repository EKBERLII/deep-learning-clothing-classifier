# deep-learning-clothing-classifier
A Convolutional Neural Network (CNN) model built with TensorFlow/Keras to classify clothing images into 3 distinct categories.
# 👕 Clothing Classification using CNN (3 Categories)

This repository contains a Deep Learning project that utilizes a Convolutional Neural Network (CNN) to automatically classify images of clothing into three distinct categories (e.g., Shirts, Trousers, and Dresses). The model is trained on image datasets using data augmentation techniques to improve accuracy.

---

## 🚀 Features
* **Custom CNN Architecture:** Built with multiple Convolutional, MaxPooling, Dropout, and Dense layers.
* **Data Augmentation:** Implemented image rotation, zoom, and horizontal flips to prevent overfitting.
* **Performance Tracking:** Visualization of Training vs. Validation Loss and Accuracy curves.
* **Prediction Pipeline:** A function to upload any custom clothing image and get the predicted category with confidence scores.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python
* **Deep Learning Framework:** TensorFlow / Keras
* **Image Processing:** OpenCV, Pillow (PIL)
* **Data Handling & Visualization:** NumPy, Matplotlib, Seaborn

---

## 📂 Project Structure
```text
├── clothing_classification_cnn.ipynb  # Main Google Colab Notebook
├── sample_images/                     # Test images for prediction demos
└── README.md                          # Project documentation



## 💻 How to Run

You can run this project directly in Google Colab:

### Option 1: Run in Google Colab (Recommended)
1. Download the `CNN.ipynb` file from this repository.
2. Go to [Google Colab](https://colab.research.google.com/) and upload the notebook.
3. If your dataset is hosted on Kaggle or Google Drive, ensure you mount the drive or configure API tokens as instructed inside the notebook.
4. Run the cells to train and test the model.
